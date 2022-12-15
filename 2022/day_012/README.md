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
| `kcen/2022/12/solve input-kcen` | 130.8 ± 0.9 | 129.4 | 132.4 | 111.04 ± 6.93 |
| `kcen/2022/12/solve input-lanjian` | 127.6 ± 1.1 | 125.7 | 129.6 | 108.32 ± 6.78 |
| `kcen/2022/12/solve input-mattcl` | 153.7 ± 1.4 | 151.6 | 155.8 | 130.49 ± 8.17 |
| `kcen/2022/12/solve input-pting` | 142.6 ± 1.2 | 141.1 | 145.6 | 121.11 ± 7.58 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.5 | 1.07 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.6 | 1.03 ± 0.08 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.19 ± 0.10 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.13 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.9 | 1.10 ± 0.12 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 3.1 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.20 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.14 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 46.8 ± 0.8 | 45.6 | 49.2 | 39.75 ± 2.55 |
| `python pting/day12/day12.py input-lanjian` | 42.3 ± 0.8 | 40.8 | 44.6 | 35.95 ± 2.32 |
| `python pting/day12/day12.py input-mattcl` | 54.2 ± 0.8 | 53.0 | 56.6 | 45.99 ± 2.93 |
| `python pting/day12/day12.py input-pting` | 49.9 ± 0.7 | 48.7 | 53.5 | 42.40 ± 2.70 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.3 ± 1.7 | 139.6 | 146.1 | 127.83 ± 10.48 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.5 ± 1.4 | 150.8 | 155.9 | 136.95 ± 11.17 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.8 | 1.24 ± 0.13 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 3.4 | 1.30 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.1 | 1.23 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 3.1 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.5 ± 0.9 | 49.3 | 53.2 | 45.39 ± 3.77 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.5 ± 0.5 | 40.3 | 42.9 | 37.25 ± 3.06 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
