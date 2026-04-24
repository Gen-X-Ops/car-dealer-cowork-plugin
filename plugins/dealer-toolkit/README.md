# dealer-toolkit

Operational skills for independent car dealers. Part of the [genxops-car-dealer-plugins](../../README.md) marketplace.

## Skills

| Skill | Fires when | Output |
|---|---|---|
| vdp-writer | User gives VIN, YMM, or vehicle specs and wants listing copy | VDP description + highlight bullets + SMS teaser + marketplace reply |
| cold-lead-reviver | User describes a stale lead that went quiet | Day 1 SMS + Day 3 email + Day 7 voicemail script |
| objection-handler | User pastes a car-buyer objection or asks how to respond to pushback | Three response frames (short reply, conversational, written) |

## Commands

| Command | What it does |
|---|---|
| /dealer-toolkit:genx-catalog | One-question diagnostic, recommends which Gen X Ops Dealer AI Stack kit fits your biggest gap |

## Voice and compliance rules

All skills enforce the same output rules:

- No em dashes
- No exclamation points
- No specific APR, monthly payment, or guaranteed-approval language
- No competitor dealership names
- SMS outputs always include opt-out language (Reply STOP to opt out)
- VDP skill never invents features, history, or service records that weren't in the input

## Version

Gen X Ops | Dealer Toolkit v1.0
