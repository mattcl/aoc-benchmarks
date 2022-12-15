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
| `kcen/2022/12/solve input-kcen` | 131.2 ± 1.8 | 128.7 | 136.2 | 108.67 ± 6.64 |
| `kcen/2022/12/solve input-lanjian` | 127.0 ± 1.5 | 124.7 | 130.4 | 105.24 ± 6.40 |
| `kcen/2022/12/solve input-mattcl` | 154.1 ± 1.8 | 151.1 | 157.1 | 127.65 ± 7.76 |
| `kcen/2022/12/solve input-pting` | 142.9 ± 2.1 | 140.1 | 148.7 | 118.38 ± 7.27 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.2 | 1.1 | 4.7 | 1.07 ± 0.19 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 5.9 | 1.03 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.5 | 1.19 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.4 ± 0.1 | 1.2 | 5.0 | 1.12 ± 0.12 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 6.7 | 1.07 ± 0.14 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.1 | 1.19 ± 0.10 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 4.3 | 1.13 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 47.1 ± 1.2 | 45.5 | 51.9 | 38.98 ± 2.53 |
| `python pting/day12/day12.py input-lanjian` | 42.5 ± 0.7 | 41.2 | 44.4 | 35.23 ± 2.18 |
| `python pting/day12/day12.py input-mattcl` | 54.1 ± 0.6 | 53.2 | 56.4 | 44.86 ± 2.72 |
| `python pting/day12/day12.py input-pting` | 50.0 ± 1.0 | 48.7 | 53.2 | 41.46 ± 2.60 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.9 ± 1.9 | 139.9 | 148.1 | 128.29 ± 14.97 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.2 ± 1.6 | 149.7 | 155.5 | 136.69 ± 15.90 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.0 | 1.24 ± 0.17 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.2 | 1.29 ± 0.16 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.7 | 1.22 ± 0.17 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 3.9 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.8 ± 1.2 | 49.1 | 55.6 | 45.63 ± 5.40 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.5 ± 0.8 | 40.3 | 43.6 | 37.29 ± 4.37 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
