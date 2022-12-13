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
| `kcen/2022/12/solve input-kcen` | 135.0 ± 4.6 | 130.5 | 148.1 | 116.21 ± 8.87 |
| `kcen/2022/12/solve input-lanjian` | 132.1 ± 4.9 | 126.0 | 143.0 | 113.71 ± 8.86 |
| `kcen/2022/12/solve input-mattcl` | 157.5 ± 4.6 | 152.6 | 171.4 | 135.56 ± 10.10 |
| `kcen/2022/12/solve input-pting` | 145.8 ± 2.9 | 142.7 | 153.1 | 125.43 ± 8.94 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 1.8 | 1.09 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.06 ± 0.11 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.22 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.14 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.0 | 1.08 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 1.8 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.6 | 1.19 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.0 | 1.13 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 45.2 ± 1.5 | 43.4 | 49.9 | 38.86 ± 2.94 |
| `python pting/day12/day12.py input-lanjian` | 40.9 ± 1.2 | 39.6 | 47.1 | 35.19 ± 2.62 |
| `python pting/day12/day12.py input-mattcl` | 51.8 ± 1.4 | 50.1 | 56.9 | 44.60 ± 3.28 |
| `python pting/day12/day12.py input-pting` | 48.1 ± 1.8 | 46.1 | 53.9 | 41.42 ± 3.21 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 145.6 ± 1.3 | 143.5 | 148.8 | 135.63 ± 11.93 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 158.9 ± 2.5 | 155.6 | 163.4 | 148.02 ± 13.17 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.31 ± 0.15 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.35 ± 0.16 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.27 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 2.4 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.8 ± 0.9 | 47.6 | 51.2 | 45.41 ± 4.06 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 42.2 ± 1.8 | 40.4 | 50.2 | 39.28 ± 3.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
