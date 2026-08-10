# SMB AI-Adoption Stats: Source Verification

**Prepared:** 2026-05-29
**For:** Justin Massa - civic AI pitch deck and op-ed use
**Status:** Both stats confirmed with primary source citation

---

## Stat 1: "82% of very small businesses say generative AI is 'not applicable'"

### Verdict: CONFIRMED - use with minor precision note

**Exact source text:**
> "As shown in Figure 5, **nearly 82 percent of businesses under five employees** reported relevance as a reason they were not planning to use AI in the near future."

**Source:**
- **Document:** "AI in Business: Small Firms Closing In" - Research Spotlight
- **Author:** Robert Press, Regulatory Economist, SBA Office of Advocacy
- **Published:** September 24, 2025
- **URL:** https://advocacy.sba.gov/wp-content/uploads/2025/09/Research-Spotlight-AI-in-Business-Small-Firms-Closing-In_-092425.pdf
- **Underlying data:** Census Bureau Business Trends and Outlook Survey (BTOS), supplemental AI questions collected December 4, 2023 - February 25, 2024

**Full data from Figure 5 (by employment band):**

| Employees | "AI not applicable" rate |
|-----------|--------------------------|
| 1-4       | ~82% (nearly 82%)        |
| 5-9       | ~78%                     |
| 10-19     | ~77%                     |
| 20-49     | ~75%                     |
| 50-99     | ~73%                     |
| 100-249   | ~72%                     |
| 250+      | ~68%                     |

**How to cite it:**
"According to a September 2025 SBA Research Spotlight on AI adoption, nearly 82 percent of businesses with fewer than five employees say generative AI is 'not applicable to their business' - making perceived irrelevance, not cost or security concerns, the dominant barrier."

**One nuance to flag:**
The 82% figure applies specifically to the 1-4 employee band (micro-businesses). The range across all small businesses is 68-82%. Saying "very small businesses" is accurate. Avoid "small businesses" broadly without the size qualifier.

---

## Stat 2: "Smaller businesses expect AI to increase hiring; larger businesses expect cuts"

### Verdict: CONFIRMED - the SBA report states this directly

**Exact source text:**
> "Figure 7 shows expectations for employment to change due to AI usage for employers of various sizes. **Small employers are most likely to expect AI usage to increase their employment needs, and least likely to expect AI usage to decrease their employment.**"

**Source:** Same SBA Research Spotlight, September 24, 2025 (Figure 7, page 7)

**Full data from Figure 7 (by employment band):**

| Employees | Expect hiring to increase | Expect hiring to decrease | Net |
|-----------|---------------------------|---------------------------|-----|
| 1-4       | 6.4%                      | 5.7%                      | +0.7% (net positive) |
| 5-9       | 6.4%                      | 6.2%                      | +0.2% (net positive) |
| 10-19     | 7.3%                      | 6.8%                      | +0.5% (net positive, strongest) |
| 20-49     | 6.2%                      | 6.9%                      | -0.7% (net negative) |
| 50-99     | 7.0%                      | 8.3%                      | -1.3% (net negative) |
| 100-249   | 6.2%                      | 8.0%                      | -1.8% (net negative) |
| 250+      | 5.0%                      | 8.8%                      | -3.8% (most negative) |

**Key inflection:** The crossover point is at 20 employees. Businesses with 1-19 employees are net-positive (expect more hiring than cuts). Businesses with 20+ employees are net-negative. The 250+ band has the most negative gap (-3.8 points).

**How to cite it:**
"The same SBA study shows that small businesses - those with fewer than 20 employees - are more likely to expect AI to grow their headcount than shrink it. For businesses with 250 or more employees, the opposite is true: the expectation of job cuts outpaces hiring expectations by nearly 4 percentage points."

**The economic explanation (from the SBA report itself):**
The report cites Hicks-Marshall Laws of Derived Demand: small firms have elastic demand (more output leads to more customers and more hiring), while large firms have inelastic demand (more output on flat demand means fewer workers needed). The SBA uses this framing explicitly, so it's available as part of the sourced argument.

---

## Source Summary for Footnote/Endnote

> Robert Press, "AI in Business: Small Firms Closing In," SBA Office of Advocacy Research Spotlight, September 24, 2025. Data from the Census Bureau Business Trends and Outlook Survey (BTOS), December 2023 - February 2024. Available at: https://advocacy.sba.gov/wp-content/uploads/2025/09/Research-Spotlight-AI-in-Business-Small-Firms-Closing-In_-092425.pdf

---

## Data Freshness Note

The survey data underlying both figures was collected December 2023 - February 2024. The report was published September 2025. As of May 2026, this is approximately 2 years old. The overall adoption gap between small and large businesses has narrowed since then (Figure 1 in the same report shows convergence through August 2025), but the "not applicable" barrier and the employment expectation split are structural attitudes less likely to shift quarter-to-quarter. Both figures are appropriate to cite with the qualifier "as of 2024" or simply by noting the SBA publication date (September 2025).

---

## Dashboard Reference

A full interactive TAM/SAM/SOM analysis using this and other SBA/Census data sources is live at:
**http://100.120.116.15:8422/** (Tailscale, internal only)

To update: edit `/Users/justinmassa/vercel-deploys/remix-tam-sam-som/public/index.html`, then SCP to Kirby.
