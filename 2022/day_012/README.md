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
| `kcen/2022/12/solve input-kcen` | 130.5 ± 1.4 | 128.6 | 134.1 | 106.78 ± 6.34 |
| `kcen/2022/12/solve input-lanjian` | 126.3 ± 1.4 | 124.6 | 130.7 | 103.36 ± 6.14 |
| `kcen/2022/12/solve input-mattcl` | 152.6 ± 1.4 | 150.1 | 156.2 | 124.86 ± 7.39 |
| `kcen/2022/12/solve input-pting` | 142.3 ± 2.3 | 139.8 | 150.8 | 116.42 ± 7.05 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 1.7 | 1.03 ± 0.08 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.6 | 1.01 ± 0.08 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.2 | 1.3 | 7.0 | 1.17 ± 0.15 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.09 ± 0.08 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.2 | 1.2 | 6.8 | 1.07 ± 0.15 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.1 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.9 | 1.18 ± 0.09 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.9 | 1.12 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 46.5 ± 0.8 | 45.0 | 48.5 | 38.05 ± 2.32 |
| `python pting/day12/day12.py input-lanjian` | 42.1 ± 1.3 | 40.9 | 50.0 | 34.48 ± 2.26 |
| `python pting/day12/day12.py input-mattcl` | 54.0 ± 1.4 | 52.7 | 60.5 | 44.22 ± 2.82 |
| `python pting/day12/day12.py input-pting` | 50.0 ± 0.8 | 48.8 | 52.5 | 40.90 ± 2.48 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.5 ± 1.7 | 140.4 | 145.9 | 129.06 ± 10.26 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.5 ± 2.2 | 150.1 | 160.0 | 138.07 ± 11.03 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 1.8 | 1.23 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 4.7 | 1.31 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.5 | 1.25 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 3.5 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.1 ± 0.9 | 49.0 | 52.4 | 45.39 ± 3.65 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.5 ± 0.7 | 40.3 | 44.3 | 37.54 ± 3.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
