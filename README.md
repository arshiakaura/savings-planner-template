# Savings Planner: Compare Where Your Money Could Grow

A free Excel workbook that shows how monthly savings, fees, and time affect your balance. It compares savings accounts, GICs, and index funds or ETFs side by side, so you can see the difference a fee or a rate makes before you choose.

**This tool is for learning and rough planning. It does not recommend any bank or product.**

## What's inside

| Tab | What it does |
|---|---|
| **Start Here** | Three steps to get going and a colour key |
| **Disclaimers** | What the results do and don't include, and where to check current rules |
| **Glossary** | Plain-English definitions of terms like GIC, MER, TFSA, and FHSA |
| **My Inputs** | Where you enter your own numbers |
| **Bank Products** | Illustrative rates and fees for each bank's products |
| **Projection** | Year-by-year balances for every option (calculated automatically) |
| **Dashboard** | The best option, a full comparison table, and a chart |

## How to use it

1. **Go to My Inputs** and fill in the yellow cells:
   - Monthly amount you can save
   - Down payment goal
   - Savings you already have
   - Number of years to project (1 to 30)
2. **Go to Bank Products** and check the yellow cells. The rates and fees are illustrative, so check each bank's website for current figures before you rely on them.
3. **Go to the Dashboard** to see:
   - The option that grows the most over your timeframe, shown in red on the chart
   - The balance each option reaches, how much you put in, and how much growth came from returns after fees
   - The number of years to reach your down payment goal

You only need to type in the yellow cells. Everything else updates automatically.

## How the numbers are calculated

- **Net return** = gross return − fund fee (MER)
- **Each year's balance** = (last year's balance + 12 × monthly savings) × (1 + net return) − account fee
- **Years to down payment** = the number of years the balance stays below your goal

These are simplified. Contributions are added once a year and returns compound once a year. Taxes and inflation are not included.

## Important: illustrative numbers

The rates and fees on **Bank Products** are **illustrative values made for this project**, to show how the model works. They are not real bank rates, fees, or offers. The five banks have similar but different numbers so the comparison is easy to follow.

If you update a rate with a real figure, add the date you checked it and a link to the source.

## Rules used in the Glossary

Checked against public sources in October 2026. Rules change, so confirm them with the Canada Revenue Agency (CRA), the Government of Canada, or your bank.

- **TFSA:** $7,000 annual limit for 2026
- **FHSA:** $8,000 a year, $40,000 lifetime
- **RRSP:** the lower of $33,810 or 18% of prior-year earned income, plus carried-forward room
- **CDIC insurance:** up to $100,000 per depositor, per category, at each member institution
- **Mortgage default insurance:** required when the down payment is under 20%

## Not financial advice

Nothing in this workbook is financial, tax, legal, or investment advice. For decisions about your money, speak with a licensed professional who can consider your full situation.

## Feedback

Found an error or have an idea to make it clearer? Open an issue on this repository or leave a comment on the post where you found it.

## Built with

Built in Excel with formulas only, so every result recalculates when you change an input. The figures were checked against the sources above, but errors are still possible.
