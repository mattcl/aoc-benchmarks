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
| `kcen/2022/12/solve input-kcen` | 132.6 ± 1.9 | 129.3 | 136.3 | 117.25 ± 6.32 |
| `kcen/2022/12/solve input-lanjian` | 128.8 ± 1.2 | 127.2 | 130.9 | 113.91 ± 5.99 |
| `kcen/2022/12/solve input-mattcl` | 157.3 ± 1.6 | 155.2 | 161.3 | 139.09 ± 7.35 |
| `kcen/2022/12/solve input-pting` | 145.5 ± 1.8 | 142.3 | 148.9 | 128.68 ± 6.85 |
| `lanjian/day_12 input-kcen` | 1.2 ± 0.1 | 1.1 | 3.0 | 1.10 ± 0.09 |
| `lanjian/day_12 input-lanjian` | 1.2 ± 0.1 | 1.1 | 1.8 | 1.06 ± 0.08 |
| `lanjian/day_12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.4 | 1.23 ± 0.09 |
| `lanjian/day_12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.0 | 1.16 ± 0.09 |
| `mattcl-solver/aoc run 12 input-kcen` | 1.2 ± 0.1 | 1.1 | 1.7 | 1.09 ± 0.08 |
| `mattcl-solver/aoc run 12 input-lanjian` | 1.1 ± 0.1 | 1.0 | 1.6 | 1.00 |
| `mattcl-solver/aoc run 12 input-mattcl` | 1.4 ± 0.1 | 1.3 | 1.8 | 1.21 ± 0.08 |
| `mattcl-solver/aoc run 12 input-pting` | 1.3 ± 0.1 | 1.2 | 2.3 | 1.15 ± 0.09 |
| `python pting/day12/day12.py input-kcen` | 44.1 ± 0.7 | 42.7 | 45.9 | 38.96 ± 2.10 |
| `python pting/day12/day12.py input-lanjian` | 40.3 ± 0.7 | 39.3 | 42.1 | 35.60 ± 1.94 |
| `python pting/day12/day12.py input-mattcl` | 50.8 ± 0.8 | 49.6 | 53.2 | 44.89 ± 2.42 |
| `python pting/day12/day12.py input-pting` | 47.2 ± 0.8 | 46.2 | 50.5 | 41.70 ± 2.27 |
## Benchmarks using unofficial challenge inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/12/solve challenge-input-degenerate` | 146.4 ± 1.6 | 144.1 | 150.2 | 138.09 ± 8.76 |
| `kcen/2022/12/solve challenge-input-edge-cases` | 155.2 ± 1.6 | 152.7 | 158.9 | 146.33 ± 9.27 |
| `lanjian/day_12 challenge-input-degenerate` | 1.4 ± 0.1 | 1.2 | 3.8 | 1.28 ± 0.12 |
| `lanjian/day_12 challenge-input-edge-cases` | 1.4 ± 0.1 | 1.3 | 4.1 | 1.35 ± 0.13 |
| `mattcl-solver/aoc run 12 challenge-input-degenerate` | 1.3 ± 0.1 | 1.2 | 4.2 | 1.25 ± 0.12 |
| `mattcl-solver/aoc run 12 challenge-input-edge-cases` | 1.1 ± 0.1 | 1.0 | 1.7 | 1.00 |
| `python pting/day12/day12.py challenge-input-degenerate` | 48.3 ± 0.7 | 46.9 | 50.5 | 45.53 ± 2.91 |
| `python pting/day12/day12.py challenge-input-edge-cases` | 41.1 ± 0.6 | 40.1 | 43.7 | 38.75 ± 2.49 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>456</pre>|<pre>454</pre>|
|input-mattcl|<pre>484</pre>|<pre>478</pre>|
|input-pting|<pre>481</pre>|<pre>480</pre>|
|challenge-input-edge-cases|<pre>516</pre>|<pre>295</pre>|
|input-kcen|<pre>423</pre>|<pre>416</pre>|
|challenge-input-degenerate|<pre>657</pre>|<pre>502</pre>|
