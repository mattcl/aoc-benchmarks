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
| `kcen/2022/12/solve input-kcen` | 131.4 ± 2.7 | 128.7 | 137.8 | 110.65 ± 7.11 |
| `kcen/2022/12/solve input-lanjian` | 126.8 ± 1.3 | 124.4 | 128.9 | 106.78 ± 6.58 |
| `kcen/2022/12/solve input-mattcl` | 154.2 ± 1.9 | 152.0 | 158.4 | 129.88 ± 8.06 |
| `kcen/2022/12/solve input-pting` | 144.5 ± 1.4 | 142.3 | 147.2 | 121.71 ± 7.49 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.04 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.6 | 1.02 ± 0.09 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.3 | 1.14 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.2 | 1.2 | 6.2 | 1.12 ± 0.17 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.2 | 1.08 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.3 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.5 | 1.16 ± 0.10 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 4.3 | 1.13 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 46.6 ± 0.9 | 45.6 | 49.4 | 39.23 ± 2.50 |
| `python pting/day12/day12.py input-lanjian` | 42.2 ± 0.6 | 41.0 | 43.8 | 35.58 ± 2.23 |
| `python pting/day12/day12.py input-mattcl` | 54.8 ± 1.7 | 53.1 | 61.6 | 46.18 ± 3.13 |
| `python pting/day12/day12.py input-pting` | 50.5 ± 0.6 | 49.3 | 52.3 | 42.57 ± 2.64 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.0 ± 1.4 | 141.0 | 147.7 | 134.08 ± 9.50 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.7 ± 1.3 | 151.7 | 156.7 | 144.15 ± 10.18 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 4.4 | 1.25 ± 0.13 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.7 | 1.32 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.2 | 1.2 | 5.4 | 1.26 ± 0.18 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 2.1 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.2 ± 0.6 | 49.3 | 52.5 | 47.12 ± 3.35 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.7 ± 0.7 | 40.7 | 45.7 | 39.08 ± 2.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
