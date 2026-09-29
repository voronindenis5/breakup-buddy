---
name: breakup-buddy
description: Untangle a shared life — fair item splits, joint-account renewal traps, one-payment settle-up, dated move-out plan.
version: 1.0.0
author: Denis Voronin
license: MIT
tags: [breakup, moving, shared-assets, subscriptions, life-transitions]
---

# Breakup Buddy

**Two lives untangled, itemized, settled, and closed.**

When a live-in relationship ends, the logistical work is what ruins the next
three months. This is a structured untangling system: shared-item catalog with
three fair-split engines (alternating draft with seeded coin flip, buyout at
depreciated equity, sell-and-split), sentimental-item quarantine, joint-account
audit that flags anything renewing within 90 days with no decision, shared
expenses collapsed to one net payment, and a dated move-out plan with notice
deadlines and deposit-demand timeline.

## Quick Start
```bash
python3 scripts/untangle.py split draft --seed 42
python3 scripts/untangle.py account list --due 90
python3 scripts/untangle.py expense settle
python3 scripts/untangle.py report
```

100% local, one JSON file — this data is among the most sensitive there is.
