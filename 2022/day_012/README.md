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
| `kcen/2022/12/solve input-kcen` | 131.1 ± 1.2 | 129.4 | 133.6 | 113.99 ± 6.18 |
| `kcen/2022/12/solve input-lanjian` | 128.6 ± 1.7 | 126.4 | 132.8 | 111.88 ± 6.16 |
| `kcen/2022/12/solve input-mattcl` | 153.8 ± 1.4 | 151.0 | 157.6 | 133.78 ± 7.25 |
| `kcen/2022/12/solve input-pting` | 144.6 ± 1.8 | 142.3 | 148.0 | 125.80 ± 6.90 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 1.7 | 1.10 ± 0.08 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.1 | 1.05 ± 0.08 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.6 | 1.22 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.14 ± 0.09 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.4 | 1.12 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.1 ± 0.1 | 1.1 | 1.8 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.19 ± 0.09 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.14 ± 0.09 |
| `python pting/day12/day12.py input-kcen` | 44.2 ± 0.9 | 42.9 | 49.5 | 38.45 ± 2.21 |
| `python pting/day12/day12.py input-lanjian` | 40.5 ± 0.6 | 39.8 | 43.0 | 35.25 ± 1.95 |
| `python pting/day12/day12.py input-mattcl` | 51.1 ± 0.8 | 50.0 | 54.2 | 44.41 ± 2.48 |
| `python pting/day12/day12.py input-pting` | 47.1 ± 0.8 | 46.1 | 49.4 | 40.96 ± 2.30 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.1 ± 1.2 | 140.6 | 145.0 | 137.61 ± 11.90 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.8 ± 1.3 | 151.0 | 156.3 | 147.93 ± 12.80 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.8 | 1.28 ± 0.14 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.2 | 1.35 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.26 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.0 ± 0.1 | 0.9 | 3.3 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.1 ± 0.7 | 47.0 | 49.8 | 46.28 ± 4.04 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.1 ± 0.8 | 40.0 | 44.8 | 39.50 ± 3.49 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
