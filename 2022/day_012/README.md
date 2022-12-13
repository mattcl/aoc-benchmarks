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
| `kcen/2022/12/solve input-kcen` | 132.8 ± 2.3 | 129.2 | 136.7 | 110.34 ± 9.34 |
| `kcen/2022/12/solve input-lanjian` | 128.7 ± 4.2 | 125.7 | 143.4 | 106.93 ± 9.54 |
| `kcen/2022/12/solve input-mattcl` | 155.3 ± 3.4 | 151.5 | 164.7 | 129.02 ± 11.06 |
| `kcen/2022/12/solve input-pting` | 144.7 ± 2.0 | 141.3 | 149.8 | 120.23 ± 10.11 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.1 | 1.04 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.9 | 1.04 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.1 | 1.17 ± 0.12 |
| `lanjian/day_12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.5 | 1.12 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.3 | 1.04 ± 0.12 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.2 | 3.0 | 1.15 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.10 ± 0.12 |
| `python pting/day12/day12.py input-kcen` | 44.5 ± 1.1 | 43.0 | 47.6 | 36.96 ± 3.20 |
| `python pting/day12/day12.py input-lanjian` | 40.6 ± 1.1 | 39.1 | 44.0 | 33.70 ± 2.94 |
| `python pting/day12/day12.py input-mattcl` | 50.8 ± 0.8 | 49.7 | 53.0 | 42.18 ± 3.56 |
| `python pting/day12/day12.py input-pting` | 47.3 ± 1.2 | 45.8 | 50.5 | 39.32 ± 3.40 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 144.6 ± 2.8 | 140.7 | 151.2 | 134.96 ± 11.03 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 156.0 ± 2.9 | 152.0 | 161.5 | 145.55 ± 11.89 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 4.3 | 1.25 ± 0.14 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.2 | 1.33 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 2.3 | 1.24 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 3.3 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.7 ± 1.3 | 47.1 | 51.5 | 45.41 ± 3.81 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.3 ± 0.7 | 40.0 | 43.5 | 38.53 ± 3.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
