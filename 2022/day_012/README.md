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
| `kcen/2022/12/solve input-kcen` | 130.9 ± 1.0 | 128.8 | 133.0 | 107.88 ± 7.91 |
| `kcen/2022/12/solve input-lanjian` | 128.5 ± 1.1 | 127.0 | 131.3 | 105.94 ± 7.77 |
| `kcen/2022/12/solve input-mattcl` | 153.1 ± 2.1 | 150.8 | 157.4 | 126.21 ± 9.36 |
| `kcen/2022/12/solve input-pting` | 143.9 ± 1.1 | 142.5 | 146.2 | 118.64 ± 8.69 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.2 | 1.07 ± 0.12 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.2 | 1.03 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.7 | 1.19 ± 0.12 |
| `lanjian/day_12 input-pting` | 1.4 ± 0.1 | 1.2 | 1.9 | 1.12 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 1.7 | 1.08 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.8 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.4 | 1.18 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.14 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 46.9 ± 0.9 | 45.5 | 49.9 | 38.68 ± 2.91 |
| `python pting/day12/day12.py input-lanjian` | 42.9 ± 0.6 | 41.8 | 44.8 | 35.36 ± 2.62 |
| `python pting/day12/day12.py input-mattcl` | 54.3 ± 0.9 | 53.0 | 56.9 | 44.79 ± 3.35 |
| `python pting/day12/day12.py input-pting` | 50.7 ± 1.1 | 49.4 | 54.1 | 41.82 ± 3.18 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.0 ± 0.8 | 141.2 | 144.5 | 125.54 ± 10.89 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.1 ± 1.3 | 150.7 | 155.8 | 134.39 ± 11.69 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.3 | 3.0 | 1.22 ± 0.13 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.5 ± 0.1 | 1.3 | 3.4 | 1.31 ± 0.15 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.2 | 1.22 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 3.4 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.4 ± 0.7 | 49.3 | 52.5 | 44.22 ± 3.88 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.8 ± 0.8 | 40.7 | 44.4 | 36.72 ± 3.25 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
