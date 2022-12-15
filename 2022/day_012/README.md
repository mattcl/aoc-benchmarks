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
| `kcen/2022/12/solve input-kcen` | 129.8 ± 1.6 | 127.6 | 133.7 | 108.90 ± 7.58 |
| `kcen/2022/12/solve input-lanjian` | 127.4 ± 1.0 | 125.8 | 129.7 | 106.91 ± 7.36 |
| `kcen/2022/12/solve input-mattcl` | 154.6 ± 1.5 | 152.0 | 156.8 | 129.69 ± 8.97 |
| `kcen/2022/12/solve input-pting` | 142.8 ± 1.3 | 141.4 | 147.5 | 119.77 ± 8.27 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 5.5 | 1.06 ± 0.14 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.1 | 1.03 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.8 | 1.17 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.1 | 1.11 ± 0.09 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 1.7 | 1.08 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.3 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.7 | 1.20 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.2 | 1.14 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 46.6 ± 0.9 | 45.5 | 50.4 | 39.12 ± 2.79 |
| `python pting/day12/day12.py input-lanjian` | 42.2 ± 0.8 | 41.4 | 45.2 | 35.44 ± 2.51 |
| `python pting/day12/day12.py input-mattcl` | 54.8 ± 1.0 | 53.5 | 60.4 | 45.94 ± 3.25 |
| `python pting/day12/day12.py input-pting` | 50.1 ± 0.9 | 49.0 | 53.1 | 42.07 ± 2.98 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.4 ± 1.0 | 140.9 | 144.5 | 130.80 ± 36.72 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.6 ± 1.2 | 150.7 | 154.8 | 140.19 ± 39.36 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.22 ± 0.35 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 1.8 | 1.29 ± 0.37 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.8 | 1.22 ± 0.35 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.3 | 1.0 | 6.6 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.7 ± 0.9 | 49.3 | 53.7 | 46.59 ± 13.10 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.5 ± 0.5 | 40.7 | 42.9 | 38.12 ± 10.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
