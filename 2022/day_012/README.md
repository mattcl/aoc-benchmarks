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
| `kcen/2022/12/solve input-kcen` | 132.3 ± 1.3 | 130.7 | 135.2 | 113.72 ± 8.68 |
| `kcen/2022/12/solve input-lanjian` | 128.0 ± 1.3 | 125.8 | 132.4 | 109.99 ± 8.39 |
| `kcen/2022/12/solve input-mattcl` | 156.0 ± 1.7 | 153.9 | 160.7 | 134.01 ± 10.24 |
| `kcen/2022/12/solve input-pting` | 145.1 ± 1.4 | 142.0 | 147.6 | 124.72 ± 9.52 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.4 | 1.10 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 4.6 | 1.07 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.23 ± 0.13 |
| `lanjian/day_12 input-pting` | 1.4 ± 0.1 | 1.2 | 2.2 | 1.16 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 1.7 | 1.09 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 2.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.1 | 1.19 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.13 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 44.3 ± 0.9 | 42.9 | 47.6 | 38.09 ± 2.98 |
| `python pting/day12/day12.py input-lanjian` | 40.4 ± 0.7 | 39.3 | 42.6 | 34.70 ± 2.70 |
| `python pting/day12/day12.py input-mattcl` | 50.9 ± 0.9 | 49.6 | 53.6 | 43.78 ± 3.39 |
| `python pting/day12/day12.py input-pting` | 47.2 ± 1.2 | 45.7 | 52.8 | 40.54 ± 3.23 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate python pting/day12/day12.py` | 48.3 ± 0.9 | 46.8 | 51.5 | 112.22 ± 17.17 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases python pting/day12/day12.py` | 40.9 ± 0.7 | 39.6 | 43.6 | 95.17 ± 14.55 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/{fnmae} lanjian/day_12` | 0.4 ± 0.1 | 0.3 | 1.5 | 1.00 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/{fnmae} lanjian/day_12` | 0.4 ± 0.1 | 0.3 | 2.6 | 1.02 ± 0.24 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate` | 145.8 ± 1.9 | 144.0 | 152.8 | 338.84 ± 51.64 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases` | 155.9 ± 2.0 | 152.4 | 159.6 | 362.35 ± 55.20 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 0.5 ± 0.1 | 0.4 | 1.2 | 1.14 ± 0.23 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 0.5 ± 0.1 | 0.4 | 2.7 | 1.18 ± 0.25 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
