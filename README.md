# Project Jupiter Water Analysis: The Numbers Nobody Published

An independent quantitative analysis of water pressure, supply margins, and accountability gaps in the El Paso / Santa Teresa data center corridor.

## What This Is

This document answers one question with math instead of opinion: **do we have enough water for the new data centers?**

Every number comes from a public source. Every calculation can be reproduced with a calculator and the cited documents. If any number is wrong, correct it publicly and cite your source.

## Who This Is For

The document has four tiers. Pick the one that fits you.

| Tab | Audience | What You Get |
|-----|----------|-------------|
| Residents | Community members | Plain language, 6th grade reading level |
| Journalists | Reporters, editors | Sourced data tables with full bibliography |
| Technical | Engineers, professors, researchers | Full equations, input values, sensitivity analysis |
| Español | Comunidad hispanohablante | Resumen en español claro |

## Key Findings

- Data center water demand (1.56 MGD at full build) is only 1.5% of existing demand
- That same demand is **17.9% of the supply surplus** (the safety margin between supply and demand)
- The conclusion flips from "we're fine" to "we're over capacity" depending on which supply definition is used
- No public document specifies which supply definition decision-makers used
- Project Jupiter's beneficial ownership chain is not fully public

## Sources

1. Texas Tribune, April 2025 (El Paso baseline demand)
2. El Paso Water Conservation Plan, 2024 (2023 production data)
3. Bureau of Reclamation, Rio Grande Project (supply and demand allocations)
4. Doña Ana County MOU, September 24, 2025 (Jupiter water requirements)
5. KVIA / Yahoo News (Meta El Paso water requirements)
6. State MOU, February 25, 2025 (BorderPlex Digital Assets LLC)
7. EPA inspection report, 2025 (arsenic treatment plant status)
8. Legal complaint, Case D-307-CV-2025-02766

## Verification

To reproduce this analysis:

1. Obtain the source documents listed above
2. Extract the stated values (demand, supply, DC water requirements)
3. Compute: `P = (DC_demand + existing_demand) / available_supply`
4. Compare your results to the document

If your numbers differ, publish the correction with your source.

## License

Public domain. See [LICENSE](LICENSE).
