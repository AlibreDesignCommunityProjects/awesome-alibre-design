# Contributing

Open an issue or pull request to add a resource, correct a description, or report a broken link in [Awesome Alibre Design](README.md).

## Inclusion criteria

- Explain how the resource helps Alibre Design users or developers.
- Link to a public product page, repository, package listing, channel, or discussion. For paid resources, let readers review the features before buying.
- Describe what the resource does in one sentence. Mention limits that affect its use, such as stub implementations or required Alibre versions.
- Use the author's or publisher's canonical URL without tracking parameters. For commercial add-ons, link the name to the product website and include a forum link when available.
- Add a resource once, in the most useful section. Keep related website and discussion links in the same entry.
- Open the link and check its content before submitting it. Avoid placeholders, affiliate links, and unsupported claims.

You may submit your own work. State your connection to it in the issue or pull request.

## Entry format

Use a named Markdown link followed by a brief description:

```markdown
- [Resource Name](https://example.com/) - What the resource does and how it relates to Alibre Design.
```

For a product with a forum discussion:

```markdown
- [Product Name](https://example.com/product/) - Brief description. [Forum](https://www.alibre.com/forum/index.php?threads/example.12345/).
```

Replace the example names and URLs with the resource's details. Write descriptions in your own words.

## Choosing a section

- **Official:** Alibre's website, channels, documentation, and tools, including official releases and guides posted on its forum. Keep the G2/G3 Spline Continuity Add-on here.
- **Packages:** Installable Python and .NET packages.
- **YouTube:** Creators with relevant Alibre content. Broader channel descriptions can reflect their stated focus.
- **GitHub Projects:** Source repositories and collections. Use one organization link for AlibreDesignCommunityProjects in this section.
- **Add-ons:** Community tools and commercial products, grouped under the matching subsection.
- **Resellers:** Alibre resellers and regional resources.
- **Extensions:** Editor extensions, separated by Visual Studio and Visual Studio Code.
- **Interoperability and Conversion:** Import, export, and file conversion tools, including source repositories.

Update the contents when adding, renaming, or removing a heading. Add a section only when you have a resource for it.

## Reporting a broken link

Include the entry name, URL, and what happened when you opened it. For a replacement URL, explain how you confirmed it belongs to the same project or publisher. Note any login requirement, outage, or automated-request block.

## Link checks

The [Check links workflow](.github/workflows/check-links.yml) checks Markdown links on pull requests and pushes that change documentation or checker configuration. It has a Monday schedule and a manual trigger. GitHub requires the workflow file on the default branch for [scheduled and manual runs](https://docs.github.com/en/actions/reference/workflows-and-actions/events-that-trigger-workflows). Check the job summary for failures before requesting review.

To check links on your computer, install [lychee](https://github.com/lycheeverse/lychee) v0.24.2 and run from the repository root:

```sh
lychee --config .lychee.toml --no-progress './**/*.md'
```

We exclude Alibre's homepage and forum URLs in [.lycheeignore](.lycheeignore) because they block automated requests. The checker cannot verify excluded links; open them in a browser before submitting changes. For new exceptions, confirm that the page works and record the reason beside the URL pattern. Keep each pattern as narrow as the block allows.

## License

By contributing original text to this repository, you agree to dedicate it under [CC0 1.0 Universal](LICENSE). Linked resources retain their own licenses and terms.
