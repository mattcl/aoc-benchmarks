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
| `kcen/2022/12/solve input-kcen` | 132.3 ± 1.8 | 129.2 | 136.2 | 110.41 ± 7.61 |
| `kcen/2022/12/solve input-lanjian` | 129.2 ± 2.0 | 126.0 | 133.2 | 107.77 ± 7.46 |
| `kcen/2022/12/solve input-mattcl` | 154.1 ± 2.0 | 150.5 | 158.4 | 128.58 ± 8.85 |
| `kcen/2022/12/solve input-pting` | 144.7 ± 1.4 | 142.5 | 148.0 | 120.77 ± 8.24 |
| `lanjian/day_12 input-kcen` | 1.3 ± 0.1 | 1.1 | 2.9 | 1.06 ± 0.10 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.04 ± 0.10 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.5 | 1.19 ± 0.11 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 3.8 | 1.12 ± 0.11 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.3 ± 0.1 | 1.2 | 3.0 | 1.08 ± 0.10 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 4.3 | 1.16 ± 0.12 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.0 | 1.11 ± 0.10 |
| `python pting/day12/day12.py input-kcen` | 44.1 ± 0.8 | 42.8 | 46.4 | 36.79 ± 2.57 |
| `python pting/day12/day12.py input-lanjian` | 40.4 ± 0.8 | 39.4 | 44.0 | 33.73 ± 2.38 |
| `python pting/day12/day12.py input-mattcl` | 50.9 ± 1.0 | 49.2 | 53.8 | 42.43 ± 2.98 |
| `python pting/day12/day12.py input-pting` | 46.8 ± 1.0 | 45.6 | 49.8 | 39.07 ± 2.77 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 144.6 ± 2.1 | 141.6 | 149.3 | 136.48 ± 11.95 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 153.6 ± 1.6 | 151.0 | 156.0 | 144.91 ± 12.61 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 2.0 | 1.28 ± 0.13 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.33 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.25 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 0.9 | 3.8 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.1 ± 0.9 | 46.8 | 50.6 | 45.40 ± 4.02 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 40.9 ± 0.8 | 39.6 | 43.9 | 38.60 ± 3.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
