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
| `kcen/2022/12/solve input-kcen` | 131.1 ± 1.0 | 129.6 | 133.7 | 109.80 ± 14.15 |
| `kcen/2022/12/solve input-lanjian` | 127.8 ± 1.4 | 125.9 | 132.9 | 107.07 ± 13.82 |
| `kcen/2022/12/solve input-mattcl` | 153.7 ± 2.2 | 151.9 | 159.2 | 128.75 ± 16.66 |
| `kcen/2022/12/solve input-pting` | 144.4 ± 1.7 | 142.4 | 148.7 | 120.99 ± 15.62 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 1.8 | 1.03 ± 0.14 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 5.6 | 1.02 ± 0.17 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.15 ± 0.16 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.6 | 1.09 ± 0.16 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 2.2 | 1.07 ± 0.15 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.2 | 1.1 | 6.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.8 | 1.17 ± 0.18 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.8 | 1.12 ± 0.17 |
| `python pting/day12/day12.py input-kcen` | 46.5 ± 0.7 | 45.6 | 50.8 | 38.97 ± 5.05 |
| `python pting/day12/day12.py input-lanjian` | 42.8 ± 0.8 | 41.8 | 47.0 | 35.88 ± 4.67 |
| `python pting/day12/day12.py input-mattcl` | 54.2 ± 0.9 | 52.7 | 58.5 | 45.39 ± 5.89 |
| `python pting/day12/day12.py input-pting` | 50.2 ± 0.8 | 49.3 | 54.4 | 42.09 ± 5.46 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.4 ± 1.5 | 141.3 | 145.5 | 136.56 ± 9.16 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 154.0 ± 1.9 | 151.4 | 159.2 | 146.73 ± 9.89 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.2 | 1.26 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.5 | 1.32 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 2.7 | 1.27 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.0 ± 0.1 | 1.0 | 2.4 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.3 ± 0.7 | 49.5 | 52.3 | 47.86 ± 3.23 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.8 ± 1.3 | 40.5 | 48.6 | 39.79 ± 2.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
