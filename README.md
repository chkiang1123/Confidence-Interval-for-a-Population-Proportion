# Confidence-Interval-for-a-Population-Proportion

Teaching resources for **HKDSE Mathematics Extended Part — Module 1 (Calculus and Statistics)**,
*Learning Unit 23: Confidence interval for a population proportion* (Objective 23.1).

Based on the Explanatory Notes to the Senior Secondary Mathematics Curriculum (Module 1) and
**HKDSE 2020 Mathematics M1 Question 4**.

## Pages

| File | What it is |
|------|-----------|
| `index.html` | The full guide. Sampling-distribution simulator, CI-coverage animation, z-explorer, calculator, DSE 2020 Q4 worked solution, and a DSE-style practice generator. |
| `confidence-interval-proportion-v2.html` | A second, shorter visual version. Interactive normal curve (z → confidence level), a build-your-own-interval number line, and the 2020 Q4 solution revealed step by step. |

## The content

- Sample proportion $p_s = x/n$ as a point estimate of the unknown population proportion $p$
- Sampling distribution: $P_s \sim N\!\left(p,\ \dfrac{p(1-p)}{n}\right)$ for large $n$
- Standard error approximated by replacing the unknown $p$ with $p_s$
- Confidence interval $p_s \pm z\sqrt{\dfrac{p_s(1-p_s)}{n}}$, with $z = 1.96$ (95%) and $z = 2.575$ (99%)
- Width $= 2z\cdot\text{SE}$, and the reverse problem: given the width, recover $z$ then $\beta$
- Common mistakes: forgetting the $\div n$, treating the width as the margin of error, using a one-tailed area

## Run

No build step. Open either file in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Maths is typeset with KaTeX from a CDN, so the first load needs an internet connection.
