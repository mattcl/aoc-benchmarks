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
| `kcen/2022/12/solve input-kcen` | 130.2 ± 1.4 | 128.6 | 134.8 | 105.65 ± 7.28 |
| `kcen/2022/12/solve input-lanjian` | 126.5 ± 1.1 | 124.9 | 128.5 | 102.61 ± 7.03 |
| `kcen/2022/12/solve input-mattcl` | 153.8 ± 2.2 | 150.8 | 158.6 | 124.82 ± 8.67 |
| `kcen/2022/12/solve input-pting` | 142.1 ± 1.3 | 140.2 | 144.8 | 115.32 ± 7.92 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.0 | 1.04 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.3 ± 0.1 | 1.1 | 5.3 | 1.03 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.3 | 1.16 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.4 ± 0.1 | 1.2 | 6.1 | 1.11 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 2.7 | 1.06 ± 0.09 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.4 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.0 | 1.17 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 5.8 | 1.12 ± 0.13 |
| `python pting/day12/day12.py input-kcen` | 46.4 ± 0.7 | 45.5 | 48.9 | 37.62 ± 2.62 |
| `python pting/day12/day12.py input-lanjian` | 42.4 ± 0.9 | 41.2 | 47.4 | 34.38 ± 2.46 |
| `python pting/day12/day12.py input-mattcl` | 54.2 ± 1.6 | 52.3 | 59.0 | 43.95 ± 3.27 |
| `python pting/day12/day12.py input-pting` | 50.0 ± 1.2 | 48.6 | 54.5 | 40.54 ± 2.92 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.2 ± 0.9 | 140.9 | 144.0 | 130.84 ± 8.33 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 151.8 ± 1.6 | 149.3 | 154.3 | 139.65 ± 8.96 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.5 | 1.26 ± 0.13 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.5 | 1.32 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.4 | 1.23 ± 0.11 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 2.1 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.2 ± 0.9 | 48.9 | 52.9 | 46.19 ± 3.04 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.0 ± 0.6 | 40.1 | 43.2 | 37.73 ± 2.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
