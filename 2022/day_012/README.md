# Day 12 benchmarks

[link to problem](http://adventofcode.com/2022/day/12)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 12)


- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve input-kcen` | 131.0 ± 1.0 | 129.1 | 133.2 | 107.87 ± 7.25 |
| `kcen/2022/12/solve input-lanjian` | 127.6 ± 1.0 | 125.5 | 130.0 | 105.05 ± 7.06 |
| `kcen/2022/12/solve input-mattcl` | 154.5 ± 1.8 | 152.0 | 159.0 | 127.20 ± 8.61 |
| `kcen/2022/12/solve input-pting` | 143.7 ± 1.4 | 141.3 | 146.0 | 118.36 ± 7.98 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.4 | 1.09 ± 0.13 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.9 | 1.02 ± 0.09 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.18 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.11 ± 0.09 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 2.6 | 1.08 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.3 | 1.18 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.12 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 44.3 ± 0.9 | 43.0 | 47.9 | 36.51 ± 2.54 |
| `python pting/day12/day12.py input-lanjian` | 40.3 ± 0.8 | 39.3 | 43.5 | 33.19 ± 2.31 |
| `python pting/day12/day12.py input-mattcl` | 50.7 ± 0.8 | 49.5 | 53.2 | 41.76 ± 2.86 |
| `python pting/day12/day12.py input-pting` | 47.2 ± 0.9 | 45.9 | 49.7 | 38.85 ± 2.69 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.7 ± 2.9 | 141.0 | 154.5 | 134.81 ± 9.38 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.3 ± 1.4 | 150.4 | 156.6 | 143.85 ± 9.68 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.25 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 4.1 | 1.33 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.24 ± 0.11 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 2.0 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.3 ± 1.5 | 47.2 | 58.1 | 45.36 ± 3.34 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.2 ± 0.9 | 39.8 | 45.1 | 38.63 ± 2.70 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
