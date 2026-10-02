# PLG for AI Products: Claude Skills

Five diagnostic skills for product-led growth in AI products, built from the frameworks I use with clients at [Small Table Studio](https://manalihanamsagar.com/smalltablestudio?utm_source=github&utm_medium=readme&utm_campaign=plg-for-ai-products).

Install them in Claude, point Claude at your product, and it runs the diagnostic for you: where trust breaks, where activation stalls, what to fix first.

**By Manali Hanamsagar**, growth operator and founder of Small Table Studio. 10+ years making growth channels work, now focused on product-led growth and building trust in AI products.

## The skills

| Skill | Use it when | What you get |
|---|---|---|
| [**ai-trust-audit**](skills/ai-trust-audit/SKILL.md) | Users try your AI feature once and don't come back, or double-check everything it produces | A trust scorecard, your top 3 trust gaps, and the first thing to test |
| [**activation-audit**](skills/activation-audit/SKILL.md) | Signups look fine but users churn or stall weeks later | Where users believe they're progressing but aren't, and the top 3 fixes |
| [**behavioral-design-gap**](skills/behavioral-design-gap/SKILL.md) | Your PLG motion is built but conversion and engagement plateau | A 5-question behavioral diagnostic and quick wins for this week |
| [**plg-with-sales**](skills/plg-with-sales/SKILL.md) | You're adding self-serve to a sales-led company and both motions are struggling | The sales gaps to productize first and a handoff audit |
| [**ai-plg-90-day-plan**](skills/ai-plg-90-day-plan/SKILL.md) | You're starting PLG for an AI product and don't know where to begin | A sequenced 30/60/90-day plan for your product |

Each skill includes the full framework in `references/framework.md`, so you can also just read them.

## Install

### Claude.ai or the Claude desktop app
1. Download the skill you want from the [`downloads`](downloads) folder (each is a `.zip`).
2. In Claude, open **Settings → Skills** and upload the zip. Skills require a paid plan with code execution enabled.
3. Start a chat and ask, for example: *"Run an AI trust audit on our onboarding"* and share screenshots or a description of your product.

### Claude Code
Install all five as a plugin:

```
/plugin marketplace add manali-sagar/plg-for-ai-products
/plugin install plg-for-ai-products@small-table-studio
```

Or copy any folder from [`skills`](skills) into `~/.claude/skills/`.

The same collection also includes [Growth Channel Skills](https://github.com/manali-sagar/growth-channel-skills) (growth planning and referral programs). Install it with `/plugin install growth-channel-skills@small-table-studio`.

## How to get the most out of them

- **Bring real material.** Screenshots of your onboarding, your homepage promise, your metrics, sales call notes. The skills won't invent data; they'll tell you what's missing and how to find it.
- **Start with one feature or one flow.** The frameworks work best applied narrowly: the AI feature with the biggest drop-off, the onboarding path with the most churn.
- **Use the output with your team.** The reports are built to bring into a product review.

## Want help?

These skills give you the diagnosis. If you want help prioritizing and fixing what they find, that's what [Small Table Studio](https://manalihanamsagar.com/smalltablestudio?utm_source=github&utm_medium=readme&utm_campaign=plg-for-ai-products) does for AI product teams.

Newsletter: [The Small Table Company on Substack](https://smalltableco.substack.com/) · [LinkedIn](https://www.linkedin.com/in/manalihanamsagar/)

## License

[CC BY 4.0](LICENSE). Use, adapt, and share these freely, including commercially. Just credit Manali Hanamsagar / Small Table Studio.
