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
| `kcen/2022/12/solve input-kcen` | 131.9 ± 1.2 | 129.6 | 134.5 | 115.85 ± 6.65 |
| `kcen/2022/12/solve input-lanjian` | 130.1 ± 1.9 | 127.4 | 135.4 | 114.25 ± 6.68 |
| `kcen/2022/12/solve input-mattcl` | 155.4 ± 1.4 | 152.8 | 158.7 | 136.47 ± 7.84 |
| `kcen/2022/12/solve input-pting` | 145.2 ± 1.3 | 142.9 | 148.2 | 127.56 ± 7.33 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.2 | 1.09 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.2 | 1.06 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.4 | 1.23 ± 0.09 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.16 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.2 ± 0.1 | 1.1 | 4.7 | 1.09 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.1 ± 0.1 | 1.0 | 1.7 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.21 ± 0.09 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.7 | 1.15 ± 0.09 |
| `python pting/day12/day12.py input-kcen` | 44.2 ± 0.7 | 43.2 | 46.3 | 38.86 ± 2.30 |
| `python pting/day12/day12.py input-lanjian` | 40.8 ± 0.7 | 39.7 | 43.3 | 35.82 ± 2.13 |
| `python pting/day12/day12.py input-mattcl` | 51.4 ± 1.0 | 50.0 | 53.9 | 45.17 ± 2.70 |
| `python pting/day12/day12.py input-pting` | 47.1 ± 0.7 | 46.1 | 49.7 | 41.35 ± 2.43 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate lanjian/day_12` | 1.4 ± 0.1 | 1.3 | 3.4 | 2.27 ± 0.29 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate python pting/day12/day12.py` | 48.6 ± 0.8 | 47.3 | 50.7 | 79.75 ± 8.89 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases lanjian/day_12` | 1.4 ± 0.1 | 1.3 | 3.4 | 2.35 ± 0.30 |
| `AOC_INPUT=/tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases python pting/day12/day12.py` | 41.2 ± 0.5 | 40.2 | 42.7 | 67.66 ± 7.49 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-degenerate` | 144.7 ± 1.1 | 142.8 | 146.7 | 237.57 ± 26.23 |
| `kcen/2022/12/solve /tmp/build/a1bedd04/aoc-inputs-write/2022/day_012/challenge-input-edge-cases` | 154.0 ± 1.4 | 151.5 | 156.0 | 252.93 ± 27.95 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 0.6 ± 0.1 | 0.5 | 2.5 | 1.00 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 0.6 ± 0.1 | 0.5 | 1.2 | 1.01 ± 0.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
