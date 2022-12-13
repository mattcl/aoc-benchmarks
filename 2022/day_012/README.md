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
| `kcen/2022/12/solve input-kcen` | 133.3 ± 1.3 | 131.1 | 137.2 | 111.84 ± 8.22 |
| `kcen/2022/12/solve input-lanjian` | 130.4 ± 1.4 | 127.6 | 132.5 | 109.39 ± 8.06 |
| `kcen/2022/12/solve input-mattcl` | 156.1 ± 2.0 | 153.2 | 159.9 | 130.89 ± 9.68 |
| `kcen/2022/12/solve input-pting` | 147.8 ± 4.0 | 143.9 | 157.2 | 123.95 ± 9.64 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.08 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.3 ± 0.1 | 1.1 | 3.4 | 1.07 ± 0.14 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.7 | 1.20 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.4 ± 0.1 | 1.2 | 4.4 | 1.15 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.0 | 1.06 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.0 | 1.16 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.5 | 1.14 ± 0.12 |
| `python pting/day12/day12.py input-kcen` | 44.7 ± 0.9 | 43.4 | 47.1 | 37.47 ± 2.83 |
| `python pting/day12/day12.py input-lanjian` | 41.3 ± 1.1 | 39.5 | 45.7 | 34.62 ± 2.69 |
| `python pting/day12/day12.py input-mattcl` | 51.5 ± 1.0 | 50.0 | 54.1 | 43.21 ± 3.27 |
| `python pting/day12/day12.py input-pting` | 47.6 ± 1.3 | 45.9 | 51.2 | 39.96 ± 3.11 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 144.3 ± 1.2 | 142.7 | 148.5 | 134.35 ± 12.15 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 154.4 ± 0.8 | 153.4 | 156.5 | 143.73 ± 12.96 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.3 | 2.1 | 1.28 ± 0.13 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.4 | 1.34 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.9 | 1.25 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 3.8 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.7 ± 0.7 | 47.5 | 50.3 | 45.35 ± 4.14 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.3 ± 0.7 | 40.3 | 43.9 | 38.46 ± 3.53 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
