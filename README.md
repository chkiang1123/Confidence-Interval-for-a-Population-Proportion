# Confidence Interval for a Population Proportion

Offline-friendly teaching pages for the HKDSE Mathematics Module 1 (Calculus & Statistics) topic
**"Confidence interval for a population proportion"**.

## Pages

| File | Description |
| --- | --- |
| `index.html` | Long-form lesson: full derivation, worked examples, canvas simulators. Uses MathJax from CDN. |
| `confidence-interval-proportion-v2.html` | **New condensed visual version.** Gradient header + sticky nav, KaTeX typesetting, hand-drawn SVG visuals (normal curve with shaded tails, number line for the interval), an interactive playground, the HKDSE 2020 M1 Q4 walkthrough with step-by-step reveal, and a common-mistakes section. |

## Topics covered

- Sample proportion $\hat p = \dfrac{x}{n}$ as a point estimate of the population proportion $p$
- Sampling distribution of $\hat p$ and the normal approximation
  $\hat p \sim N\!\left(p,\ \sqrt{\dfrac{p(1-p)}{n}}\right)$
- Confidence interval
  $\hat p \pm z\sqrt{\dfrac{\hat p(1-\hat p)}{n}}$
- Critical values $z_{0.05}=1.645$, $z_{0.025}=1.96$, $z_{0.005}=2.575$
- Width of the interval $= 2z\sqrt{\dfrac{\hat p(1-\hat p)}{n}}$ — and how $n$ and the confidence
  level affect it
- Worked HKDSE example: $n=841$, $x=441$, interval width $0.088$

## Running

Just open either `.html` file in a browser — no build step, no server.
`index.html` and `confidence-interval-proportion-v2.html` load KaTeX / MathJax from a CDN, so an
internet connection is needed for the formulas to render nicely (the text still reads without it).
