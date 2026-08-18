# operations/ — Inventory, Assembly, Packing & Shipping

**Owner:** `operations-fulfillment-manager`

## What belongs here
SOPs · assembly instructions · quality control checklists · packing specs · inventory system design · supply forecasts · vendor comparisons · shipping analysis · the risk register · the fulfillment calendar · damage and replacement procedures.

## Structure
```
operations/
├── sops/        ← step-by-step procedures anyone can follow
├── assembly/    ← how to build each kit
├── vendors/     ← supplier comparisons by category
└── (top-level: inventory-system, supply-forecast, shipping-analysis,
     risk-register, fulfillment-calendar, packing-spec,
     quality-control-checklist, damage-and-replacements)
```

## The rules for this folder
1. **No vendor has been contacted and no order has been placed.** Comparisons use public information or quotes Maya obtained.
2. **No invented prices, lead times, minimums, or shipping rates.** Unknown = `[NEEDS QUOTE]`.
3. **Forecasts are scenarios, not predictions**, and every input is shown.

## Templates
`templates/sop-template.md` · `templates/vendor-comparison-template.md`
