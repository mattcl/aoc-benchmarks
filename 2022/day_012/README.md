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
| `kcen/2022/12/solve input-kcen` | 130.6 ± 1.5 | 128.3 | 134.1 | 106.20 ± 5.61 |
| `kcen/2022/12/solve input-lanjian` | 127.0 ± 1.3 | 125.3 | 130.7 | 103.26 ± 5.43 |
| `kcen/2022/12/solve input-mattcl` | 153.4 ± 2.3 | 150.0 | 158.1 | 124.78 ± 6.69 |
| `kcen/2022/12/solve input-pting` | 144.2 ± 2.1 | 141.0 | 149.5 | 117.29 ± 6.27 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.1 | 1.03 ± 0.08 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.00 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.16 ± 0.08 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.5 | 1.09 ± 0.08 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.07 ± 0.08 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.2 | 1.1 | 7.2 | 1.00 ± 0.15 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.5 ± 0.1 | 1.3 | 5.5 | 1.18 ± 0.13 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 1.8 | 1.12 ± 0.08 |
| `python pting/day12/day12.py input-kcen` | 46.4 ± 0.9 | 45.0 | 49.1 | 37.74 ± 2.08 |
| `python pting/day12/day12.py input-lanjian` | 42.5 ± 0.7 | 41.5 | 44.7 | 34.53 ± 1.86 |
| `python pting/day12/day12.py input-mattcl` | 54.1 ± 0.7 | 53.1 | 56.7 | 44.01 ± 2.35 |
| `python pting/day12/day12.py input-pting` | 50.0 ± 0.7 | 48.7 | 52.9 | 40.65 ± 2.18 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 141.7 ± 1.3 | 139.8 | 145.3 | 128.89 ± 15.06 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.8 ± 1.6 | 150.0 | 155.6 | 138.92 ± 16.26 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 4.8 | 1.24 ± 0.18 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.2 | 1.3 | 6.8 | 1.31 ± 0.23 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 4.3 | 1.25 ± 0.19 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 5.9 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.5 ± 0.9 | 49.6 | 54.7 | 45.94 ± 5.41 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.9 ± 1.0 | 40.6 | 48.6 | 38.06 ± 4.53 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
