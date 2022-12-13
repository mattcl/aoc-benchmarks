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
| `kcen/2022/12/solve input-kcen` | 132.0 ± 1.3 | 130.3 | 135.1 | 115.36 ± 7.36 |
| `kcen/2022/12/solve input-lanjian` | 129.6 ± 1.6 | 127.8 | 133.5 | 113.23 ± 7.27 |
| `kcen/2022/12/solve input-mattcl` | 155.9 ± 2.4 | 152.4 | 160.6 | 136.23 ± 8.84 |
| `kcen/2022/12/solve input-pting` | 145.0 ± 1.9 | 141.3 | 149.1 | 126.70 ± 8.15 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.4 | 1.10 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.1 | 1.05 ± 0.11 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.0 | 1.21 ± 0.12 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.1 | 1.16 ± 0.10 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.6 | 1.12 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.1 ± 0.1 | 1.0 | 1.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.2 | 3.8 | 1.18 ± 0.11 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.13 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 44.7 ± 1.1 | 43.2 | 48.5 | 39.07 ± 2.65 |
| `python pting/day12/day12.py input-lanjian` | 40.4 ± 0.6 | 39.3 | 42.3 | 35.27 ± 2.29 |
| `python pting/day12/day12.py input-mattcl` | 51.1 ± 0.7 | 50.0 | 53.1 | 44.63 ± 2.89 |
| `python pting/day12/day12.py input-pting` | 47.3 ± 1.2 | 46.1 | 53.8 | 41.36 ± 2.80 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 146.5 ± 4.2 | 142.7 | 161.4 | 138.65 ± 12.63 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 158.6 ± 6.8 | 152.2 | 179.3 | 150.11 ± 14.48 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 2.0 | 1.29 ± 0.14 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.1 | 1.36 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.2 | 1.25 ± 0.14 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 3.9 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 49.3 ± 2.0 | 47.1 | 55.7 | 46.63 ± 4.47 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 42.1 ± 1.5 | 40.4 | 49.2 | 39.81 ± 3.74 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
