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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 25.8 ± 3.3 | 13.7 | 38.4 | 12.67 ± 12.31 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 24.9 ± 4.8 | 13.0 | 46.7 | 12.24 ± 12.03 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 25.8 ± 2.6 | 13.5 | 36.8 | 12.70 ± 12.29 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 27.3 ± 3.8 | 13.9 | 42.3 | 13.42 ± 13.05 |
| `aspidites-solver/aoc -i input-pting -d 3` | 25.4 ± 4.2 | 12.5 | 42.3 | 12.49 ± 12.20 |
| `kcen/2022/03/solve input-aspidites` | 411.4 ± 44.8 | 338.5 | 493.3 | 202.35 ± 196.04 |
| `kcen/2022/03/solve input-kcen` | 367.3 ± 19.7 | 333.4 | 391.9 | 180.69 ± 174.21 |
| `kcen/2022/03/solve input-lanjian` | 402.1 ± 43.1 | 337.4 | 471.3 | 197.80 ± 191.59 |
| `kcen/2022/03/solve input-mattcl` | 440.9 ± 39.2 | 393.9 | 520.0 | 216.86 ± 209.65 |
| `kcen/2022/03/solve input-pting` | 416.2 ± 35.4 | 354.1 | 471.2 | 204.72 ± 197.84 |
| `lanjian/day_03 input-aspidites` | 2.7 ± 1.4 | 0.3 | 12.4 | 1.34 ± 1.47 |
| `lanjian/day_03 input-kcen` | 2.3 ± 1.5 | 0.2 | 17.2 | 1.13 ± 1.31 |
| `lanjian/day_03 input-lanjian` | 2.6 ± 1.8 | 0.4 | 17.4 | 1.28 ± 1.52 |
| `lanjian/day_03 input-mattcl` | 2.7 ± 2.2 | 0.5 | 45.6 | 1.35 ± 1.69 |
| `lanjian/day_03 input-pting` | 2.6 ± 1.7 | 0.4 | 12.4 | 1.27 ± 1.47 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.3 ± 1.6 | 0.8 | 22.9 | 1.61 ± 1.74 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.0 ± 2.0 | 0.3 | 37.6 | 1.00 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.5 ± 1.4 | 0.6 | 11.4 | 1.73 ± 1.80 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.1 ± 1.4 | 0.8 | 8.3 | 1.52 ± 1.62 |
| `mattcl-solver/aoc run 3 input-pting` | 3.5 ± 2.1 | 0.9 | 22.9 | 1.70 ± 1.93 |
| `python pting/day03.py input-aspidites` | 55.2 ± 8.9 | 39.2 | 84.6 | 27.15 ± 26.50 |
| `python pting/day03.py input-kcen` | 54.5 ± 6.6 | 43.7 | 65.7 | 26.81 ± 26.01 |
| `python pting/day03.py input-lanjian` | 59.3 ± 12.3 | 43.6 | 92.6 | 29.16 ± 28.71 |
| `python pting/day03.py input-mattcl` | 52.8 ± 7.4 | 40.4 | 73.3 | 25.99 ± 25.28 |
| `python pting/day03.py input-pting` | 59.8 ± 13.0 | 42.5 | 105.8 | 29.41 ± 29.03 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
