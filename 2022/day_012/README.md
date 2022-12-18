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
| `kcen/2022/12/solve input-kcen` | 129.6 ± 1.2 | 127.5 | 132.4 | 107.87 ± 8.03 |
| `kcen/2022/12/solve input-lanjian` | 126.8 ± 1.9 | 124.7 | 134.4 | 105.51 ± 7.94 |
| `kcen/2022/12/solve input-mattcl` | 152.4 ± 1.8 | 150.3 | 157.0 | 126.80 ± 9.47 |
| `kcen/2022/12/solve input-pting` | 142.4 ± 1.2 | 140.9 | 146.5 | 118.48 ± 8.80 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.5 | 1.05 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 6.2 | 1.03 ± 0.14 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.6 | 1.19 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 5.4 | 1.11 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 2.5 | 1.09 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 5.2 | 1.18 ± 0.13 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 5.1 | 1.14 ± 0.15 |
| `python pting/day12/day12.py input-kcen` | 46.1 ± 0.8 | 44.9 | 50.0 | 38.39 ± 2.92 |
| `python pting/day12/day12.py input-lanjian` | 42.8 ± 0.8 | 41.7 | 44.9 | 35.62 ± 2.70 |
| `python pting/day12/day12.py input-mattcl` | 54.6 ± 1.5 | 52.7 | 60.5 | 45.44 ± 3.57 |
| `python pting/day12/day12.py input-pting` | 50.1 ± 1.0 | 48.8 | 54.3 | 41.70 ± 3.19 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 141.3 ± 1.2 | 139.5 | 143.4 | 126.51 ± 18.91 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 151.7 ± 0.9 | 149.4 | 153.4 | 135.77 ± 20.28 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.22 ± 0.20 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.4 | 1.3 | 17.8 | 1.30 ± 0.44 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.22 ± 0.20 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.2 | 1.0 | 4.7 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.1 ± 0.7 | 48.9 | 52.3 | 44.86 ± 6.72 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.2 ± 0.7 | 40.2 | 42.8 | 36.86 ± 5.53 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
