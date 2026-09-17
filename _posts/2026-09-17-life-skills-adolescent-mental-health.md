---
title: "Do Life Skills Programs Improve Adolescent Girls' Mental Health? Causal Evidence from Three Countries"
date: 2026-09-17
permalink: /posts/2026/09/life-skills-adolescent-mental-health/
tags:
  - Research
  - Causal Inference
  - Mental Health
  - Adolescents
---

Adolescent mental health is a growing policy concern in low- and middle-income countries, but the evidence base behind it is thin. Life skills programming, which teaches goal setting, self-efficacy, negotiation, and related skills, is one of the most widely deployed adolescent interventions in the world. Until recently there was very little causal evidence on whether it actually moves mental health outcomes.

A paper published in the *Journal of Human Resources* takes on that question directly, pooling three randomized controlled trials run in Tanzania, Bangladesh, and Ethiopia. The full citation is Shah, Baird, Seager, Avuwadah, Hamory, Sabarwal, and Vyas (2024), *Journal of Human Resources* 59(S), S317 to S364.

## The design

The paper is built around three separate experiments, each with a different program and a different randomization level, evaluated using a common set of mental health measures for girls aged 10 to 19.

* **Tanzania.** 1,449 adolescent girls across 79 communities. A goal setting intervention was randomized at the individual level, layered on top of communities that did or did not already host Empowerment and Livelihood for Adolescents (ELA) clubs.
* **Bangladesh.** 1,200 girls in grades 7 and 8, randomized at the school level across 100 schools. Arms included a Growth Mindset curriculum, the Girl Rising gender sensitization program, and both together. Delivery moved online during COVID-19 school closures.
* **Ethiopia.** 1,863 girls across 126 rural communities, randomized at the community level. The Act With Her program combined adolescent and caregiver training with community norm change activities, and some sites also received asset transfers.

## What the trials found

Every context saw a significant improvement in at least one component of mental health, but the pattern of results is more interesting than that headline suggests.

In **Bangladesh**, the Growth Mindset curriculum on its own raised socio-emotional development by 0.317 standard deviations and the overall mental health index by 0.286 standard deviations. Adding Girl Rising on top of it produced null effects.

In **Ethiopia**, Act With Her raised socio-emotional development by 0.158 standard deviations and the overall index by 0.172 standard deviations. Layering asset transfers onto the program muted those gains rather than amplifying them.

