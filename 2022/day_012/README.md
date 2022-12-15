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
| `kcen/2022/12/solve input-kcen` | 130.3 ± 1.4 | 128.6 | 135.6 | 108.17 ± 9.31 |
| `kcen/2022/12/solve input-lanjian` | 126.0 ± 0.9 | 124.7 | 127.9 | 104.64 ± 8.97 |
| `kcen/2022/12/solve input-mattcl` | 152.8 ± 1.6 | 151.1 | 157.0 | 126.85 ± 10.92 |
| `kcen/2022/12/solve input-pting` | 142.2 ± 1.1 | 140.6 | 144.5 | 118.09 ± 10.13 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.3 | 1.06 ± 0.12 |
| `lanjian/day_12 input-lanjian` | 1.3 ± 0.1 | 1.1 | 3.5 | 1.04 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.18 ± 0.12 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.12 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.08 ± 0.12 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.6 | 1.18 ± 0.13 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.12 ± 0.12 |
| `python pting/day12/day12.py input-kcen` | 46.6 ± 0.6 | 45.6 | 48.5 | 38.70 ± 3.34 |
| `python pting/day12/day12.py input-lanjian` | 42.6 ± 1.1 | 41.5 | 49.1 | 35.35 ± 3.16 |
| `python pting/day12/day12.py input-mattcl` | 54.4 ± 1.2 | 53.0 | 58.9 | 45.19 ± 3.98 |
| `python pting/day12/day12.py input-pting` | 50.0 ± 0.7 | 49.1 | 52.3 | 41.51 ± 3.59 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.4 ± 1.8 | 141.3 | 149.3 | 130.96 ± 9.81 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.5 ± 1.3 | 150.4 | 155.1 | 139.26 ± 10.35 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.24 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.31 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.23 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 2.9 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.4 ± 0.9 | 49.1 | 53.4 | 46.04 ± 3.50 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.9 ± 0.8 | 40.5 | 44.0 | 38.30 ± 2.93 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
