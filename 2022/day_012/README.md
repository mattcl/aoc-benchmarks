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
| `kcen/2022/12/solve input-kcen` | 131.5 ± 1.3 | 129.5 | 134.9 | 110.77 ± 7.18 |
| `kcen/2022/12/solve input-lanjian` | 128.1 ± 1.2 | 125.6 | 131.1 | 107.96 ± 6.99 |
| `kcen/2022/12/solve input-mattcl` | 154.7 ± 1.6 | 152.5 | 158.0 | 130.35 ± 8.46 |
| `kcen/2022/12/solve input-pting` | 143.7 ± 1.4 | 141.8 | 147.6 | 121.07 ± 7.84 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 2.9 | 1.02 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.00 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.8 | 1.16 ± 0.09 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.1 | 1.08 ± 0.09 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.10 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.5 | 1.01 ± 0.10 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.3 | 1.20 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.15 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 43.9 ± 0.6 | 42.9 | 45.7 | 37.00 ± 2.43 |
| `python pting/day12/day12.py input-lanjian` | 40.4 ± 0.9 | 39.4 | 45.2 | 34.05 ± 2.30 |
| `python pting/day12/day12.py input-mattcl` | 50.9 ± 0.7 | 49.7 | 53.2 | 42.87 ± 2.81 |
| `python pting/day12/day12.py input-pting` | 47.0 ± 0.8 | 45.9 | 49.7 | 39.58 ± 2.62 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 145.5 ± 2.1 | 142.0 | 150.9 | 129.18 ± 8.52 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.7 ± 1.4 | 151.0 | 156.2 | 135.58 ± 8.80 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 2.0 | 1.20 ± 0.10 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.5 | 1.24 ± 0.11 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.3 | 3.7 | 1.24 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 1.8 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.4 ± 1.0 | 47.2 | 52.1 | 43.00 ± 2.91 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 40.8 ± 0.5 | 39.9 | 42.3 | 36.25 ± 2.38 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