<svg class="bya-chart" viewBox="0 0 700 356" role="img" width="700" aria-label="Coefficient plot of the effect of each treatment arm on the mental health index in Bangladesh and Ethiopia, with 95 percent confidence intervals. Only the standalone arms are distinguishable from zero.">
<style>
.bya-chart{--s1:#2a78d6;--s2:#eb6834;font-family:inherit;max-width:100%;height:auto;display:block;margin:0 auto}
:root[data-theme="dark"] .bya-chart{--s1:#3987e5;--s2:#d95926}
.bya-chart text{fill:currentColor;font-family:inherit}
.bya-chart .ax{font-size:13px;opacity:.62}
.bya-chart .lab{font-size:14px}
.bya-chart .val{font-size:13px;font-weight:600}
.bya-chart .grp{font-size:12px;letter-spacing:.08em;text-transform:uppercase;opacity:.55}
.bya-chart .rule{stroke:currentColor;opacity:.16;stroke-width:1}
.bya-chart .zero{stroke:currentColor;opacity:.45;stroke-width:1.5}
.bya-chart .s1{fill:var(--s1);stroke:var(--s1)}
.bya-chart .s2{fill:var(--s2);stroke:var(--s2)}
</style>
<text x="8" y="22" class="lab" style="font-weight:700">Only the standalone programs shifted the index</text>
<text x="8" y="42" class="ax">Effect on the mental health index, in standard deviations (95% CI)</text>
<rect x="8" y="53" width="12" height="12" rx="3" class="s1"/>
<text x="26" y="63" class="lab">Program on its own</text>
<rect x="198" y="53" width="12" height="12" rx="3" class="s2"/>
<text x="216" y="63" class="lab">Program plus add-on</text>
<line x1="236.0" y1="74" x2="236.0" y2="294" class="rule"/>
<text x="236.0" y="314" class="ax" text-anchor="middle">-0.2</text>
<line x1="345.0" y1="74" x2="345.0" y2="294" class="zero"/>
<text x="345.0" y="314" class="ax" text-anchor="middle">+0.0</text>
<line x1="454.0" y1="74" x2="454.0" y2="294" class="rule"/>
<text x="454.0" y="314" class="ax" text-anchor="middle">+0.2</text>
<line x1="563.0" y1="74" x2="563.0" y2="294" class="rule"/>
<text x="563.0" y="314" class="ax" text-anchor="middle">+0.4</text>
<line x1="672.0" y1="74" x2="672.0" y2="294" class="rule"/>
<text x="672.0" y="314" class="ax" text-anchor="middle">+0.6</text>
<text x="8" y="90" class="grp">BANGLADESH</text>
<text x="222" y="113" class="lab" text-anchor="end">Growth Mindset only</text>
<line x1="367.3" y1="108" x2="634.4" y2="108" class="s1" stroke-width="2" stroke-linecap="round" opacity=".55"/>
<circle cx="500.9" cy="108" r="5.5" class="s1"/>
<text x="643.4" y="113" class="val">+0.29*</text>
<text x="222" y="159" class="lab" text-anchor="end">Growth Mindset + Girl Rising</text>
<line x1="292.6" y1="154" x2="495.5" y2="154" class="s2" stroke-width="2" stroke-linecap="round" opacity=".55"/>
<circle cx="394.1" cy="154" r="5.5" class="s2"/>
<text x="504.5" y="159" class="val">+0.09</text>
<text x="8" y="208" class="grp">ETHIOPIA</text>
<text x="222" y="231" class="lab" text-anchor="end">Act With Her only</text>
<line x1="362.9" y1="226" x2="514.6" y2="226" class="s1" stroke-width="2" stroke-linecap="round" opacity=".55"/>
<circle cx="438.7" cy="226" r="5.5" class="s1"/>
<text x="523.6" y="231" class="val">+0.17*</text>
<text x="222" y="277" class="lab" text-anchor="end">Act With Her + transfers</text>
<line x1="298.2" y1="272" x2="460.5" y2="272" class="s2" stroke-width="2" stroke-linecap="round" opacity=".55"/>
<circle cx="379.3" cy="272" r="5.5" class="s2"/>
<text x="469.5" y="277" class="val">+0.06</text>
<text x="8" y="344" class="ax">Estimates from Shah et al. (2024), Table 4. * significant at the 5% level.</text>
</svg>

**Tanzania** produced the sharpest result, and it runs the other way. Goal setting delivered on its own *increased* moderate to severe depression by 8.6 percentage points. Where ELA clubs were already running, that effect was 11.1 percentage points lower, which is enough to cancel it out. The intervention was identical in both places. What differed was the support structure around it.

## Why it matters

The obvious reading is that life skills programming works, and in an aggregate sense it does. The more useful reading is that bundling is not automatically better, and that an intervention which raises aspirations without providing any means to act on them can do harm.

Asking a girl to set ambitious goals is a very different experience depending on whether she has a club, a mentor, and a peer group to pursue them with. Where that scaffolding existed, goal setting helped. Where it did not, it appears to have produced frustration rather than agency. Two of the three trials show the same shape of result: the leanest version of the program outperformed the more elaborate one.

For anyone designing adolescent programs, that is a caution against the instinct to add components. It also argues for measuring mental health outcomes routinely rather than assuming that a well-intentioned empowerment program cannot hurt.

The paper is available through the [Journal of Human Resources](https://jhr.uwpress.org/content/59/S/S317), and a summary of it sits on the [Research]({{ base_path }}/publications/) page.
