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
| `kcen/2022/12/solve input-kcen` | 131.2 ± 1.1 | 129.4 | 132.9 | 109.13 ± 7.83 |
| `kcen/2022/12/solve input-lanjian` | 128.5 ± 1.2 | 127.0 | 131.2 | 106.90 ± 7.68 |
| `kcen/2022/12/solve input-mattcl` | 153.2 ± 2.0 | 150.5 | 158.3 | 127.46 ± 9.24 |
| `kcen/2022/12/solve input-pting` | 143.6 ± 1.3 | 142.1 | 147.5 | 119.49 ± 8.58 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.1 | 1.06 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.0 | 1.03 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.19 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.5 | 1.12 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.09 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.4 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.2 | 1.20 ± 0.13 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.6 | 1.12 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 47.2 ± 1.1 | 45.9 | 52.2 | 39.30 ± 2.96 |
| `python pting/day12/day12.py input-lanjian` | 42.9 ± 0.8 | 41.8 | 47.5 | 35.67 ± 2.63 |
| `python pting/day12/day12.py input-mattcl` | 54.6 ± 1.2 | 53.3 | 58.8 | 45.42 ± 3.38 |
| `python pting/day12/day12.py input-pting` | 51.5 ± 1.9 | 49.5 | 58.3 | 42.84 ± 3.43 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.3 ± 1.5 | 140.9 | 146.4 | 127.30 ± 12.64 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.5 ± 1.3 | 150.9 | 156.6 | 135.49 ± 13.43 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.8 | 1.23 ± 0.15 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.5 ± 0.1 | 1.3 | 4.9 | 1.29 ± 0.17 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 5.1 | 1.24 ± 0.17 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 4.9 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.6 ± 0.7 | 49.4 | 52.5 | 44.92 ± 4.48 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.9 ± 0.8 | 40.5 | 45.4 | 37.19 ± 3.74 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
