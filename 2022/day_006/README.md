# Day 6 benchmarks

[link to problem](http://adventofcode.com/2022/day/6)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 6)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.2 ± 2.9 | 13.4 | 42.1 | 13.06 ± 8.69 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.6 ± 2.2 | 13.1 | 37.1 | 13.25 ± 8.75 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.7 ± 2.4 | 23.5 | 37.5 | 13.32 ± 8.82 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 21.0 ± 5.6 | 13.0 | 36.9 | 10.87 ± 7.70 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.8 ± 2.1 | 23.7 | 36.4 | 13.38 ± 8.83 |
| `kcen/2022/06/solve input-aspidites` | 177.6 ± 20.5 | 151.9 | 217.9 | 92.04 ± 61.25 |
| `kcen/2022/06/solve input-kcen` | 167.6 ± 15.7 | 145.3 | 202.2 | 86.86 ± 57.50 |
| `kcen/2022/06/solve input-lanjian` | 182.3 ± 24.7 | 149.1 | 232.1 | 94.51 ± 63.24 |
| `kcen/2022/06/solve input-mattcl` | 171.8 ± 13.5 | 152.6 | 205.7 | 89.05 ± 58.78 |
| `kcen/2022/06/solve input-pting` | 166.3 ± 10.8 | 152.1 | 188.0 | 86.21 ± 56.77 |
| `lanjian/day_06 input-aspidites` | 2.0 ± 0.8 | 0.5 | 5.7 | 1.02 ± 0.80 |
| `lanjian/day_06 input-kcen` | 2.1 ± 1.0 | 0.7 | 11.3 | 1.10 ± 0.90 |
| `lanjian/day_06 input-lanjian` | 2.1 ± 1.1 | 0.6 | 11.9 | 1.11 ± 0.92 |
| `lanjian/day_06 input-mattcl` | 2.2 ± 1.1 | 0.6 | 9.4 | 1.13 ± 0.94 |
| `lanjian/day_06 input-pting` | 3.1 ± 3.9 | 0.4 | 63.4 | 1.59 ± 2.26 |
| `mattcl-solver/aoc run 6 input-aspidites` | 1.9 ± 1.3 | 0.6 | 14.4 | 1.00 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.5 ± 1.2 | 0.8 | 12.5 | 1.28 ± 1.03 |
| `mattcl-solver/aoc run 6 input-lanjian` | 4.4 ± 4.5 | 0.8 | 50.2 | 2.30 ± 2.79 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.7 ± 1.2 | 0.9 | 10.8 | 1.42 ± 1.12 |
| `mattcl-solver/aoc run 6 input-pting` | 2.4 ± 1.2 | 0.8 | 14.3 | 1.23 ± 1.01 |
| `python pting/day06.py input-aspidites` | 54.5 ± 7.4 | 44.9 | 73.2 | 28.25 ± 18.91 |
| `python pting/day06.py input-kcen` | 65.1 ± 11.5 | 47.0 | 88.4 | 33.76 ± 22.92 |
| `python pting/day06.py input-lanjian` | 57.2 ± 11.7 | 41.9 | 94.8 | 29.63 ± 20.35 |
| `python pting/day06.py input-mattcl` | 59.3 ± 9.1 | 43.0 | 81.6 | 30.74 ± 20.69 |
| `python pting/day06.py input-pting` | 58.1 ± 10.7 | 44.4 | 99.2 | 30.13 ± 20.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
