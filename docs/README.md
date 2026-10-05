# JFXENGINE Documentation

[Project overview and architecture diagrams](../README.md)

The documentation describes a proposed MBSE, simulation, AI and 3D integration
platform. The repository snapshot contains documentation and Draw.io models;
runtime integrations remain work to implement and validate.

## Guides

| Document | Scope |
| --- | --- |
| [Four-phase engineering delivery plan](roadmap/four-phase-engineering-delivery-plan.md) | All ten source activities, phase gates, SIL/HIL distinctions and the relationship to the seven platform milestones |
| [Domain ingestion pipelines](architecture/domain-ingestion-pipelines.md) | Four source/target workstreams, adapter boundaries, semantic review and validation records |
| [README architecture](../README.md#6-conceptual-architecture) | Mermaid views of the workspace, data, digital twins and engineering lifecycle |

## Editable architecture sources

These existing Draw.io assets remain the editable source material for their
respective views; Mermaid documentation does not overwrite them.

- [Expanded AI roadmap](../MBSE/CAS/Drawio/Expanded%20AI%20Roadmap.drawio)
- [AI / MBSE / 3D integration](../MBSE/CAS/Drawio/jfxengine_ai_mbse_3d_integration_v31_4_2.drawio)
- [Multi-domain ingestion pipelines](../MBSE/CAS/Drawio/multi-domain-ingestion-pipelines.drawio)
- [Visual integration](../MBSE/CAS/Drawio/visual-integration.drawio)

## Diagram conventions

- Use Mermaid for architecture relationships, workflows and feedback loops.
- Keep component names concise and show review/revision paths explicitly.
- Use ordinary lists for inventories and text blocks for directory layouts.
- Mark conceptual integrations as proposals; diagram arrows do not demonstrate
  implemented interoperability or lossless conversion.
- Update links and this migration register when documents move.

## Source migration register

| Original file under `docs/` | English Markdown destination | Treatment |
| --- | --- | --- |
| `Detalle de las 4 Fases.txt` | [Four-phase delivery plan](roadmap/four-phase-engineering-delivery-plan.md) | All four phases and ten activities retained; review gates and two Mermaid workflows added |
| `Especificación de los.txt` | [Domain ingestion pipelines](architecture/domain-ingestion-pipelines.md) | Four domain rows reconstructed; two Mermaid views added; bidirectional conversion claims qualified |

Both TXT files are replaced by these documents. Their original Spanish wording
remains in Git history. The README's architecture and process diagrams are
converted from plain text to Mermaid, with feedback and review paths made explicit.
