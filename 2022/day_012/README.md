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
| `kcen/2022/12/solve input-kcen` | 132.5 ± 1.9 | 129.7 | 137.1 | 114.97 ± 9.32 |
| `kcen/2022/12/solve input-lanjian` | 128.5 ± 1.7 | 126.3 | 133.1 | 111.45 ± 9.02 |
| `kcen/2022/12/solve input-mattcl` | 155.7 ± 3.2 | 152.0 | 162.8 | 135.04 ± 11.13 |
| `kcen/2022/12/solve input-pting` | 146.9 ± 3.6 | 142.6 | 159.6 | 127.41 ± 10.63 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 2.9 | 1.07 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.04 ± 0.11 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.2 | 2.1 | 1.21 ± 0.12 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.5 | 1.13 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.07 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 2.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.2 | 3.1 | 1.19 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.12 ± 0.12 |
| `python pting/day12/day12.py input-kcen` | 44.6 ± 1.4 | 42.4 | 49.0 | 38.66 ± 3.31 |
| `python pting/day12/day12.py input-lanjian` | 40.6 ± 0.8 | 39.4 | 44.1 | 35.19 ± 2.89 |
| `python pting/day12/day12.py input-mattcl` | 51.3 ± 1.2 | 49.5 | 54.7 | 44.48 ± 3.70 |
| `python pting/day12/day12.py input-pting` | 47.7 ± 1.3 | 46.0 | 52.1 | 41.35 ± 3.50 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 145.1 ± 1.9 | 142.6 | 148.2 | 136.41 ± 11.71 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 158.4 ± 3.5 | 154.0 | 165.9 | 148.96 ± 13.07 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 4.4 | 1.28 ± 0.15 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.3 | 1.36 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.24 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 3.2 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.8 ± 1.1 | 47.2 | 53.2 | 45.89 ± 4.04 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.6 ± 1.0 | 40.2 | 44.7 | 39.11 ± 3.46 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
