# Scoring Systems

OWLCMS supports several scoring systems for best-athlete awards, score-based medals, score-based team rankings, and results reports.

This page summarizes each scoring family in the order used by OWLCMS selectors: **GAMX**, **Q**, **Sinclair**, and **Robi**, followed by the **at SR Category Weight** variants.

The term "peer-relative" refers to the population used for ranking.  Depending on the scoring system, your peers are the people in the same body weight category, irrespective of age, or the people that weigh the same as you, or the the people that weigh the same and and have the same age.

The details of each system are described below.

## Summary Table

<table style="display: table; width: 100%; border-collapse: collapse; font-size: 0.92em;">
  <thead>
    <tr style="background-color: #dce5ee; text-align: left;">
      <th style="border: 1px solid #c5cfd9; padding: 8px; width: 15%;">Short Label</th>
      <th style="border: 1px solid #c5cfd9; padding: 8px; width: 27%;">Selector Label</th>
      <th style="border: 1px solid #c5cfd9; padding: 8px; width: 30%;">Basis / Adjustments</th>
      <th style="border: 1px solid #c5cfd9; padding: 8px; width: 28%;">Typical Use</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #edf2f7;">
      <td colspan="4" style="border: 1px solid #c5cfd9; padding: 6px 8px;"><strong>GAMX Family</strong></td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>GAMX</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX (Total, 15+, BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Peer-relative score at actual body weight (world elite &approx; 1000); equitable across men and women</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Official IWF ranking system (since May 2026); best athlete and mixed team awards</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>GAMX-M</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX-M (Total, Masters, Age- and BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Peer-relative score adjusted for Masters age and body weight</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Masters best-athlete, score-based medal, and team rankings</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>GAMX-U</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX-U (Total, 7-17, Age- and BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Peer-relative score adjusted for youth age and body weight (USA national U11&ndash;U20 data)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Youth competitions where physical development varies sharply by age</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>GAMX-A</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX-A (Total, 13-40, Age- and BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Peer-relative score adjusted for age and body weight across ages 13&ndash;40 (large USA meets)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Club or regional meets comparing best effort across youth, senior, and masters</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>GAMX-S</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX-S (Snatch, 15+, BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Peer-relative snatch score at actual body weight</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Best snatch award and results reports</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>GAMX-J</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX-J (Clean &amp; Jerk, 15+, BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Peer-relative clean &amp; jerk score at actual body weight</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Best clean &amp; jerk award and results reports</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>GAMX-SM</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX-SM (Snatch, Masters, Age- and BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Peer-relative snatch score adjusted for Masters age and body weight</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Masters best snatch award and results reports</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>GAMX-JM</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX-JM (Clean &amp; Jerk, Masters, Age- and BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Peer-relative clean &amp; jerk score adjusted for Masters age and body weight</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Masters best clean &amp; jerk award and results reports</td>
    </tr>
    <tr style="background-color: #edf2f7;">
      <td colspan="4" style="border: 1px solid #c5cfd9; padding: 6px 8px;"><strong>Q Family</strong></td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>QPoints</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">QPoints (Total, 15+, BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Body-weight-adjusted total using modern statistical modeling</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Alternative to Sinclair for ages 15+</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>QMasters</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">QMasters (Total, Masters, Age- and BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Age- and body-weight-adjusted total for Masters</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">IMWA and Masters federations (since 2025)</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>QYouth</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">QYouth (Total, 7-20, Age- and BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Age- and body-weight-adjusted total for youth</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Youth score-based medals and best-lifter awards</td>
    </tr>
    <tr style="background-color: #edf2f7;">
      <td colspan="4" style="border: 1px solid #c5cfd9; padding: 6px 8px;"><strong>Sinclair</strong></td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>Sinclair</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Sinclair (Total, 15+, BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Body-weight-adjusted total derived from World Championship data (15+)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Legacy scoring; still used by some federations</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>SMHF</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">SMHF (Total, Masters, Age- and BW-Adjusted)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Sinclair&ndash;Meltzer&ndash;Huebner&ndash;Faber; age- and body-weight-adjusted total (uses 2020 Sinclair)</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Traditional Masters formula</td>
    </tr>
    <tr style="background-color: #edf2f7;">
      <td colspan="4" style="border: 1px solid #c5cfd9; padding: 6px 8px;"><strong>Robi</strong></td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>Robi</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Robi</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Per-category IWF benchmark points</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Former IWF system; evaluates category performance rather than body weight</td>
    </tr>
    <tr style="background-color: #edf2f7;">
      <td colspan="4" style="border: 1px solid #c5cfd9; padding: 6px 8px;"><strong>At SR Category Weight</strong></td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>Cat. Wt. GAMX</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX at SR Category Weight</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">GAMX computed at the upper limit of the athlete's Senior IWF category</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Best-athlete award based on international medal potential</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>Category QPoints</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">QPoints at SR Category Weight</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">QPoints computed at the upper limit of the athlete's Senior IWF category</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Best-athlete award based on medal potential using QPoints</td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top; white-space: nowrap;"><strong>Category Sinclair</strong></td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Sinclair at SR Category Weight</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Sinclair computed at the upper limit of the athlete's Senior IWF category</td>
      <td style="border: 1px solid #d0d7de; padding: 6px 8px; vertical-align: top;">Best-athlete award based on medal potential using Sinclair</td>
    </tr>
  </tbody>
</table>

## GAMX Family

**GAMX** is the official IWF ranking system. Rather than computing an adjusted total in kilograms, GAMX produces a score that positions an athlete relative to peers worldwide. World-elite performances score in the **1000** range.

GAMX is designed to be equitable across men and women: a woman with a higher GAMX score ranks higher relative to her peers than a man with a lower GAMX score. This makes GAMX directly usable for mixed-gender rankings and mixed team scoring.

- **`GAMX` — `GAMX (Total, 15+, BW-Adjusted)`**: Measures how strong an athlete's total is relative to lifters worldwide **at their actual body weight**.

- **`GAMX-M` — `GAMX-M (Total, Masters, Age- and BW-Adjusted)`**: Extends GAMX with age adjustment for Masters lifters.

- **`GAMX-U` — `GAMX-U (Total, 7-17, Age- and BW-Adjusted)`**: Built for children and youth, where physical development changes rapidly with age (a 12-year-old at 55 kg is not comparable to a 17-year-old at 55 kg). Calibrated from USA national youth and junior meets (U11, U13, U15, U17, U20).

  It is recommended to give different awards to the younger athletes (say U11+U13 than for older ones say U15-U17)

- **`GAMX-A` — `GAMX-A (Total, 13-40, Age- and BW-Adjusted)`**: Calibrated from large USA meets (1,500+ athletes) and compensates for age across ages 13 to 40, allowing lifters of different ages (for example, an 18-year-old and a 38-year-old) to be compared on "best effort". Most useful for club or regional meets as an emulation mechanism.

- **Single-lift variants** (`GAMX-S`, `GAMX-J`, `GAMX-SM`, `GAMX-JM`): Used for best snatch and best clean & jerk awards and in results reports. They are excluded from championship best-athlete total selectors.

## Q Family

The **Q** family adjusts an athlete's total using modern statistical modeling (the same general goal as Sinclair, with better statistics, and exclusion of doping cases).

- **`QPoints` — `QPoints (Total, 15+, BW-Adjusted)`**: Body-weight-adjusted total for athletes aged 15 and older.
- **`QMasters` — `QMasters (Total, Masters, Age- and BW-Adjusted)`**: Adjusts for both age and body weight. An older athlete receives a higher score than a younger athlete at the same body weight and total, because with lower muscle mass the same lift represents a greater relative effort.
- **`QYouth` — `QYouth (Total, 7-20, Age- and BW-Adjusted)`**: Adjusts for both age and body weight together for young athletes.

## Sinclair

- **`Sinclair` — `Sinclair (Total, 15+, BW-Adjusted)`**: Derived from World Championship data (ages 15+), adjusting an athlete's total based on body weight. Coefficients are published on a 4-year cycle; OWLCMS lets you choose which cycle to use in [Competition Rules Reference](../100-AdvancedTopics/020-ReferenceCompetiionInformationAndRules.md).
- **`SMHF` — `SMHF (Total, Masters, Age- and BW-Adjusted)`**: The traditional Masters age- and body-weight-adjusted Sinclair formula. Per Masters rules, SMHF always uses the 2020 Sinclair coefficients regardless of the Sinclair cycle selected for regular Sinclair.

> **Important limitation:** Sinclair is an older formula with known statistical flaws. In particular, using Sinclair to judge best effort for children is methodologically broken—it is fitted to senior/15+ World Championship data and ignores youth physical development—even though some competitions still use it. For children, use `GAMX-U` or `QYouth`; for athletes 15+, prefer `GAMX` or `QPoints`.

## Robi

- **`Robi`**: The former IWF scoring system. Because Robi points were calibrated per weight category rather than strictly by body weight, Robi evaluated performance relative to category benchmarks rather than "best lifter pound-for-pound".

## Scoring at SR Category Weight

OWLCMS provides "at SR Category Weight" variants across the GAMX, Q, and Sinclair families:

- **`Cat. Wt. GAMX` — `GAMX at SR Category Weight`**
- **`Category QPoints` — `QPoints at SR Category Weight`**
- **`Category Sinclair` — `Sinclair at SR Category Weight`**

Instead of evaluating the formula at the athlete's actual weigh-in body weight, these options evaluate it at the **upper weight limit of the athlete's Senior IWF bodyweight category**.

For example, a 78 kg woman competing in the 86 kg category is scored as if she weighed **86 kg**. Being well below the category limit means she is unlikely to be near the top of that category or to have medal potential in that category at an international meet.

This reflects two different philosophies for a "best athlete" award:

- **At actual body weight** (`GAMX`, `QPoints`, `Sinclair`): "Best lifter pound-for-pound"—how good a performance is relative to all lifters at the same body weight.
- **At SR category weight** (`GAMX at SR Category Weight`, `QPoints at SR Category Weight`, `Sinclair at SR Category Weight`): **Best medal potential**, assuming an athlete will compete close to the top of their weight category. Federations such as Canada use category-weight formulas for best-athlete awards on this principle (similar in spirit to how Robi operated per category).

## Where Scoring Systems Are Configured

- **Best-athlete and team awards**: Configured per championship in [Championships and Awards](050-Championships.md).
- **Score-based medals**: Configured per age group; see [Score-based Medals](../040-CompetitionSetup/060-ScoreBasedCompetitions.md).
- **Additional computed scores and Sinclair cycle**: Configured under **Scoring System Options** in [Competition Rules Reference](../100-AdvancedTopics/020-ReferenceCompetiionInformationAndRules.md).
