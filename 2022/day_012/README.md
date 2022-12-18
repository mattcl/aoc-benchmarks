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
| `kcen/2022/12/solve input-kcen` | 130.7 ± 1.1 | 128.4 | 132.8 | 108.18 ± 7.54 |
| `kcen/2022/12/solve input-lanjian` | 126.5 ± 1.0 | 124.9 | 129.2 | 104.67 ± 7.30 |
| `kcen/2022/12/solve input-mattcl` | 155.9 ± 2.9 | 151.6 | 162.9 | 129.06 ± 9.24 |
| `kcen/2022/12/solve input-pting` | 143.2 ± 1.4 | 141.0 | 146.1 | 118.53 ± 8.28 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.9 | 1.04 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.6 | 1.01 ± 0.09 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.8 | 1.17 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.11 ± 0.12 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.2 | 1.09 ± 0.13 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.18 ± 0.10 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.1 | 1.13 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 46.6 ± 0.8 | 45.2 | 48.8 | 38.59 ± 2.75 |
| `python pting/day12/day12.py input-lanjian` | 42.3 ± 0.6 | 41.3 | 44.5 | 35.01 ± 2.47 |
| `python pting/day12/day12.py input-mattcl` | 54.1 ± 0.9 | 52.9 | 56.9 | 44.81 ± 3.18 |
| `python pting/day12/day12.py input-pting` | 50.5 ± 1.0 | 49.2 | 54.8 | 41.81 ± 3.01 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.5 ± 1.6 | 140.0 | 147.5 | 128.65 ± 8.24 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.0 ± 1.6 | 150.5 | 156.0 | 138.12 ± 8.82 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 4.4 | 1.23 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.30 ± 0.10 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 2.5 | 1.24 ± 0.11 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 1.7 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.4 ± 0.9 | 49.2 | 53.2 | 45.52 ± 2.99 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.6 ± 0.8 | 40.7 | 44.5 | 37.54 ± 2.47 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
