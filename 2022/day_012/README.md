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
| `kcen/2022/12/solve input-kcen` | 130.5 ± 1.6 | 128.1 | 134.3 | 109.33 ± 7.63 |
| `kcen/2022/12/solve input-lanjian` | 125.8 ± 1.3 | 123.9 | 129.3 | 105.38 ± 7.33 |
| `kcen/2022/12/solve input-mattcl` | 152.2 ± 2.3 | 149.4 | 159.8 | 127.50 ± 8.98 |
| `kcen/2022/12/solve input-pting` | 142.8 ± 0.9 | 140.6 | 144.0 | 119.61 ± 8.27 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 2.9 | 1.02 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.1 | 1.01 ± 0.11 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.7 | 1.17 ± 0.12 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.09 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.1 | 1.06 ± 0.09 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 3.1 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.2 | 1.3 | 6.0 | 1.18 ± 0.17 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.11 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 46.3 ± 0.7 | 45.3 | 48.3 | 38.80 ± 2.74 |
| `python pting/day12/day12.py input-lanjian` | 42.4 ± 0.6 | 41.3 | 44.5 | 35.49 ± 2.50 |
| `python pting/day12/day12.py input-mattcl` | 54.0 ± 0.9 | 52.8 | 56.8 | 45.24 ± 3.21 |
| `python pting/day12/day12.py input-pting` | 49.8 ± 0.8 | 48.7 | 52.0 | 41.72 ± 2.96 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 141.7 ± 1.3 | 139.7 | 144.3 | 133.27 ± 8.37 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.8 ± 1.5 | 151.1 | 158.2 | 143.77 ± 9.05 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 2.8 | 1.25 ± 0.11 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.2 | 1.9 | 1.31 ± 0.10 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 4.6 | 1.27 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 1.5 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.1 ± 0.8 | 49.0 | 52.5 | 47.13 ± 3.01 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.5 ± 0.7 | 39.8 | 44.1 | 39.00 ± 2.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
