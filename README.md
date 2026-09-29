# Growth Audit — Lifesum

Five ranked ideas to unlock more revenue from the traffic Lifesum already has, plus a clickable
prototype of the onboarding and paywall rebuilt in Lifesum's own design.

**Live:** https://bterzic123.github.io/lifesum-flow-rebuild-v2/

Open it and you land on the overview. **Prototype** in the top bar opens the phone, and every idea
links straight to the screen that shows it. Above the phone: English / Swedish / German, light and
dark, and a 30-second walkthrough. On a phone, the prototype fills the screen.

## The five ideas

| # | Idea | Potential outcome |
|---|------|-------------------|
| 01 | Offer the free trial when they close the paywall. Apple lists all three Premium plans with a trial, but no onboarding screen offers one. | ARPU +10–15% |
| 02 | Show the plan before asking for an account. Today the sign-up wall sits between "Your personalized plan is ready" and the plan itself. | CR +8% · ARPU +17% |
| 03 | Put their goal and date in the paywall headline. The flow works out both; the paywall uses neither. | CR +15–20% |
| 04 | Ask for Apple Health after the purchase, not at step six. | CR +10–15% |
| 05 | Let the loader read their answers back while it counts to 100%. | CR +10–15% |

## Your design, unchanged

Every screen is Lifesum's: the cream surface, the green buttons, the three-column wheel picker, the
forest-green loader, the Free vs Premium table, the award band and the three plan cards. Only the
order changed.

## Grounding

Prices ($49.99 / year, $14.99 / 3 months, $7.49 / month, each tagged Trial), the 4.6 rating from
151K ratings and Editors' Choice come from Lifesum's US App Store listing. Strikethrough prices,
"50% off Premium", the "5x more likely" line and Anabelle's quote come from Lifesum's own paywall.
The 1,712 kcal daily target is from Lifesum's App Store screenshots. The photography is Lifesum's own.
Swedish and German screens are our translation; store prices stay as published and the quote stays
verbatim.

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps —
**not** measured lift for Lifesum.

## Run it locally

```bash
python3 -m http.server 8921
```

Then open http://127.0.0.1:8921. It is one static `index.html` plus the `img/` folder.
