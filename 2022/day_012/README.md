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
| `kcen/2022/12/solve input-kcen` | 130.4 ± 1.2 | 128.7 | 133.5 | 107.88 ± 6.47 |
| `kcen/2022/12/solve input-lanjian` | 127.1 ± 0.9 | 125.9 | 128.6 | 105.08 ± 6.26 |
| `kcen/2022/12/solve input-mattcl` | 153.4 ± 1.4 | 151.8 | 157.1 | 126.87 ± 7.60 |
| `kcen/2022/12/solve input-pting` | 143.1 ± 1.5 | 141.1 | 146.9 | 118.37 ± 7.11 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 4.2 | 1.06 ± 0.12 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 4.2 | 1.02 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.0 | 1.17 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 4.0 | 1.11 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.4 | 1.09 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.6 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.5 | 1.18 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.7 | 1.14 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 44.5 ± 1.0 | 43.0 | 47.8 | 36.79 ± 2.32 |
| `python pting/day12/day12.py input-lanjian` | 39.9 ± 0.7 | 38.6 | 43.0 | 33.03 ± 2.05 |
| `python pting/day12/day12.py input-mattcl` | 50.8 ± 1.0 | 49.4 | 53.2 | 42.00 ± 2.63 |
| `python pting/day12/day12.py input-pting` | 46.7 ± 0.7 | 45.7 | 48.8 | 38.62 ± 2.36 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.7 ± 1.9 | 140.2 | 148.6 | 131.31 ± 11.32 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.0 ± 1.3 | 150.3 | 156.6 | 139.91 ± 11.98 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 4.2 | 1.26 ± 0.15 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.3 | 1.31 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.9 | 1.25 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 3.5 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.0 ± 0.9 | 46.4 | 50.8 | 44.20 ± 3.85 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 40.8 ± 0.8 | 39.2 | 43.5 | 37.56 ± 3.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
