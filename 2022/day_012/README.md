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
| `kcen/2022/12/solve input-kcen` | 134.1 ± 1.1 | 132.0 | 136.1 | 114.66 ± 7.83 |
| `kcen/2022/12/solve input-lanjian` | 129.8 ± 1.5 | 127.3 | 133.4 | 111.03 ± 7.64 |
| `kcen/2022/12/solve input-mattcl` | 154.8 ± 1.6 | 152.7 | 158.4 | 132.43 ± 9.08 |
| `kcen/2022/12/solve input-pting` | 145.9 ± 2.1 | 143.6 | 152.6 | 124.82 ± 8.64 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.1 | 1.08 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.06 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.2 | 1.20 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.9 | 1.15 ± 0.12 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.06 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.4 | 1.18 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.14 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 44.3 ± 0.7 | 43.2 | 46.6 | 37.89 ± 2.64 |
| `python pting/day12/day12.py input-lanjian` | 41.0 ± 0.7 | 39.8 | 42.9 | 35.08 ± 2.45 |
| `python pting/day12/day12.py input-mattcl` | 51.0 ± 0.7 | 49.9 | 53.0 | 43.63 ± 3.02 |
| `python pting/day12/day12.py input-pting` | 47.3 ± 0.8 | 46.3 | 49.8 | 40.41 ± 2.83 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate python pting/day12/day12.py` | 48.7 ± 1.5 | 47.2 | 58.1 | 91.52 ± 11.79 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases python pting/day12/day12.py` | 41.4 ± 0.6 | 40.3 | 42.9 | 77.68 ± 9.79 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/{fnmae} lanjian/day_12` | 0.5 ± 0.1 | 0.5 | 1.6 | 1.00 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/{fnmae} lanjian/day_12` | 0.5 ± 0.1 | 0.5 | 2.1 | 1.02 ± 0.19 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate` | 145.3 ± 1.6 | 142.3 | 147.7 | 272.82 ± 34.32 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases` | 155.5 ± 2.7 | 151.7 | 163.7 | 292.11 ± 36.94 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 0.6 ± 0.1 | 0.5 | 1.1 | 1.13 ± 0.17 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 0.6 ± 0.1 | 0.5 | 1.8 | 1.16 ± 0.20 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
