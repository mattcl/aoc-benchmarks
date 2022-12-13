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
| `kcen/2022/12/solve input-kcen` | 134.6 ± 4.6 | 129.8 | 149.6 | 116.65 ± 11.39 |
| `kcen/2022/12/solve input-lanjian` | 131.6 ± 2.4 | 129.0 | 139.6 | 114.07 ± 10.64 |
| `kcen/2022/12/solve input-mattcl` | 157.1 ± 2.1 | 154.0 | 161.3 | 136.16 ± 12.58 |
| `kcen/2022/12/solve input-pting` | 148.6 ± 6.1 | 143.6 | 163.5 | 128.81 ± 12.90 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.1 | 1.09 ± 0.13 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.05 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.23 ± 0.14 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.8 | 1.16 ± 0.14 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 4.0 | 1.10 ± 0.14 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 3.4 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.2 | 3.4 | 1.19 ± 0.14 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.15 ± 0.15 |
| `python pting/day12/day12.py input-kcen` | 45.0 ± 1.7 | 43.1 | 51.6 | 39.01 ± 3.85 |
| `python pting/day12/day12.py input-lanjian` | 40.5 ± 0.7 | 39.2 | 43.7 | 35.06 ± 3.27 |
| `python pting/day12/day12.py input-mattcl` | 52.1 ± 1.2 | 50.1 | 55.6 | 45.12 ± 4.25 |
| `python pting/day12/day12.py input-pting` | 48.0 ± 2.0 | 46.2 | 54.8 | 41.59 ± 4.16 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 145.6 ± 1.6 | 142.9 | 148.7 | 138.91 ± 10.30 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 157.4 ± 3.4 | 153.9 | 166.2 | 150.12 ± 11.49 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.1 | 1.31 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.5 ± 0.1 | 1.3 | 3.7 | 1.39 ± 0.16 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.27 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.0 ± 0.1 | 0.9 | 2.7 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 49.3 ± 0.8 | 48.3 | 51.6 | 47.05 ± 3.54 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 42.0 ± 1.4 | 40.3 | 47.3 | 40.08 ± 3.21 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
