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
| `kcen/2022/12/solve input-kcen` | 130.1 ± 0.8 | 129.0 | 132.0 | 108.73 ± 5.72 |
| `kcen/2022/12/solve input-lanjian` | 127.7 ± 2.2 | 125.4 | 134.2 | 106.69 ± 5.87 |
| `kcen/2022/12/solve input-mattcl` | 153.2 ± 1.3 | 150.9 | 155.8 | 127.97 ± 6.77 |
| `kcen/2022/12/solve input-pting` | 142.6 ± 1.3 | 140.4 | 146.0 | 119.11 ± 6.32 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 1.6 | 1.04 ± 0.08 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.8 | 1.02 ± 0.08 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.8 | 1.18 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 4.1 | 1.10 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 1.7 | 1.08 ± 0.08 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 5.0 | 1.20 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.2 | 1.2 | 6.1 | 1.14 ± 0.16 |
| `python pting/day12/day12.py input-kcen` | 46.3 ± 1.4 | 44.9 | 54.8 | 38.69 ± 2.33 |
| `python pting/day12/day12.py input-lanjian` | 42.2 ± 0.7 | 41.1 | 45.5 | 35.26 ± 1.94 |
| `python pting/day12/day12.py input-mattcl` | 54.0 ± 1.0 | 52.4 | 57.3 | 45.15 ± 2.50 |
| `python pting/day12/day12.py input-pting` | 49.9 ± 1.0 | 48.4 | 53.6 | 41.70 ± 2.34 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.2 ± 1.1 | 140.6 | 144.2 | 127.00 ± 7.27 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.0 ± 1.4 | 149.2 | 155.2 | 135.71 ± 7.81 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 1.7 | 1.21 ± 0.09 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.4 | 1.29 ± 0.11 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.2 | 1.23 ± 0.10 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 1.7 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.4 ± 0.8 | 49.1 | 52.8 | 44.99 ± 2.65 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.2 ± 0.7 | 39.9 | 44.1 | 36.76 ± 2.18 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
