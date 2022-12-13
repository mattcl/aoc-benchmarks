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
| `kcen/2022/12/solve input-kcen` | 134.1 ± 1.7 | 131.1 | 137.7 | 117.82 ± 11.06 |
| `kcen/2022/12/solve input-lanjian` | 131.1 ± 1.7 | 127.9 | 134.4 | 115.19 ± 10.82 |
| `kcen/2022/12/solve input-mattcl` | 156.0 ± 1.6 | 152.9 | 158.6 | 136.99 ± 12.82 |
| `kcen/2022/12/solve input-pting` | 146.7 ± 1.4 | 144.9 | 149.6 | 128.83 ± 12.05 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.1 | 1.11 ± 0.13 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.0 | 1.06 ± 0.12 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.25 ± 0.14 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.6 | 1.17 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 1.8 | 1.11 ± 0.12 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.1 ± 0.1 | 1.0 | 4.6 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.3 | 1.24 ± 0.14 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.6 | 1.17 ± 0.13 |
| `python pting/day12/day12.py input-kcen` | 44.5 ± 1.0 | 43.2 | 50.8 | 39.11 ± 3.75 |
| `python pting/day12/day12.py input-lanjian` | 40.3 ± 0.7 | 39.2 | 42.4 | 35.42 ± 3.36 |
| `python pting/day12/day12.py input-mattcl` | 51.1 ± 1.0 | 49.4 | 54.3 | 44.88 ± 4.27 |
| `python pting/day12/day12.py input-pting` | 48.0 ± 1.2 | 46.1 | 51.3 | 42.16 ± 4.06 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate python pting/day12/day12.py` | 48.3 ± 1.0 | 46.8 | 51.8 | 87.66 ± 11.25 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases python pting/day12/day12.py` | 41.1 ± 0.7 | 40.0 | 43.2 | 74.70 ± 9.53 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/{fnmae} lanjian/day_12` | 0.6 ± 0.1 | 0.4 | 2.4 | 1.00 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/{fnmae} lanjian/day_12` | 0.6 ± 0.1 | 0.5 | 1.0 | 1.03 ± 0.18 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate` | 147.2 ± 2.6 | 142.8 | 154.1 | 267.24 ± 34.15 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases` | 154.4 ± 1.5 | 152.7 | 158.5 | 280.41 ± 35.60 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 0.6 ± 0.1 | 0.5 | 2.4 | 1.14 ± 0.19 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 0.6 ± 0.1 | 0.5 | 4.5 | 1.15 ± 0.24 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
