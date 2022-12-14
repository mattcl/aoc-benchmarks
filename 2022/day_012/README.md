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
| `kcen/2022/12/solve input-kcen` | 131.1 ± 1.3 | 128.5 | 133.6 | 111.25 ± 7.99 |
| `kcen/2022/12/solve input-lanjian` | 128.2 ± 1.3 | 126.2 | 132.4 | 108.80 ± 7.83 |
| `kcen/2022/12/solve input-mattcl` | 155.2 ± 1.7 | 152.1 | 157.6 | 131.68 ± 9.49 |
| `kcen/2022/12/solve input-pting` | 145.5 ± 1.7 | 141.9 | 148.5 | 123.46 ± 8.91 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.9 | 1.08 ± 0.11 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 2.9 | 1.05 ± 0.11 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.2 | 1.22 ± 0.13 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.14 ± 0.12 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.1 | 3.0 | 1.09 ± 0.11 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.0 | 2.9 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.18 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.2 | 1.13 ± 0.11 |
| `python pting/day12/day12.py input-kcen` | 44.1 ± 0.8 | 42.8 | 46.5 | 37.40 ± 2.74 |
| `python pting/day12/day12.py input-lanjian` | 40.4 ± 0.7 | 39.1 | 42.7 | 34.27 ± 2.51 |
| `python pting/day12/day12.py input-mattcl` | 52.3 ± 1.6 | 50.7 | 60.9 | 44.41 ± 3.45 |
| `python pting/day12/day12.py input-pting` | 47.8 ± 1.4 | 46.1 | 52.5 | 40.52 ± 3.12 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 146.6 ± 4.8 | 140.9 | 159.2 | 140.15 ± 9.92 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 154.2 ± 2.2 | 151.2 | 160.7 | 147.42 ± 9.47 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 2.9 | 1.30 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 2.3 | 1.36 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 3.6 | 1.25 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.0 ± 0.1 | 0.9 | 1.5 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 49.4 ± 1.3 | 47.6 | 54.0 | 47.25 ± 3.20 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 40.9 ± 0.5 | 40.1 | 42.9 | 39.14 ± 2.50 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
