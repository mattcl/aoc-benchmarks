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
| `kcen/2022/12/solve input-kcen` | 131.6 ± 1.5 | 129.8 | 134.5 | 114.24 ± 6.76 |
| `kcen/2022/12/solve input-lanjian` | 130.0 ± 2.0 | 126.0 | 133.4 | 112.81 ± 6.77 |
| `kcen/2022/12/solve input-mattcl` | 154.1 ± 1.9 | 150.2 | 157.2 | 133.80 ± 7.94 |
| `kcen/2022/12/solve input-pting` | 143.7 ± 1.4 | 141.4 | 146.7 | 124.74 ± 7.34 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.2 | 1.07 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.7 | 1.04 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.19 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.13 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.2 | 1.07 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 1.8 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.2 | 3.1 | 1.18 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.8 | 1.16 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 44.0 ± 0.7 | 43.0 | 46.7 | 38.19 ± 2.30 |
| `python pting/day12/day12.py input-lanjian` | 40.8 ± 0.8 | 39.5 | 43.3 | 35.41 ± 2.16 |
| `python pting/day12/day12.py input-mattcl` | 50.8 ± 0.7 | 49.7 | 53.5 | 44.09 ± 2.63 |
| `python pting/day12/day12.py input-pting` | 47.1 ± 0.9 | 45.9 | 49.9 | 40.90 ± 2.51 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 145.3 ± 1.5 | 142.3 | 148.3 | 139.18 ± 8.34 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.5 ± 1.8 | 149.6 | 155.9 | 146.14 ± 8.81 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.7 | 1.29 ± 0.13 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.7 | 1.34 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.24 ± 0.10 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.0 ± 0.1 | 0.9 | 1.6 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.1 ± 0.8 | 47.1 | 51.6 | 46.12 ± 2.84 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 40.8 ± 0.6 | 39.6 | 43.4 | 39.12 ± 2.38 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
