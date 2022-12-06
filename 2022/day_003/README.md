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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 27.3 ± 5.5 | 12.9 | 46.9 | 13.78 ± 8.56 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.6 ± 3.5 | 14.7 | 48.3 | 12.92 ± 7.79 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 26.0 ± 3.6 | 23.4 | 39.8 | 13.13 ± 7.93 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.9 ± 2.1 | 23.7 | 39.8 | 13.08 ± 7.76 |
| `aspidites-solver/aoc -i input-pting -d 3` | 28.5 ± 6.8 | 23.4 | 65.3 | 14.36 ± 9.10 |
| `kcen/2022/03/solve input-aspidites` | 400.4 ± 33.8 | 348.4 | 457.9 | 202.01 ± 119.87 |
| `kcen/2022/03/solve input-kcen` | 386.7 ± 30.5 | 334.6 | 445.8 | 195.13 ± 115.64 |
| `kcen/2022/03/solve input-lanjian` | 407.3 ± 35.9 | 345.7 | 456.6 | 205.52 ± 122.06 |
| `kcen/2022/03/solve input-mattcl` | 438.8 ± 29.9 | 385.9 | 499.6 | 221.41 ± 130.92 |
| `kcen/2022/03/solve input-pting` | 488.8 ± 92.1 | 377.9 | 666.2 | 246.64 ± 152.13 |
| `lanjian/day_03 input-aspidites` | 2.9 ± 1.5 | 0.4 | 13.6 | 1.48 ± 1.16 |
| `lanjian/day_03 input-kcen` | 5.7 ± 5.4 | 0.7 | 41.9 | 2.88 ± 3.19 |
| `lanjian/day_03 input-lanjian` | 2.6 ± 1.3 | 0.5 | 9.2 | 1.29 ± 1.00 |
| `lanjian/day_03 input-mattcl` | 2.3 ± 1.6 | 0.3 | 18.3 | 1.14 ± 1.04 |
| `lanjian/day_03 input-pting` | 2.2 ± 1.3 | 0.4 | 10.1 | 1.09 ± 0.92 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.9 ± 1.5 | 0.7 | 16.1 | 1.46 ± 1.13 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.7 ± 1.8 | 1.0 | 33.4 | 1.38 ± 1.22 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.4 ± 1.2 | 0.4 | 7.5 | 1.21 ± 0.93 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.0 ± 1.2 | 0.5 | 11.4 | 1.00 |
| `mattcl-solver/aoc run 3 input-pting` | 2.4 ± 1.2 | 0.7 | 10.8 | 1.20 ± 0.92 |
| `python pting/day03.py input-aspidites` | 59.7 ± 12.8 | 45.1 | 111.0 | 30.15 ± 18.85 |
| `python pting/day03.py input-kcen` | 61.2 ± 6.0 | 47.1 | 71.5 | 30.86 ± 18.37 |
| `python pting/day03.py input-lanjian` | 69.8 ± 15.3 | 55.6 | 145.0 | 35.21 ± 22.08 |
| `python pting/day03.py input-mattcl` | 73.0 ± 24.9 | 48.8 | 166.6 | 36.81 ± 25.01 |
| `python pting/day03.py input-pting` | 68.0 ± 12.8 | 50.5 | 107.4 | 34.29 ± 21.14 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
