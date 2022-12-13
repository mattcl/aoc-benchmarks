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
| `kcen/2022/12/solve input-kcen` | 132.1 ± 1.3 | 130.1 | 134.5 | 114.32 ± 8.06 |
| `kcen/2022/12/solve input-lanjian` | 129.8 ± 2.3 | 127.2 | 136.5 | 112.35 ± 8.11 |
| `kcen/2022/12/solve input-mattcl` | 156.6 ± 4.5 | 151.8 | 171.1 | 135.58 ± 10.25 |
| `kcen/2022/12/solve input-pting` | 144.6 ± 1.8 | 142.2 | 148.3 | 125.13 ± 8.87 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.08 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.07 ± 0.11 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 3.6 | 1.22 ± 0.12 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.7 | 1.16 ± 0.13 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.9 | 1.09 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 2.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.2 | 2.1 | 1.20 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.14 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 44.7 ± 1.3 | 43.0 | 50.5 | 38.66 ± 2.92 |
| `python pting/day12/day12.py input-lanjian` | 40.5 ± 0.9 | 39.4 | 44.5 | 35.10 ± 2.57 |
| `python pting/day12/day12.py input-mattcl` | 51.5 ± 1.1 | 50.0 | 56.4 | 44.56 ± 3.26 |
| `python pting/day12/day12.py input-pting` | 47.4 ± 1.0 | 46.0 | 50.9 | 41.06 ± 3.00 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 143.9 ± 1.1 | 141.7 | 146.2 | 135.05 ± 9.91 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 155.1 ± 1.9 | 152.3 | 158.8 | 145.57 ± 10.77 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 2.7 | 1.27 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 4.3 | 1.34 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 2.0 | 1.25 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 1.6 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.7 ± 0.8 | 47.4 | 50.4 | 45.67 ± 3.41 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.3 ± 0.8 | 40.3 | 44.9 | 38.74 ± 2.92 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
