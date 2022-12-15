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
| `kcen/2022/12/solve input-kcen` | 132.1 ± 1.6 | 129.5 | 134.7 | 106.40 ± 7.14 |
| `kcen/2022/12/solve input-lanjian` | 126.8 ± 1.1 | 124.9 | 128.7 | 102.15 ± 6.80 |
| `kcen/2022/12/solve input-mattcl` | 153.7 ± 1.4 | 150.9 | 156.6 | 123.79 ± 8.25 |
| `kcen/2022/12/solve input-pting` | 143.5 ± 1.5 | 141.8 | 148.0 | 115.62 ± 7.73 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.04 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.3 ± 0.1 | 1.1 | 3.3 | 1.03 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.7 | 1.13 ± 0.09 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 5.5 | 1.07 ± 0.12 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.2 | 1.2 | 7.1 | 1.07 ± 0.16 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.2 | 1.3 | 5.4 | 1.15 ± 0.14 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.1 | 1.08 ± 0.09 |
| `python pting/day12/day12.py input-kcen` | 47.6 ± 1.6 | 45.8 | 54.0 | 38.31 ± 2.85 |
| `python pting/day12/day12.py input-lanjian` | 42.5 ± 0.7 | 41.6 | 45.8 | 34.22 ± 2.32 |
| `python pting/day12/day12.py input-mattcl` | 55.0 ± 1.7 | 53.5 | 59.6 | 44.33 ± 3.22 |
| `python pting/day12/day12.py input-pting` | 50.4 ± 0.5 | 49.4 | 51.9 | 40.56 ± 2.71 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.5 ± 1.5 | 139.9 | 144.8 | 133.90 ± 8.17 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.7 ± 1.9 | 151.1 | 159.2 | 144.44 ± 8.87 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 2.6 | 1.25 ± 0.11 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.31 ± 0.10 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 5.4 | 1.25 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 1.5 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.8 ± 1.2 | 49.2 | 56.1 | 47.74 ± 3.10 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.5 ± 0.8 | 40.6 | 45.5 | 38.98 ± 2.47 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
