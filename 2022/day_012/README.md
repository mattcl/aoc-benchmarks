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
| `kcen/2022/12/solve input-kcen` | 132.9 ± 1.7 | 129.9 | 135.9 | 115.00 ± 9.38 |
| `kcen/2022/12/solve input-lanjian` | 129.6 ± 1.6 | 127.2 | 132.7 | 112.11 ± 9.14 |
| `kcen/2022/12/solve input-mattcl` | 157.4 ± 2.3 | 154.6 | 163.6 | 136.16 ± 11.15 |
| `kcen/2022/12/solve input-pting` | 146.2 ± 1.5 | 143.4 | 148.8 | 126.47 ± 10.27 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.3 | 1.09 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.0 | 1.05 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.22 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.16 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.1 | 1.08 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.1 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.1 | 1.20 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.5 | 1.14 ± 0.12 |
| `python pting/day12/day12.py input-kcen` | 44.3 ± 1.0 | 43.2 | 49.5 | 38.35 ± 3.22 |
| `python pting/day12/day12.py input-lanjian` | 40.4 ± 0.7 | 39.3 | 42.6 | 34.98 ± 2.89 |
| `python pting/day12/day12.py input-mattcl` | 51.4 ± 1.2 | 49.6 | 55.3 | 44.49 ± 3.73 |
| `python pting/day12/day12.py input-pting` | 47.0 ± 0.5 | 45.8 | 48.8 | 40.70 ± 3.31 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate lanjian/day_12` | 1.4 ± 0.1 | 1.2 | 1.9 | 2.28 ± 0.28 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate python pting/day12/day12.py` | 48.7 ± 1.0 | 47.2 | 52.0 | 82.14 ± 9.20 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases lanjian/day_12` | 1.4 ± 0.1 | 1.3 | 2.1 | 2.39 ± 0.29 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases python pting/day12/day12.py` | 41.2 ± 0.7 | 40.1 | 43.5 | 69.59 ± 7.77 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate` | 146.5 ± 2.0 | 144.1 | 150.1 | 247.09 ± 27.45 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases` | 156.0 ± 1.9 | 153.4 | 159.4 | 263.22 ± 29.21 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 0.6 ± 0.1 | 0.5 | 2.3 | 1.00 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 0.6 ± 0.1 | 0.5 | 2.4 | 1.01 ± 0.17 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
