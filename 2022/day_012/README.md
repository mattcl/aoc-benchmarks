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
| `kcen/2022/12/solve input-kcen` | 130.6 ± 0.8 | 128.9 | 132.0 | 109.14 ± 5.89 |
| `kcen/2022/12/solve input-lanjian` | 126.9 ± 1.4 | 124.9 | 131.8 | 106.03 ± 5.80 |
| `kcen/2022/12/solve input-mattcl` | 152.8 ± 1.4 | 150.0 | 154.9 | 127.66 ± 6.93 |
| `kcen/2022/12/solve input-pting` | 142.9 ± 1.0 | 141.3 | 145.6 | 119.41 ± 6.45 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 4.6 | 1.07 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 4.2 | 1.03 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.19 ± 0.09 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.9 | 1.12 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.6 | 1.09 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.6 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.19 ± 0.09 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 1.8 | 1.14 ± 0.08 |
| `python pting/day12/day12.py input-kcen` | 44.0 ± 1.1 | 42.7 | 51.1 | 36.81 ± 2.18 |
| `python pting/day12/day12.py input-lanjian` | 39.9 ± 0.5 | 39.0 | 41.3 | 33.34 ± 1.84 |
| `python pting/day12/day12.py input-mattcl` | 51.0 ± 1.1 | 49.8 | 54.8 | 42.60 ± 2.46 |
| `python pting/day12/day12.py input-pting` | 47.1 ± 0.9 | 46.1 | 50.0 | 39.33 ± 2.25 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 141.7 ± 0.7 | 140.7 | 143.3 | 132.57 ± 9.20 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.5 ± 1.3 | 150.9 | 156.4 | 142.73 ± 9.96 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.7 | 1.27 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.1 | 1.34 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.9 | 1.27 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 2.4 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.3 ± 3.2 | 46.6 | 70.3 | 45.18 ± 4.35 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 40.9 ± 0.6 | 39.7 | 42.7 | 38.26 ± 2.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
