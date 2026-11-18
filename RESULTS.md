# Archived experiment results

This index transcribes the original HTML reports without rerunning or modifying them. Open a linked HTML file locally in a browser to view its plots and interactive map; map tiles and external JavaScript require an internet connection. GitHub file previews do not execute the maps.

**Archive summary:** 33 recorded feasible, 5 recorded infeasible, 1 unknown.

**Showcased run:** `tsp_SAgreedy_report_20250707_001515.html` was separately checked against the shared data: all 304 patrol locations visited once, all 56 routes attached to their assigned depots, total travel time 2,205 minutes, and latest return 599 minutes. See the [interactive page source](docs/index.html) and [route verification summary](docs/assets/run-summary.json). The table below still preserves the original recorded labels.

**Status is historical, not independently verified.** `Recorded feasible` means the file says `Feasible: True`; `Recorded infeasible` means it says `False`. `Unknown` means no status is present. The current notebooks only test route duration in `feasible_solution`, which does not establish full coverage, uniqueness, or depot validity. Historical code versions may have differed.

Do not rank infeasible candidates alongside feasible solutions, or compare different instance sizes. The folders below indicate storage location, not verified instance size. In particular, one report stored in the full-instance folder has objective 458, matching the smaller-instance benchmark; its scope needs checking before comparison.

Objectives are recorded total travel times in minutes; arrival durations are in minutes. Run limits are seconds, not measured times to best solution.

## 2 Solving Actual Size Problem/Results from runs with different params

| Report | Recorded status | Objective | Latest arrival | Run limit (s) |
| --- | --- | ---: | ---: | ---: |
| [tsp_report_20250620_231558.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_report_20250620_231558.html) | Recorded infeasible | 2387.0 | 600.0 | 1800 |
| [tsp_report_20250621_125939.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_report_20250621_125939.html) | Recorded infeasible | 2277.0 | 598.0 | 1800 |
| [tsp_report_20250703_001348.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_report_20250703_001348.html) | Recorded infeasible | 589.0 | 588.0 | 1800 |
| [tsp_SAgreedy_report_20250702_153535.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250702_153535.html) | Recorded infeasible | 2226.0 | 600.0 | 1800 |
| [tsp_SAgreedy_report_20250702_161822.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250702_161822.html) | Recorded infeasible | 2208.0 | 599.0 | 1800 |
| [tsp_SAgreedy_report_20250702_173703.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250702_173703.html) | Recorded feasible | 2217.0 | 599.0 | 1800 |
| [tsp_SAgreedy_report_20250702_185922.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250702_185922.html) | Recorded feasible | 2236.0 | 599.0 | 1800 |
| [tsp_SAgreedy_report_20250702_210856.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250702_210856.html) | Recorded feasible | 2219.0 | 599.0 | 1800 |
| [tsp_SAgreedy_report_20250702_212304.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250702_212304.html) | Recorded feasible | 2509.0 | 600.0 | 600 |
| [tsp_SAgreedy_report_20250702_215445.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250702_215445.html) | Recorded feasible | 2270.0 | 600.0 | 1800 |
| [tsp_SAgreedy_report_20250702_230907.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250702_230907.html) | Recorded feasible | 2247.0 | 600.0 | 1800 |
| [tsp_SAgreedy_report_20250703_165023.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250703_165023.html) | Recorded feasible | 2233.0 | 600.0 | 1800 |
| [tsp_SAgreedy_report_20250703_173209.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250703_173209.html) | Recorded feasible | 2335.0 | 600.0 | 1800 |
| [tsp_SAgreedy_report_20250703_184912.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250703_184912.html) | Recorded feasible | 2246.0 | 598.0 | 1800 |
| [tsp_SAgreedy_report_20250704_004344.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_004344.html) | Recorded feasible | 2233.0 | 599.0 | 1800 |
| [tsp_SAgreedy_report_20250704_014845.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_014845.html) | Recorded feasible | 2229.0 | 600.0 | 3600 |
| [tsp_SAgreedy_report_20250704_183529.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_183529.html) | Recorded feasible | 2266 | 599 | 1800 |
| [tsp_SAgreedy_report_20250704_190827.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_190827.html) | Recorded feasible | 2297 | 600 | 1800 |
| [tsp_SAgreedy_report_20250704_194157.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_194157.html) | Recorded feasible | 2324 | 599 | 1800 |
| [tsp_SAgreedy_report_20250704_201740.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_201740.html) | Recorded feasible | 2264 | 600 | 1800 |
| [tsp_SAgreedy_report_20250704_204846.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_204846.html) | Recorded feasible | 2261 | 600 | 1800 |
| [tsp_SAgreedy_report_20250704_211911.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_211911.html) | Recorded feasible | 2281 | 599 | 1800 |
| [tsp_SAgreedy_report_20250704_214959.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_214959.html) | Recorded feasible | 2300 | 600 | 1800 |
| [tsp_SAgreedy_report_20250704_225407.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250704_225407.html) | Recorded feasible | 2245 | 598 | 1800 |
| [tsp_SAgreedy_report_20250705_135433.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_135433.html) | Recorded feasible | 2215 | 598 | 1800 |
| [tsp_SAgreedy_report_20250705_143549.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_143549.html) | Recorded feasible | 2347 | 600 | 1800 |
| [tsp_SAgreedy_report_20250705_145615.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_145615.html) | Recorded feasible | 458.0 | 594.0 | 1800 |
| [tsp_SAgreedy_report_20250705_151302.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_151302.html) | Recorded feasible | 2351 | 599 | 1800 |
| [tsp_SAgreedy_report_20250705_160040.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_160040.html) | Recorded feasible | 2292 | 599 | 1800 |
| [tsp_SAgreedy_report_20250705_164611.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_164611.html) | Recorded feasible | 2348 | 599 | 1800 |
| [tsp_SAgreedy_report_20250705_221131.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_221131.html) | Recorded feasible | 2261 | 597 | 1800 |
| [tsp_SAgreedy_report_20250705_225838.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_225838.html) | Recorded feasible | 2245 | 600 | 1800 |
| [tsp_SAgreedy_report_20250705_233856.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250705_233856.html) | Recorded feasible | 2323 | 596 | 1800 |
| [tsp_SAgreedy_report_20250706_215539.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250706_215539.html) | Recorded feasible | 2266 | 600 | 1800 |
| [tsp_SAgreedy_report_20250706_223226.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250706_223226.html) | Unknown | Not recorded | Not recorded | Not recorded |
| [tsp_SAgreedy_report_20250706_231151.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250706_231151.html) | Recorded feasible | 2208 | 599 | 1800 |
| [tsp_SAgreedy_report_20250707_001515.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250707_001515.html) | Recorded feasible | 2205 | 599 | 3600 |
| [tsp_SAgreedy_report_20250707_202336.html](2%20Solving%20Actual%20Size%20Problem/Results%20from%20runs%20with%20different%20params/tsp_SAgreedy_report_20250707_202336.html) | Recorded feasible | 2335 | 600 | 1800 |

## 3 Solving a Smaller Instance

| Report | Recorded status | Objective | Latest arrival | Run limit (s) |
| --- | --- | ---: | ---: | ---: |
| [tsp_SAgreedy_report_20250706_144858.html](3%20Solving%20a%20Smaller%20Instance/tsp_SAgreedy_report_20250706_144858.html) | Recorded feasible | 458.0 | 594.0 | 1800 |

