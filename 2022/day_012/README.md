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
| `kcen/2022/12/solve input-kcen` | 131.1 ± 1.9 | 128.5 | 135.2 | 107.26 ± 6.81 |
| `kcen/2022/12/solve input-lanjian` | 127.1 ± 0.9 | 125.4 | 128.9 | 104.03 ± 6.47 |
| `kcen/2022/12/solve input-mattcl` | 154.3 ± 1.3 | 151.9 | 156.6 | 126.29 ± 7.88 |
| `kcen/2022/12/solve input-pting` | 143.5 ± 1.1 | 141.7 | 147.2 | 117.45 ± 7.31 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.06 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.3 ± 0.1 | 1.1 | 3.0 | 1.04 ± 0.09 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.4 | 1.16 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.8 | 1.09 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.2 | 1.08 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.2 | 1.3 | 8.9 | 1.16 ± 0.18 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 2.0 | 1.11 ± 0.09 |
| `python pting/day12/day12.py input-kcen` | 46.6 ± 0.7 | 45.7 | 48.7 | 38.16 ± 2.43 |
| `python pting/day12/day12.py input-lanjian` | 43.0 ± 2.7 | 41.7 | 64.4 | 35.22 ± 3.10 |
| `python pting/day12/day12.py input-mattcl` | 54.2 ± 0.4 | 53.2 | 55.3 | 44.36 ± 2.76 |
| `python pting/day12/day12.py input-pting` | 50.5 ± 0.8 | 49.4 | 53.5 | 41.35 ± 2.63 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.2 ± 1.2 | 141.3 | 145.9 | 131.72 ± 17.92 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.4 ± 1.5 | 151.4 | 157.0 | 141.11 ± 19.21 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 6.2 | 1.24 ± 0.21 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.3 | 1.30 ± 0.20 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 5.9 | 1.24 ± 0.21 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 4.9 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 51.1 ± 1.3 | 49.7 | 57.1 | 46.98 ± 6.49 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.5 ± 0.7 | 40.6 | 46.2 | 38.21 ± 5.23 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
