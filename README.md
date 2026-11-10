# Universal Chuck Safety Shield

A mechanical retrofit project for a lathe chuck shield that mounts to the tool post, helps redirect machining chips toward the collection area, and retains a view of the workpiece through transparent panels.

This repository preserves the supplied CAD exports, manufacturing drawings, prototype photographs, demonstration videos, project report, and presentation. The report describes a prototype fitted to an ST-34 lathe; the design is intended to be adaptable, with dimensions and clearances adjusted for each machine.

![Shield components: main box, hinge, side panel frame, and support mount](3D%20Design/Screenshots/Picture2.png)

## Project overview

Conventional lathes can throw chips beyond the machining area. The project investigates a shield that can be retrofitted around the working area without a complicated sliding enclosure or extensive changes to the machine.

The proposed arrangement uses a sheet-metal main box, a side panel assembly, a support mount, hinges, and transparent thermoplastic panels. Mounting around the tool post is intended to accommodate machines with additional equipment, including automatic job changers.

## Design features

- **Tool-post mounting:** a support mount connects the shield to the tool post. The supplied design aims to avoid drilling additional mounting holes into the tool post.
- **Access for maintenance:** the hinged assembly can be opened or flipped back to expose the chuck and tooling.
- **Visibility:** transparent panels provide views of the machining area from the front and sides.
- **Adjustable side panel:** alternative mounting positions provide space for an air-gun connection or other nearby components.
- **Simple mechanical arrangement:** the concept emphasizes few moving parts, removable components, and a sheet-metal enclosure.
- **Prototype sensor integration:** the report describes a Mindman RCA sensor switch used to stop the demonstrated machine when the shield is lifted.

The report describes approximately 110 degrees of installed opening travel, while the presentation discusses up to 180 degrees where there are no obstructions. Available travel depends on the installation; these figures are not a single universal clearance specification.

## Repository contents

| Folder | Contents |
| --- | --- |
| [3D Design](3D%20Design/) | Six STEP (`.stp`) models, three DWG views, and two CAD screenshots |
| [Drafting](Drafting/) | Seven PDF drawings, including [Final.pdf](Drafting/Final.pdf) |
| [Images](Images/) | Nine photographs of the manufactured prototype and its installation |
| [Videos](Videos/) | Three supplied media clips |
| [Documentation](Documentation/) | Project report, 27-slide presentation, and project video |

### Documents and demonstrations

- [Project report](Documentation/Report.docx) — *Retrofit Safety Solutions: Risk Mitigation in Lathe Machining via a Universal Chuck Shield for Frequency Conversion Systems*
- [Presentation](Documentation/Presentation.pptx) — design considerations, drawings, components, prototype, and demonstrations
- [Project video](Documentation/Video.mp4)
- [Media 1](Videos/Media1.mp4)
- [Media 2](Videos/Media2.mp4)
- [Media 3](Videos/Media3.mp4)
- [Prototype photograph](Images/20220908_100432.jpg)

## Viewing and downloading

The large documents and videos are stored directly in their original folders using **Git LFS**. On GitHub, open a file and use its download control to retrieve the original binary.

To obtain the full repository locally, install Git and Git LFS, then run:

```bash
git lfs install
git clone https://github.com/ArviZuko/Universal-Chuck-Safety-Shield.git
cd Universal-Chuck-Safety-Shield
git lfs pull
```

Use a STEP-compatible CAD application for the `.stp` models, a DWG viewer or compatible CAD application for the drawing views, and a PDF viewer for the manufacturing drawings. The report and presentation can be opened with compatible office software, and the videos with an MP4-capable player. The report identifies KeyCreator as the original CAD design tool; the repository contains the supplied STEP/DWG exports.

## Reported observations and limits

The supplied documents describe manufacture and installation of the prototype and show it during lathe operation. The report includes preliminary observations of improved chip collection. Its quantitative results contain inconsistent totals and time periods, so this README does not present them as a validated collection-efficiency or accident-reduction benchmark.

“Universal” describes the retrofit concept, rather than a verified fit across all lathes. The report states that dimensions need to be adapted to the particular machine. The repository does not provide a verified impact-containment rating, safety-rated interlock validation, or evidence of compliance testing. Machine-specific engineering assessment is needed before treating the design as protective equipment.

## Project status

This is a design and prototype documentation archive. The original 33 project files are preserved with their supplied filenames and folder structure. No standalone control software or automated test suite was supplied.
