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
| `kcen/2022/12/solve input-kcen` | 130.3 ± 2.6 | 127.6 | 140.9 | 109.44 ± 7.03 |
| `kcen/2022/12/solve input-lanjian` | 127.0 ± 1.1 | 125.5 | 129.2 | 106.65 ± 6.57 |
| `kcen/2022/12/solve input-mattcl` | 152.9 ± 1.3 | 150.7 | 156.0 | 128.46 ± 7.92 |
| `kcen/2022/12/solve input-pting` | 142.2 ± 1.1 | 140.6 | 144.3 | 119.45 ± 7.35 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 4.3 | 1.05 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.9 | 1.03 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.3 | 1.18 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.13 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 5.1 | 1.08 ± 0.12 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.3 | 1.19 ± 0.10 |
| `mattcl-solver/aoc run 12 input-pting` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.15 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 46.5 ± 0.7 | 45.5 | 48.9 | 39.09 ± 2.46 |
| `python pting/day12/day12.py input-lanjian` | 42.3 ± 0.8 | 41.3 | 45.9 | 35.52 ± 2.27 |
| `python pting/day12/day12.py input-mattcl` | 54.5 ± 1.2 | 53.0 | 58.7 | 45.76 ± 2.97 |
| `python pting/day12/day12.py input-pting` | 50.1 ± 0.7 | 49.2 | 52.8 | 42.07 ± 2.64 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.7 ± 1.2 | 140.3 | 145.2 | 133.37 ± 9.22 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.4 ± 1.5 | 150.9 | 156.5 | 143.33 ± 9.93 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.2 | 1.26 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.9 | 1.31 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.26 ± 0.11 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 2.9 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.7 ± 0.8 | 49.5 | 53.0 | 47.40 ± 3.33 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.4 ± 0.7 | 40.1 | 43.1 | 38.64 ± 2.73 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
