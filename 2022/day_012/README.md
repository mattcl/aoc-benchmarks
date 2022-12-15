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
| `kcen/2022/12/solve input-kcen` | 130.2 ± 1.3 | 128.0 | 132.3 | 109.15 ± 7.70 |
| `kcen/2022/12/solve input-lanjian` | 127.7 ± 1.7 | 125.6 | 133.6 | 107.01 ± 7.61 |
| `kcen/2022/12/solve input-mattcl` | 154.7 ± 2.2 | 152.0 | 159.0 | 129.68 ± 9.25 |
| `kcen/2022/12/solve input-pting` | 142.4 ± 1.0 | 141.1 | 144.6 | 119.41 ± 8.39 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.5 | 1.06 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.03 ± 0.09 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.18 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.4 ± 0.5 | 1.2 | 20.2 | 1.14 ± 0.40 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 4.7 | 1.09 ± 0.13 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.18 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.2 | 1.14 ± 0.12 |
| `python pting/day12/day12.py input-kcen` | 46.6 ± 0.8 | 45.3 | 49.2 | 39.08 ± 2.82 |
| `python pting/day12/day12.py input-lanjian` | 42.4 ± 0.9 | 41.0 | 45.4 | 35.51 ± 2.59 |
| `python pting/day12/day12.py input-mattcl` | 53.8 ± 0.6 | 52.8 | 55.9 | 45.10 ± 3.19 |
| `python pting/day12/day12.py input-pting` | 49.8 ± 0.9 | 48.5 | 52.9 | 41.76 ± 3.01 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.3 ± 1.4 | 140.4 | 145.0 | 127.62 ± 21.79 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.2 ± 1.2 | 150.4 | 154.3 | 136.50 ± 23.29 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.21 ± 0.22 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.6 | 1.27 ± 0.23 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.21 ± 0.22 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.2 | 1.0 | 5.3 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.3 ± 0.9 | 49.1 | 53.7 | 45.07 ± 7.72 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.3 ± 0.8 | 40.1 | 44.4 | 37.01 ± 6.35 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
