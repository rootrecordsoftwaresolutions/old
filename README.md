# old — G0 deepest skill / runtime archive

> **Not production. Not a poller host. Do not bulk-merge into live Pacific.**

| Field | Value |
| --- | --- |
| **Generation** | **G0** (deeper than G1 `Solar-Pacific-RootRecord-Server-Old`) |
| **Role** | Forensic / feature scavenger source only |
| **Shape** | ~200 **flattened** skill tops (+ older AVA/runtime notes on some trees) |
| **Production authority** | [RootRecord-Software-Solutions](https://github.com/RootRecord-Software-Solutions) |
| **Live runtime** | [RootRecord-Pacific-Solar-Server](https://github.com/RootRecord-Software-Solutions/RootRecord-Pacific-Solar-Server) |
| **Docs** | [RootRecord-Library](https://github.com/RootRecord-Software-Solutions/RootRecord-Library) |
| **G1 (grouped packets)** | [Solar-Pacific-RootRecord-Server-Old](https://github.com/rootrecordsoftwaresolutions/Solar-Pacific-RootRecord-Server-Old) |

---

## Lineage

```text
G3  org RootRecord-Pacific-Solar-Server     ← live
G2  Solar-Pacific-RootRecord-Server         ← residual skills desk
G1  Solar-Pacific-RootRecord-Server-Old     ← grouped skill packets
G0  this repo (old)                         ← flattened / deeper archive
```

G1 often **groups** what still appears here as separate roots (e.g. `energy/ecoflow-*` on G1 vs `ecoflow-ble-poller` here). Unique or forgotten features are most likely in **G0-only** tops.

---

## Hard rules

1. **Never** run this tree as the live poller or job host.  
2. **Never** bulk-merge into G3.  
3. Recovery order: finish **G2 → G3**, then selective **G1**, then **G0 diff-only** for unique scripts.  
4. Strip secrets before any copy. Prefer `MIGRATED.md` on superseded packets (see G1 pattern).  
5. High noise / low urgency while Automations, Energy, and System residuals are still in flight.

---

## Where to read more

| Doc | Link |
| --- | --- |
| Migration index (Library) | [MIGRATION-DOCS-INDEX-2026-09-28.md](https://github.com/RootRecord-Software-Solutions/RootRecord-Library/blob/main/Documentation/00-architecture/MIGRATION-DOCS-INDEX-2026-09-28.md) |
| G0 unique vs G1 (scavenger) | Same index § **G0** |
| G1 status list | [Solar-Pacific-RootRecord-Server-Old README](https://github.com/rootrecordsoftwaresolutions/Solar-Pacific-RootRecord-Server-Old/blob/main/README.md) |
| Three generations | [Migration-Lineage](https://github.com/RootRecord-Software-Solutions/RootRecord-Library/blob/main/Documentation/00-architecture/Migration-Lineage-Three-Generations-2026-09-28.md) |

Best use of this repo: **feature scavenger list** when redesigning AI processing, weather/reports, or broadcast — not day-to-day ops.

---

*G0 README 2026-09-28 HST.*
