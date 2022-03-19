### Questions on DCF

https://pages.stern.nyu.edu/~adamodar/New_Home_Page/valquestions/valquestions.htm

### FCF

```
FCF = NOPAT - CAPEX + tax-deductible D&A - Change in WC

// changes in WC refers to NWC for current period - NWC for previous period
```

### Tax Rate

Cannot use actual taxes paid as it will reflect tax savings when interest payments are made; as EBIT is used, the tax benefits are already included in cost of capital and would be double counting.

Boils down to a choice between effective and marginal tax rates. Effective tax rate is lower than marginal tax rate as companies defer paying taxes. Best compromise is to use effective tax rates for early forecast years and move towards a marginal tax rate in the later years.

In the year of operating loss, the tax rate used in computing the NOPAT should be zero. As you project earnings into future years and they turn positive, have to first cover net operating losses from prior years, during which period the tax rate will still be zero. When net operating losses are used up, the tax rate will converge on the marginal tax rate.

### Depreciation and Amortization

Only tax deductible depreciation and amortization affect your cash flows. Hence, should compute operating income after tax deductible D&A, and add back after NOPAT. Else, will give non-tax deductible D&A a tax benefit.

```
EBITDA = $500
Tax-deductible D&A = $100
Non-tax deductible D&A = $50
tax-rate = 20%

// case including non-tax deductible
EBIT = 500 - 150 = $350
NOPAT = 350 * 0.8 = $280
NOPAT + D&A = 280 + 150 = $430

// case excluding non-tax deductible
EBIT = 500 - 100 = $400
NOPAT = 400 * 0.8 = $320
NOPAT + D&A = 320 + 100 = $420
```

### Working Capital

Working capital is considered when computing cash flows is because investments in working capital are considered wasting assets that don't earn a fair rate of return i.e. money wasted in inventory is wasted as it sits on shelves. For cash, most public companies invest their cash in commercial paper or treausry bills and hence, earn a low but fair rate of return. Thus, cash is not a wasting asset and **should not** be considered part of working capital.
