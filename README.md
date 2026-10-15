# Awesome Alibre Design

> A curated list of tools, projects, tutorials, and community resources for **Alibre Design**.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Status: Beta](https://img.shields.io/badge/status-beta-orange)

**Beta:** We are checking links, descriptions, and each resource's relevance to Alibre Design. See [Contributing](CONTRIBUTING.md) to suggest additions or corrections.

## Contents

- [Awesome Alibre Design](#awesome-alibre-design)
  - [Contents](#contents)
  - [Official](#official)
  - [Packages](#packages)
    - [Python / PyPI](#python--pypi)
    - [.NET / NuGet](#net--nuget)
  - [YouTube](#youtube)
    - [Community Creators](#community-creators)
  - [GitHub Projects](#github-projects)
  - [Add-ons](#add-ons)
    - [Community Add-ons and Tools](#community-add-ons-and-tools)
    - [Commercial Add-ons](#commercial-add-ons)
  - [Resources](#resources)
  - [Resellers](#resellers)
  - [Extensions](#extensions)
    - [Visual Studio](#visual-studio)
    - [Visual Studio Code](#visual-studio-code)
  - [Interoperability and Conversion](#interoperability-and-conversion)
  - [Contributing](#contributing)
  - [License](#license)

## Official

- [Alibre](https://www.alibre.com/) - Official website for Alibre Design products, support, and learning resources.
- [Alibre LLC](https://www.youtube.com/@AlibreLLC) - Official Alibre YouTube channel with product demonstrations, tutorials, and feature overviews.
- [Alibre Forum](https://www.alibre.com/forum/index.php) - Alibre's forum for modeling, scripting, add-ons, and technical support.
- [Alibre API Resources](https://www.alibre.com/api/) - API documentation, sample add-ons, project templates, and Alibre Script development resources.
- [Setting Up AI to Develop Add-ons](https://www.alibre.com/forum/index.php?threads/setting-up-ai-to-develop-add-ons.27092/#post-187168) - Forum guide to setting up AI tools for Alibre Design add-on development.
- [G2/G3 Spline Continuity Add-on](https://www.alibre.com/forum/index.php?threads/addon-for-g2-g3-spline-continuity.27098/#post-187255) - Alibre Design add-on for G2 and G3 spline continuity, with discussion on the Alibre forum.

## Packages

Installable libraries and packages for Alibre Design development and automation.

### Python / PyPI

- [alibrex](https://pypi.org/project/alibrex/) - Python package for working with Alibre Design and AlibreX.

### .NET / NuGet

- [AlibreObjectModel](https://www.nuget.org/packages/AlibreObjectModel) - .NET object-model wrapper for the Alibre Design CAD API, covering sessions, sketches, features, parameters, and topology.
- [AlibreObjectModel.Mcp](https://www.nuget.org/packages/AlibreObjectModel.Mcp) - Model Context Protocol (MCP) server exposing Alibre Design parts, sketches, features, and parameters as tools over stdio.
- [AlibrePDMObjectModel](https://www.nuget.org/packages/AlibrePDMObjectModel) - .NET wrapper for the Alibre PDM vault API; requires Alibre Design.
- [AlibrePDMObjectModel.Mcp](https://www.nuget.org/packages/AlibrePDMObjectModel.Mcp) - MCP server exposing Alibre PDM safes, projects, files, properties, classes, and versions as tools over stdio.
- [AlibreScriptWrapper](https://www.nuget.org/packages/AlibreScriptWrapper) - Stub wrapper for the AlibreScript API; methods are not yet implemented.
- [GetInstalledAddons.Tool](https://www.nuget.org/packages/GetInstalledAddons.Tool) - .NET command-line tool that prints the registry entries Alibre Design uses to register add-ons.

## YouTube

### Community Creators

- [Ex Machina Engineering](https://www.youtube.com/@ExMachinaEngineering) - Engineering and Alibre-related CAD content.
- [HaroldL](https://www.youtube.com/channel/UCtaUi77CAkSMNHpflewcfOQ) - Practical Alibre CAD and sheet metal tutorials demonstrating powerful modeling techniques, SolidWorks-comparable workflows, and real-world part creation for users of all experience levels.
- [stephensmitchell](https://www.youtube.com/@stephensmitchell) - Alibre development, automation, programming, and technical content.
- [Joko Engineering](https://www.youtube.com/@JokoEngineeringhelp) - CAD and engineering tutorials including Alibre Design material.
- [Too Tall Toby](https://www.youtube.com/@TooTallToby) - CAD modeling, challenges, and educational content.
- [WeekdayWeekend](https://www.youtube.com/channel/UCZ16aVz3Mpycxf36s5QGOVw) - Videos about CAD, 3D printing, and other hobbies, with occasional livestreams of workshop model solves and video games.
- [IQ Workshop](https://www.youtube.com/channel/UCJ5IFthfhbmiqHCMakgQysw) - Steve builds projects with CAD, 3D printing, electronics, laser cutting, and hobby CNC, sharing design changes and failed attempts along the way.

## GitHub Projects

Source repositories, scripts, utilities, and add-ons related to Alibre Design. See [Interoperability and Conversion](#interoperability-and-conversion) for file conversion projects.

- [AlibreDesignCommunityProjects](https://github.com/AlibreDesignCommunityProjects) - Community repositories for Alibre Design add-ons, scripts, examples, and development tools.
- [bolsover/UtilitiesForAlibre](https://github.com/bolsover/UtilitiesForAlibre) - C# utilities for Alibre Design.
- [bolsover/AlibreBOM](https://github.com/bolsover/AlibreBOM) - C# bill-of-materials utility for Alibre Design.
- [bolsover/AlibreShortcuts](https://github.com/bolsover/AlibreShortcuts) - Displays Alibre command shortcuts in list and keyboard views.
- [bolsover/DataBrowserForAlibre](https://github.com/bolsover/DataBrowserForAlibre) - C# data browser for Alibre.
- [Karl690/AlibrePartInjector](https://github.com/Karl690/AlibrePartInjector) - Inserts a part into an open Alibre assembly from the command line.
- [ftkalcevic/AlibreGears](https://github.com/ftkalcevic/AlibreGears) - C# tools for creating gears in Alibre Design; bevel gears are a work in progress.
- [LemonExplosive/AlibreCadScripts](https://github.com/LemonExplosive/AlibreCadScripts) - Community Python scripts for Alibre CAD.
- [EngineeredModern/alibre-dovetail-joint](https://github.com/EngineeredModern/alibre-dovetail-joint) - Sliding dovetail joint add-on for Alibre Design.

## Add-ons

### Community Add-ons and Tools

- [Cable Routing in Alibre](https://www.alibre.com/forum/index.php?threads/cable-routing-in-alibre.27067/) - Forum discussion about routing cables in Alibre Design.
- [Auto Generate Assembly Drawings](https://www.alibre.com/forum/index.php?threads/auto-generate-assembly-drawings-in-alibre.27024/#post-186926) - Forum discussion about automation for generating assembly drawings.
- [Bend Complex Geometry](https://www.alibre.com/forum/index.php?threads/bend-a-complex-geometry-along-a-path-and-around-an-axis.27049/) - Forum discussion about bending geometry along a path or around an axis.
- [Fillet Between Planes](https://www.alibre.com/forum/index.php?threads/my-fillet-between-planes-add-on-bonus-how-to-make-an-isogrid-pattern.27005/) - Forum discussion about fillet add-on and isogrid workflow.
- [Sketch2DXF](https://www.alibre.com/forum/index.php?threads/sketch2dxf.26921/) - Community sketch-to-DXF tool.
- [DXF Flat Pattern Export](https://www.alibre.com/forum/index.php?threads/dxf-flat-pattern-export.27114/#post-187377) - Community tool for exporting DXF flat patterns.

### Commercial Add-ons

- [LGP Renderer for Alibre Design](https://liquidgravity.us/store_test/index.php/lgp-renderer-for-alibre-design/) - Renderer add-on for Alibre Design from Liquid Gravity Productions. [Forum](https://www.alibre.com/forum/index.php?threads/lgp-renderer-add-on-for-alibre-design.27071/).
- [Rapid Parts](https://delta-eng.com/) - Fastener creation tool from Delta Engineering with an Alibre plugin. [Forum](https://www.alibre.com/forum/index.php?threads/rapid-parts.26197/).
- [CompuPortAD](https://www.compupal.biz/compuportad/) - Adds mesh import, export, and simplification tools to the Alibre Design Part workspace. [Forum](https://www.alibre.com/forum/index.php?threads/compuportad.26411/).
- [Frame Builder](https://liquidgravity.us/store_test/index.php/alibre-design-frame-builder/) - Creates structural frames from profile libraries, with tools for mitering, trimming, extending, and updating members. [Forum](https://www.alibre.com/forum/index.php?threads/release-frame-builder-v2_6_1.21412/).
- [PolySTEP Converter](https://www.polystep.se/) - Converts polygon meshes to STEP, with mesh repair and 3D-printing analysis tools. [Forum](https://www.alibre.com/forum/index.php?threads/new-version-of-polystep-converter.26414/).

## Resources

Alibre Forum resource pages. The label marks the forum source, including when the same project is listed in another section.

- [Set Color from Material](https://www.alibre.com/forum/index.php?resources/set-color-from-material.150/) (Alibre Forum Resource) - Script that sets the part color from its material.
- [Alibre Property Explorer](https://www.alibre.com/forum/index.php?resources/alibre-property-explorer.149/) (Alibre Forum Resource) - Script that browses Alibre part properties.
- [ToolBoxed_RecTube](https://www.alibre.com/forum/index.php?resources/toolboxed_rectube.148/) (Alibre Forum Resource) - Toolbox part for rectangular tube.
- [stepalibre's Resources](https://www.alibre.com/forum/index.php?resources/stepalibres-resources.145/) (Alibre Forum Resource) - Documentation index of stepalibre's resources.
- [AlibreObjectModel, AlibreScriptWrapper](https://www.alibre.com/forum/index.php?resources/alibreobjectmodel-alibrescriptwrapper.147/) (Alibre Forum Resource) - Development libraries for the Alibre object model and Alibre Script.
- [Alibre Design Extensions for Visual Studio](https://www.alibre.com/forum/index.php?resources/alibre-design-extensions-for-visual-studio.143/) (Alibre Forum Resource) - Visual Studio extension for Alibre Design.
- [Add-on that allows conversion STL->STP and import](https://www.alibre.com/forum/index.php?resources/add-on-that-allows-conversion-stl-stp-and-import.140/) (Alibre Forum Resource) - Add-on that converts STL to STEP and imports it.
- [Human_Model_Articulated](https://www.alibre.com/forum/index.php?resources/human_model_articulated.146/) (Alibre Forum Resource) - Articulated human 3D model.
- [The Tool Store](https://www.alibre.com/forum/index.php?resources/the-tool-store.144/) (Alibre Forum Resource) - Frontend for the Tool Store.
- [A better Internal and External Gear generator script with profil shifting](https://www.alibre.com/forum/index.php?resources/a-better-internal-and-external-gear-generator-script-with-profil-shifting.139/) (Alibre Forum Resource) - Script that generates internal and external gears with profile shifting.
- [AlibreScript Playground](https://www.alibre.com/forum/index.php?resources/alibrescript-playground.142/) (Alibre Forum Resource) - Development IDE for Alibre Script.
- [AlibreScript VS Code Extension](https://www.alibre.com/forum/index.php?resources/alibrescript-vs-code-extension.141/) (Alibre Forum Resource) - Visual Studio Code extension for Alibre Script.
- [AutoHotKey script to change the color of a part](https://www.alibre.com/forum/index.php?resources/autohotkey-script-to-change-the-color-of-a-part.127/) (Alibre Forum Resource) - AutoHotkey script that changes a part color.
- [Utilities for Alibre](https://www.alibre.com/forum/index.php?resources/utilities-for-alibre.125/) (Alibre Forum Resource) - Add-on of utilities for Alibre Design.
- [UNC and UNF bolts and screws](https://www.alibre.com/forum/index.php?resources/unc-and-unf-bolts-and-screws.138/) (Alibre Forum Resource) - Toolbox parts for UNC and UNF bolts and screws.
- [Frame Builder](https://www.alibre.com/forum/index.php?resources/frame-builder.123/) (Alibre Forum Resource) - Add-on that builds frames.
- [AI-Generated Scripts and Add-Ons Database](https://www.alibre.com/forum/index.php?resources/ai-generated-scripts-and-add-ons-database.132/) (Alibre Forum Resource) - Database of AI-generated scripts and add-ons.
- [Alibre Python Shell Installer](https://www.alibre.com/forum/index.php?resources/alibre-python-shell-installer.126/) (Alibre Forum Resource) - Installer for the Alibre Python shell.
- [AI-Generated Scripts and Add-Ons Archives](https://www.alibre.com/forum/index.php?resources/ai-generated-scripts-and-add-ons-archives.137/) (Alibre Forum Resource) - Archive of AI-generated scripts and add-ons.
- [Programming examples with Alibre Design](https://www.alibre.com/forum/index.php?resources/programming-examples-with-alibre-design.136/) (Alibre Forum Resource) - Documentation of programming examples for Alibre Design.
- [Script Runner](https://www.alibre.com/forum/index.php?resources/script-runner.133/) (Alibre Forum Resource) - Script runner for Alibre Script.
- [Additional threads for bolts and screws](https://www.alibre.com/forum/index.php?resources/additional-threads-for-bolts-and-screws.135/) (Alibre Forum Resource) - Toolbox parts with more bolt and screw threads.
- [ADC/JSON for Alibre Design Custom GPT](https://www.alibre.com/forum/index.php?resources/adc-json-for-alibre-design-custom-gpt.134/) (Alibre Forum Resource) - Custom GPT for Alibre ADC and JSON.
- [Hole presets](https://www.alibre.com/forum/index.php?resources/hole-presets.131/) (Alibre Forum Resource) - Toolbox hole presets.
- [Projection symbols](https://www.alibre.com/forum/index.php?resources/projection-symbols.130/) (Alibre Forum Resource) - Drawing template for projection symbols.
- [YouTube video list](https://www.alibre.com/forum/index.php?resources/youtube-video-list.129/) (Alibre Forum Resource) - Reference list of YouTube video titles.
- [Catalog thread profiles](https://www.alibre.com/forum/index.php?resources/catalog-thread-profiles.128/) (Alibre Forum Resource) - Catalog feature for thread profiles.
- [Specifications of International Thread Standards](https://www.alibre.com/forum/index.php?resources/specifications-of-international-thread-standards.124/) (Alibre Forum Resource) - Thread-standard reference from xrayxray.
- [Sheet metal thread form](https://www.alibre.com/forum/index.php?resources/sheet-metal-thread-form.112/) (Alibre Forum Resource) - Catalog feature for a sheet metal thread form.
- [Shortcuts Add-On for Alibre Design](https://www.alibre.com/forum/index.php?resources/shortcuts-add-on-for-alibre-design.122/) (Alibre Forum Resource) - Add-on that shows Alibre command shortcuts.
- [Metric SHS RHS CHS](https://www.alibre.com/forum/index.php?resources/metric-shs-rhs-chs.121/) (Alibre Forum Resource) - Toolbox parts for metric square, rectangular, and circular hollow sections.
- [ISO SHCS](https://www.alibre.com/forum/index.php?resources/iso-shcs.120/) (Alibre Forum Resource) - Toolbox parts for ISO socket head cap screws.
- [Circlips](https://www.alibre.com/forum/index.php?resources/circlips.119/) (Alibre Forum Resource) - Toolbox parts for circlips.
- [Section Properties for Alibre Sketched Sections](https://www.alibre.com/forum/index.php?resources/section-properties-for-alibre-sketched-sections.118/) (Alibre Forum Resource) - Script that calculates section properties for sketched sections.
- [Specifications of International Thread Standards](https://www.alibre.com/forum/index.php?resources/specifications-of-international-thread-standards.117/) (Alibre Forum Resource) - Thread-standard reference from GIOV.
- [Sheet metal gusset](https://www.alibre.com/forum/index.php?resources/sheet-metal-gusset.116/) (Alibre Forum Resource) - Catalog feature for a sheet metal gusset.
- [Export and Open .stl files](https://www.alibre.com/forum/index.php?resources/export-and-open-stl-files.115/) (Alibre Forum Resource) - Add-on that exports and opens STL files.
- [Open end louver](https://www.alibre.com/forum/index.php?resources/open-end-louver.114/) (Alibre Forum Resource) - Catalog feature for an open end louver.
- [Closed end twist louver](https://www.alibre.com/forum/index.php?resources/closed-end-twist-louver.113/) (Alibre Forum Resource) - Catalog feature for a closed end twist louver.
- [Louver closed end](https://www.alibre.com/forum/index.php?resources/louver-closed-end.110/) (Alibre Forum Resource) - Catalog feature for a closed end louver.
- [Card guide](https://www.alibre.com/forum/index.php?resources/card-guide.111/) (Alibre Forum Resource) - Catalog feature for a card guide.
- [Learning by Simulation](https://www.alibre.com/forum/index.php?resources/learning-by-simulation.109/) (Alibre Forum Resource) - Education resource, Learning by Simulation.
- [POLYCAD](https://www.alibre.com/forum/index.php?resources/polycad.107/) (Alibre Forum Resource) - Boat-design tool, POLYCAD.
- [Gear templates](https://www.alibre.com/forum/index.php?resources/gear-templates.106/) (Alibre Forum Resource) - 3D model of gear templates.
- [Cycloidal Gear Generator](https://www.alibre.com/forum/index.php?resources/cycloidal-gear-generator.102/) (Alibre Forum Resource) - Script that generates cycloidal gears.
- [CD jewel case](https://www.alibre.com/forum/index.php?resources/cd-jewel-case.104/) (Alibre Forum Resource) - 3D model of a CD jewel case.
- [NF-A4x10 FLX fan](https://www.alibre.com/forum/index.php?resources/nf-a4x10-flx-fan.103/) (Alibre Forum Resource) - 3D model of an NF-A4x10 FLX fan.
- [ACME Threads](https://www.alibre.com/forum/index.php?resources/acme-threads.100/) (Alibre Forum Resource) - Reference for ACME threads.
- [UN Threads](https://www.alibre.com/forum/index.php?resources/un-threads.99/) (Alibre Forum Resource) - Reference for UN threads.
- [GeoGebra](https://www.alibre.com/forum/index.php?resources/geogebra.98/) (Alibre Forum Resource) - Math tool, GeoGebra.
- [Undercut script](https://www.alibre.com/forum/index.php?resources/undercut-script.94/) (Alibre Forum Resource) - Script that creates undercuts.
- [WizoGrid](https://www.alibre.com/forum/index.php?resources/wizogrid.97/) (Alibre Forum Resource) - Sheet-metal tool, WizoGrid.
- [Worthington](https://www.alibre.com/forum/index.php?resources/worthington.96/) (Alibre Forum Resource) - 3D model of the Worthington.
- [MVE LAB20](https://www.alibre.com/forum/index.php?resources/mve-lab20.95/) (Alibre Forum Resource) - 3D model of the MVE LAB20.
- [Smath Studio](https://www.alibre.com/forum/index.php?resources/smath-studio.92/) (Alibre Forum Resource) - Math tool, Smath Studio.
- [Wizotool](https://www.alibre.com/forum/index.php?resources/wizotool.91/) (Alibre Forum Resource) - Sheet-metal tool, Wizotool.
- [K-factor for sheet metal](https://www.alibre.com/forum/index.php?resources/k-factor-for-sheet-metal.90/) (Alibre Forum Resource) - Reference for sheet metal K-factors.
- [42-40 stepper motor](https://www.alibre.com/forum/index.php?resources/42-40-stepper-motor.89/) (Alibre Forum Resource) - 3D model of a 42-40 stepper motor.
- [Humbucker](https://www.alibre.com/forum/index.php?resources/humbucker.88/) (Alibre Forum Resource) - 3D model of a humbucker.
- [Tuner](https://www.alibre.com/forum/index.php?resources/tuner.87/) (Alibre Forum Resource) - 3D model of a tuner.
- [Bridge](https://www.alibre.com/forum/index.php?resources/bridge.86/) (Alibre Forum Resource) - 3D model of a bridge.
- [Hydraulic cylinder](https://www.alibre.com/forum/index.php?resources/hydraulic-cylinder.85/) (Alibre Forum Resource) - 3D model of a hydraulic cylinder.
- [Crib sheet for threads](https://www.alibre.com/forum/index.php?resources/crib-sheet-for-threads.83/) (Alibre Forum Resource) - Reference crib sheet for threads.
- [PCO preform](https://www.alibre.com/forum/index.php?resources/pco-preform.82/) (Alibre Forum Resource) - 3D model of a PCO preform.
- [Hole preset info](https://www.alibre.com/forum/index.php?resources/hole-preset-info.81/) (Alibre Forum Resource) - Reference for hole presets.
- [Dovetail O-ring groove](https://www.alibre.com/forum/index.php?resources/dovetail-o-ring-groove.80/) (Alibre Forum Resource) - Catalog feature for a dovetail O-ring groove.
- [Belleville disc spring washers](https://www.alibre.com/forum/index.php?resources/belleville-disc-spring-washers.79/) (Alibre Forum Resource) - Toolbox parts for Belleville disc spring washers.
- [Materials file](https://www.alibre.com/forum/index.php?resources/materials-file.26/) (Alibre Forum Resource) - Material file for Alibre Design.
- [SAE nuts](https://www.alibre.com/forum/index.php?resources/sae-nuts.76/) (Alibre Forum Resource) - Toolbox parts for SAE nuts.
- [Centering bushes](https://www.alibre.com/forum/index.php?resources/centering-bushes.75/) (Alibre Forum Resource) - Toolbox parts for centering bushes.
- [CSK screws](https://www.alibre.com/forum/index.php?resources/csk-screws.74/) (Alibre Forum Resource) - Toolbox parts for countersunk screws.
- [Cap screws](https://www.alibre.com/forum/index.php?resources/cap-screws.73/) (Alibre Forum Resource) - Toolbox parts for cap screws.
- [Dowel](https://www.alibre.com/forum/index.php?resources/dowel.72/) (Alibre Forum Resource) - Toolbox parts for dowels.
- [Harting HAN 3A](https://www.alibre.com/forum/index.php?resources/harting-han-3a.71/) (Alibre Forum Resource) - 3D model of a Harting HAN 3A connector.
- [Ejector pins](https://www.alibre.com/forum/index.php?resources/ejector-pins.70/) (Alibre Forum Resource) - Toolbox parts for ejector pins.
- [Metric nuts](https://www.alibre.com/forum/index.php?resources/metric-nuts.69/) (Alibre Forum Resource) - Toolbox parts for metric nuts.
- [Button head](https://www.alibre.com/forum/index.php?resources/button-head.67/) (Alibre Forum Resource) - Toolbox parts for button head screws.
- [Rivet B](https://www.alibre.com/forum/index.php?resources/rivet-b.66/) (Alibre Forum Resource) - Toolbox parts for rivet B.
- [Rivet A](https://www.alibre.com/forum/index.php?resources/rivet-a.65/) (Alibre Forum Resource) - Toolbox parts for rivet A.
- [Washers](https://www.alibre.com/forum/index.php?resources/washers.64/) (Alibre Forum Resource) - Toolbox parts for metric washers.
## Resellers

- [Alibre Design Deutschland · O-Punkt CAD GmbH](https://alibre.info/) - German Alibre Design reseller and regional resource.
- [Alibre Switzerland](https://www.alibre.ch/) - Swiss Alibre Design resource and reseller.

## Extensions

### Visual Studio

- [Alibre Design Extension for Visual Studio](https://marketplace.visualstudio.com/items?itemName=stephensmitchell.adextension) - Project and item templates for Alibre Design add-ons and COM-based development, with samples and code comments.
- [Alibre API Samples Extension](https://marketplace.visualstudio.com/items?itemName=stephensmitchell.aapisext) - C++ project templates demonstrating Alibre Design API animation, DirectX integration, and selection handling.
- [Alibre C++ CLI Tools Extension](https://marketplace.visualstudio.com/items?itemName=stephensmitchell.AlibreCppCLIToolsExtension) - Collection of 50 C++ command-line tool templates for exploring the Alibre Design API in Visual Studio 2026.
- [Alibre PDM API Samples Extension](https://marketplace.visualstudio.com/items?itemName=stephensmitchell.newapipdm) - C# project templates for Alibre PDM server connections, safes, projects, libraries, files, properties, and version history.
- [SSM Extension for Visual Studio](https://marketplace.visualstudio.com/items?itemName=stephensmitchell.ssmextension) - General tooling and automation starter projects in C#, VB, and F# for working with data, geometry, and workflows.

### Visual Studio Code

- [alibrescript-vscode](https://marketplace.visualstudio.com/items?itemName=stephensmitchell.alibrescript) - IntelliSense and type hints for Alibre Script using generated type stubs.
- [alibrex-vscode](https://marketplace.visualstudio.com/items?itemName=stephensmitchell.alibrex-vscode) - Sets up a Python 3 environment for alibrex, including a virtual environment, typed AlibreX bindings, debugging, and Alibre Design version selection.

## Interoperability and Conversion

- [alibre-to-freecad](https://github.com/tuffrabit/alibre-to-freecad) - Tools for converting Alibre Design parts to native FreeCAD parts.
- [AlibreExportOpen](https://github.com/bolsover/AlibreExportOpen) - Exports Alibre designs as STL files and opens the exported files.
- [alibre-neutralizer](https://github.com/k4kfh/alibre-neutralizer) - Batch-exports Alibre assemblies to neutral formats for repeatable open-source hardware and Git workflows.
- [alibre-stltostp-addon](https://github.com/AlibreDesignCommunityProjects/alibre-stltostp-addon) - Community STL-to-STEP add-on.
- [mariogt/stl-to-step-alibre](https://github.com/mariogt/stl-to-step-alibre) - STL to STEP converter for Alibre Design.
- [StlStpConverter](https://github.com/bolsover/StlStpConverter) - Library and win application for conversion from .stp to .stl

## Contributing

Open an issue or pull request to suggest a resource or correction. See [CONTRIBUTING.md](CONTRIBUTING.md) for inclusion criteria, entry formatting, and broken-link reports.

## License

We dedicate this curated list and its original descriptions to the public domain under [CC0 1.0 Universal](LICENSE). Linked projects, software, videos, and trademarks retain their own terms and ownership.

---

**Trademark note:** Alibre and Alibre Design belong to their respective trademark owner. The community maintains this list; Alibre publishes the resources identified as official.
