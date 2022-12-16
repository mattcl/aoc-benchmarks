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
| `kcen/2022/12/solve input-kcen` | 129.9 ± 0.7 | 128.3 | 131.1 | 107.60 ± 6.43 |
| `kcen/2022/12/solve input-lanjian` | 127.1 ± 1.5 | 124.9 | 131.7 | 105.28 ± 6.39 |
| `kcen/2022/12/solve input-mattcl` | 153.4 ± 1.7 | 151.1 | 158.9 | 127.07 ± 7.69 |
| `kcen/2022/12/solve input-pting` | 143.0 ± 1.3 | 141.4 | 147.9 | 118.44 ± 7.13 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.4 | 1.05 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.02 ± 0.08 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.2 | 1.3 | 5.7 | 1.18 ± 0.14 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 4.6 | 1.11 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 4.3 | 1.10 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.4 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.19 ± 0.09 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 2.0 | 1.14 ± 0.09 |
| `python pting/day12/day12.py input-kcen` | 46.7 ± 0.8 | 45.6 | 49.6 | 38.66 ± 2.40 |
| `python pting/day12/day12.py input-lanjian` | 42.3 ± 1.0 | 41.3 | 48.6 | 35.07 ± 2.25 |
| `python pting/day12/day12.py input-mattcl` | 54.1 ± 1.0 | 52.6 | 58.1 | 44.81 ± 2.80 |
| `python pting/day12/day12.py input-pting` | 51.0 ± 1.6 | 49.4 | 56.6 | 42.21 ± 2.85 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 141.7 ± 1.1 | 140.1 | 144.3 | 129.44 ± 7.72 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.3 ± 1.4 | 150.9 | 155.9 | 140.05 ± 8.37 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.23 ± 0.11 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 4.4 | 1.30 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.25 ± 0.11 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 1.6 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.4 ± 0.8 | 49.1 | 53.2 | 46.03 ± 2.82 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.2 ± 0.6 | 40.3 | 42.9 | 37.66 ± 2.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
