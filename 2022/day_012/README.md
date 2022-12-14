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
| `kcen/2022/12/solve input-kcen` | 132.0 ± 1.6 | 129.9 | 135.2 | 112.86 ± 6.61 |
| `kcen/2022/12/solve input-lanjian` | 129.2 ± 2.2 | 126.7 | 136.2 | 110.50 ± 6.60 |
| `kcen/2022/12/solve input-mattcl` | 157.7 ± 2.8 | 152.5 | 164.9 | 134.92 ± 8.09 |
| `kcen/2022/12/solve input-pting` | 144.9 ± 1.7 | 142.2 | 147.8 | 123.91 ± 7.25 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.10 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.05 ± 0.09 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.7 | 1.22 ± 0.13 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.13 ± 0.09 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 2.2 | 1.11 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.3 | 1.18 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.5 | 1.14 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 44.7 ± 1.1 | 43.2 | 47.6 | 38.23 ± 2.39 |
| `python pting/day12/day12.py input-lanjian` | 40.7 ± 0.5 | 39.7 | 42.8 | 34.78 ± 2.05 |
| `python pting/day12/day12.py input-mattcl` | 51.0 ± 0.9 | 49.8 | 54.0 | 43.61 ± 2.62 |
| `python pting/day12/day12.py input-pting` | 47.3 ± 0.9 | 46.3 | 52.4 | 40.43 ± 2.45 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 144.7 ± 1.4 | 141.8 | 147.0 | 138.25 ± 9.50 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 157.7 ± 3.5 | 153.8 | 165.0 | 150.67 ± 10.77 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.27 ± 0.11 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.35 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.9 | 1.25 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.0 ± 0.1 | 0.9 | 1.8 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.7 ± 1.0 | 47.4 | 51.6 | 46.56 ± 3.30 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.9 ± 1.0 | 40.5 | 47.0 | 40.07 ± 2.90 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
