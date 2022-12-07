# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 3)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 26.5 ± 1.9 | 24.0 | 39.5 | 13.20 ± 6.29 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 43.5 ± 31.2 | 24.3 | 134.2 | 21.68 ± 18.61 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 21.6 ± 5.5 | 12.8 | 34.0 | 10.79 ± 5.78 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 21.4 ± 5.4 | 12.8 | 28.0 | 10.68 ± 5.70 |
| `aspidites-solver/aoc -i input-pting -d 3` | 24.7 ± 4.5 | 12.9 | 41.0 | 12.34 ± 6.23 |
| `kcen/2022/03/solve input-aspidites` | 379.4 ± 24.3 | 350.6 | 411.8 | 189.20 ± 89.95 |
| `kcen/2022/03/solve input-kcen` | 426.2 ± 112.3 | 312.3 | 666.6 | 212.53 ± 114.72 |
| `kcen/2022/03/solve input-lanjian` | 357.1 ± 20.7 | 331.2 | 400.5 | 178.08 ± 84.52 |
| `kcen/2022/03/solve input-mattcl` | 375.4 ± 53.1 | 299.0 | 465.6 | 187.20 ± 92.09 |
| `kcen/2022/03/solve input-pting` | 354.6 ± 39.9 | 324.3 | 462.8 | 176.81 ± 85.64 |
| `lanjian/day_03 input-aspidites` | 2.0 ± 0.9 | 0.5 | 6.6 | 1.00 |
| `lanjian/day_03 input-kcen` | 2.8 ± 1.6 | 0.5 | 10.3 | 1.39 ± 1.04 |
| `lanjian/day_03 input-lanjian` | 2.3 ± 2.0 | 0.6 | 35.2 | 1.17 ± 1.12 |
| `lanjian/day_03 input-mattcl` | 3.3 ± 3.4 | 0.8 | 35.1 | 1.67 ± 1.89 |
| `lanjian/day_03 input-pting` | 3.0 ± 1.4 | 0.9 | 18.2 | 1.51 ± 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.8 ± 1.8 | 0.8 | 27.2 | 1.39 ± 1.12 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.6 ± 1.3 | 0.8 | 9.2 | 1.29 ± 0.87 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.3 ± 1.6 | 0.9 | 22.9 | 1.67 ± 1.12 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.6 ± 1.1 | 0.8 | 10.3 | 1.32 ± 0.83 |
| `mattcl-solver/aoc run 3 input-pting` | 3.3 ± 1.3 | 1.0 | 11.2 | 1.64 ± 1.00 |
| `python pting/day03.py input-aspidites` | 54.5 ± 7.3 | 45.0 | 84.4 | 27.18 ± 13.31 |
| `python pting/day03.py input-kcen` | 58.9 ± 8.2 | 45.2 | 77.6 | 29.35 ± 14.42 |
| `python pting/day03.py input-lanjian` | 54.3 ± 7.5 | 41.7 | 75.0 | 27.06 ± 13.29 |
| `python pting/day03.py input-mattcl` | 84.3 ± 37.0 | 47.9 | 187.5 | 42.06 ± 27.08 |
| `python pting/day03.py input-pting` | 56.3 ± 9.7 | 42.8 | 90.5 | 28.09 ± 14.09 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
