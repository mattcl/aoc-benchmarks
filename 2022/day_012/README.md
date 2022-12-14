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
| `kcen/2022/12/solve input-kcen` | 131.4 ± 1.5 | 129.1 | 134.6 | 110.29 ± 8.20 |
| `kcen/2022/12/solve input-lanjian` | 127.1 ± 1.5 | 125.2 | 132.3 | 106.65 ± 7.93 |
| `kcen/2022/12/solve input-mattcl` | 154.6 ± 2.0 | 151.5 | 158.4 | 129.69 ± 9.68 |
| `kcen/2022/12/solve input-pting` | 143.3 ± 1.3 | 140.9 | 146.7 | 120.23 ± 8.90 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.6 | 1.07 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.03 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.2 | 1.3 | 5.6 | 1.17 ± 0.16 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.9 | 1.11 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.4 | 1.09 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.1 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.7 | 1.15 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 4.2 | 1.13 ± 0.12 |
| `python pting/day12/day12.py input-kcen` | 44.3 ± 0.8 | 42.8 | 46.8 | 37.20 ± 2.82 |
| `python pting/day12/day12.py input-lanjian` | 40.3 ± 0.9 | 39.2 | 43.6 | 33.81 ± 2.59 |
| `python pting/day12/day12.py input-mattcl` | 50.9 ± 0.7 | 49.6 | 54.0 | 42.67 ± 3.19 |
| `python pting/day12/day12.py input-pting` | 46.6 ± 0.7 | 44.9 | 48.9 | 39.12 ± 2.93 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 144.3 ± 3.4 | 141.0 | 157.2 | 136.13 ± 9.54 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 154.1 ± 1.7 | 151.2 | 157.7 | 145.35 ± 9.71 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.26 ± 0.10 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.4 | 1.32 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.7 | 1.26 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 2.3 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.0 ± 0.6 | 47.4 | 50.1 | 45.30 ± 3.04 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 40.7 ± 0.4 | 40.2 | 42.1 | 38.44 ± 2.56 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
