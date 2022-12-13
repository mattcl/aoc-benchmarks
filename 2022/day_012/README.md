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
| `kcen/2022/12/solve input-kcen` | 133.4 ± 3.3 | 130.5 | 143.3 | 111.41 ± 9.07 |
| `kcen/2022/12/solve input-lanjian` | 130.7 ± 4.2 | 125.8 | 139.3 | 109.23 ± 9.14 |
| `kcen/2022/12/solve input-mattcl` | 155.0 ± 2.0 | 152.3 | 158.3 | 129.50 ± 10.16 |
| `kcen/2022/12/solve input-pting` | 144.2 ± 1.4 | 142.8 | 147.7 | 120.45 ± 9.40 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.08 ± 0.12 |
| `lanjian/day_12 input-lanjian` | 1.3 ± 0.1 | 1.1 | 3.1 | 1.05 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.5 ± 0.1 | 1.3 | 2.1 | 1.22 ± 0.12 |
| `lanjian/day_12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.0 | 1.15 ± 0.12 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 1.9 | 1.09 ± 0.12 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.5 | 1.17 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 4.0 | 1.12 ± 0.12 |
| `python pting/day12/day12.py input-kcen` | 45.4 ± 2.2 | 43.4 | 53.2 | 37.90 ± 3.46 |
| `python pting/day12/day12.py input-lanjian` | 40.8 ± 1.6 | 39.3 | 46.4 | 34.07 ± 2.94 |
| `python pting/day12/day12.py input-mattcl` | 51.9 ± 2.4 | 49.9 | 60.7 | 43.36 ± 3.91 |
| `python pting/day12/day12.py input-pting` | 47.1 ± 0.8 | 46.1 | 49.6 | 39.39 ± 3.11 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 144.3 ± 2.2 | 140.5 | 148.0 | 135.70 ± 12.35 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 159.3 ± 8.0 | 152.0 | 175.5 | 149.80 ± 15.41 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.9 | 1.29 ± 0.15 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.35 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.6 | 1.25 ± 0.15 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 4.0 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.8 ± 1.7 | 47.1 | 56.4 | 45.92 ± 4.41 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.2 ± 0.6 | 40.3 | 43.0 | 38.80 ± 3.53 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
