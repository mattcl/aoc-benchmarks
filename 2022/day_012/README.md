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
| `kcen/2022/12/solve input-kcen` | 131.5 ± 1.0 | 129.9 | 133.6 | 111.16 ± 6.13 |
| `kcen/2022/12/solve input-lanjian` | 127.9 ± 3.3 | 126.2 | 142.7 | 108.10 ± 6.53 |
| `kcen/2022/12/solve input-mattcl` | 153.1 ± 2.4 | 151.0 | 161.2 | 129.41 ± 7.35 |
| `kcen/2022/12/solve input-pting` | 144.1 ± 1.6 | 141.2 | 148.6 | 121.75 ± 6.78 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 1.6 | 1.05 ± 0.08 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.5 | 1.02 ± 0.08 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 6.0 | 1.20 ± 0.13 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.13 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.10 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.19 ± 0.09 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 4.4 | 1.13 ± 0.13 |
| `python pting/day12/day12.py input-kcen` | 46.7 ± 0.7 | 45.8 | 49.6 | 39.49 ± 2.24 |
| `python pting/day12/day12.py input-lanjian` | 42.9 ± 1.2 | 41.9 | 51.1 | 36.26 ± 2.23 |
| `python pting/day12/day12.py input-mattcl` | 53.9 ± 0.7 | 52.6 | 56.9 | 45.53 ± 2.57 |
| `python pting/day12/day12.py input-pting` | 50.3 ± 0.6 | 49.5 | 52.5 | 42.51 ± 2.38 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 142.1 ± 1.1 | 140.4 | 144.2 | 129.87 ± 7.83 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 152.5 ± 1.8 | 149.9 | 156.7 | 139.40 ± 8.49 |
| `lanjian/day_12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 5.7 | 1.23 ± 0.13 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 5.3 | 1.31 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.4 ± 0.2 | 1.2 | 4.7 | 1.24 ± 0.16 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 1.5 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 50.3 ± 0.7 | 48.8 | 52.2 | 45.93 ± 2.83 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 42.0 ± 1.6 | 40.3 | 51.2 | 38.38 ± 2.74 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
