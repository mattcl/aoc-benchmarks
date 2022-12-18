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
| `kcen/2022/12/solve input-kcen` | 131.9 ± 2.7 | 128.6 | 138.8 | 105.00 ± 11.43 |
| `kcen/2022/12/solve input-lanjian` | 128.9 ± 4.2 | 125.1 | 144.6 | 102.63 ± 11.47 |
| `kcen/2022/12/solve input-mattcl` | 152.6 ± 2.0 | 149.8 | 157.0 | 121.46 ± 13.08 |
| `kcen/2022/12/solve input-pting` | 142.9 ± 1.1 | 140.7 | 144.7 | 113.70 ± 12.19 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.2 | 1.1 | 7.3 | 1.01 ± 0.20 |
| `lanjian/day_12 input-lanjian` | 1.3 ± 0.1 | 1.1 | 5.0 | 1.01 ± 0.15 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.4 | 1.14 ± 0.14 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.06 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 5.9 | 1.04 ± 0.15 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.3 ± 0.1 | 1.1 | 4.1 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.4 | 1.15 ± 0.14 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.1 | 1.10 ± 0.14 |
| `python pting/day12/day12.py input-kcen` | 47.0 ± 1.1 | 45.6 | 50.8 | 37.37 ± 4.09 |
| `python pting/day12/day12.py input-lanjian` | 42.9 ± 1.1 | 41.3 | 47.7 | 34.13 ± 3.74 |
| `python pting/day12/day12.py input-mattcl` | 54.5 ± 1.1 | 52.9 | 58.9 | 43.35 ± 4.72 |
| `python pting/day12/day12.py input-pting` | 50.0 ± 0.8 | 48.9 | 52.9 | 39.76 ± 4.30 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 141.9 ± 1.7 | 139.9 | 147.0 | 127.69 ± 9.99 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.7 ± 1.2 | 150.8 | 154.9 | 137.42 ± 10.69 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.0 | 1.22 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.1 | 1.29 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 1.8 | 1.23 ± 0.11 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 2.9 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.3 ± 0.9 | 48.8 | 54.4 | 45.22 ± 3.60 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.3 ± 0.6 | 40.4 | 43.1 | 37.15 ± 2.92 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
