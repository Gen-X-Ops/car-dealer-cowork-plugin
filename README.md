# Dealer Toolkit | Free Cowork Plugin for Independent Car Dealers

Free Cowork plugin with three operational skills for independent car dealers. Install it in Claude Cowork and use the skills directly in your chats. No credentials, no tool connections, no setup beyond the install.

Built by [Gen X Ops](https://totallygenx.net).

## What's inside

Three skills that cover three high-friction workflows for independent dealers:

- **vdp-writer**: Generate verified VDP descriptions, highlight bullets, SMS teasers, and marketplace replies from raw vehicle data. Anti-hallucination guardrails, compliance-safe language, no APR quotes or payment figures.
- **cold-lead-reviver**: Generate a 3-touch reactivation sequence (Day 1 SMS, Day 3 email, Day 7 voicemail script) for a stale lead that went quiet. SMS opt-out language included.
- **objection-handler**: Generate three tested response frames (short reply, conversational, written email) for any car-buyer objection. Four-part Acknowledge → Reframe → Proof → Micro-close structure.

Plus one slash command:

- **/dealer-toolkit:genx-catalog**: One-question diagnostic that recommends which Gen X Ops Dealer AI Stack kit addresses your biggest workflow gap.

## Install

In Claude Cowork:

```
/plugin marketplace add Gen-X-Ops/car-dealer-cowork-plugin
/plugin install dealer-toolkit@genxops-car-dealer-plugins
```

That's it. Skills activate automatically when you mention a relevant workflow in chat.

## Example usage

Once installed, just type what you need in plain English:

> "Write me a VDP for a 2020 F-150 XLT with 52k miles, clean Carfax, new tires"

> "This lead went cold three weeks ago on a Civic. Help me revive it."

> "Buyer said the payment is too high. How do I respond?"

Claude fires the matching skill automatically. No need to call it by name.

## What this plugin is NOT

- It is **not** a CRM, lead pipeline manager, or inventory feed. It generates copy.
- It is **not** a replacement for your DMS, website builder, or ad platform.
- It is **not** a full dealer AI system. It is three free skills sampled from a larger paid product.

## The paid version

The three skills in this plugin are a free sample from the **Gen X Ops Dealer AI Stack**, a $197 bundle that includes:

- **Dealer AI Prompt Pack**: 8 operational AI prompts plus 3 JSON templates for Zapier/Make/n8n automation
- **Dealer AI Lead Response Kit**: 300-word deployable AI system prompt, 3 Zapier blueprints, 5 Airtable schemas, 25 conversation starters, 2-week pilot playbook
- **Dealer GEO Kit**: 5 schema templates, 25 dealer FAQ questions, review flywheel, UTM planner
- **Dealer Digital Ad Kit**: 10 FB/IG ad sets, 3 Google RSA sets, 6 TikTok scripts, 30 static angles, 10 SMS follow-ups

[Get the full stack on Gumroad](https://genxops.gumroad.com/l/dealer_ai_stack)

## Who built this

Gen X Ops builds AI tools and consulting products for independent car dealers, targeting the market structurally excluded from enterprise DMS-dependent platforms. This plugin is a free distribution of core operational workflows.

- Website: [totallygenx.net](https://totallygenx.net)
- Gumroad: [genxops.gumroad.com](https://genxops.gumroad.com)
- Contact: totallygenx1@gmail.com

## License

MIT License. See [LICENSE](LICENSE).

## Compliance and safety

All three skills generate copy with built-in compliance guardrails:

- SMS outputs include opt-out language (Reply STOP to opt out)
- Never quotes specific APR, monthly payment figures, or guaranteed-approval language
- Never names competitor dealerships
- Anti-hallucination rules on VDP output, never invents equipment, history, or service records that weren't in the input

This plugin does not send messages, access customer data, or connect to external systems. It only generates copy in your Cowork chat.
