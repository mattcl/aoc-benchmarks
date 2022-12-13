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
| `kcen/2022/12/solve input-kcen` | 131.8 ± 1.7 | 129.3 | 136.7 | 114.97 ± 7.25 |
| `kcen/2022/12/solve input-lanjian` | 127.2 ± 1.5 | 125.3 | 130.4 | 110.95 ± 6.97 |
| `kcen/2022/12/solve input-mattcl` | 155.0 ± 2.9 | 151.9 | 164.3 | 135.21 ± 8.72 |
| `kcen/2022/12/solve input-pting` | 143.5 ± 1.5 | 141.5 | 147.2 | 125.12 ± 7.82 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 4.4 | 1.06 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.1 | 1.03 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.19 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.4 | 1.13 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.6 | 1.08 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.1 ± 0.1 | 1.0 | 1.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.3 ± 0.1 | 1.2 | 3.6 | 1.18 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.12 ± 0.09 |
| `python pting/day12/day12.py input-kcen` | 44.3 ± 0.8 | 43.0 | 46.6 | 38.63 ± 2.48 |
| `python pting/day12/day12.py input-lanjian` | 40.0 ± 0.7 | 38.9 | 43.1 | 34.88 ± 2.24 |
| `python pting/day12/day12.py input-mattcl` | 50.6 ± 1.0 | 49.3 | 54.1 | 44.09 ± 2.86 |
| `python pting/day12/day12.py input-pting` | 47.1 ± 0.9 | 45.8 | 50.7 | 41.04 ± 2.65 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.5 ± 1.6 | 140.3 | 146.1 | 135.55 ± 8.32 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.5 ± 1.8 | 150.9 | 158.7 | 145.97 ± 8.98 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.27 ± 0.10 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.6 | 1.36 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 2.1 | 1.26 ± 0.10 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 1.7 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 47.6 ± 0.7 | 46.6 | 50.3 | 45.31 ± 2.82 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.0 ± 0.6 | 39.9 | 42.8 | 39.01 ± 2.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
