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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.7 ± 4.5 | 12.7 | 49.3 | 12.30 ± 6.24 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 27.3 ± 5.2 | 13.4 | 52.3 | 13.11 ± 6.72 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.8 ± 4.3 | 23.4 | 50.1 | 12.35 ± 6.23 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 25.0 ± 6.3 | 13.2 | 46.8 | 12.01 ± 6.47 |
| `aspidites-solver/aoc -i input-pting -d 6` | 27.3 ± 5.3 | 23.0 | 49.5 | 13.10 ± 6.73 |
| `kcen/2022/06/solve input-aspidites` | 175.5 ± 23.9 | 147.9 | 236.8 | 84.16 ± 41.64 |
| `kcen/2022/06/solve input-kcen` | 343.4 ± 130.4 | 166.0 | 591.9 | 164.64 ± 100.21 |
| `kcen/2022/06/solve input-lanjian` | 169.6 ± 22.9 | 146.2 | 221.7 | 81.31 ± 40.20 |
| `kcen/2022/06/solve input-mattcl` | 184.3 ± 26.5 | 155.5 | 236.0 | 88.35 ± 43.91 |
| `kcen/2022/06/solve input-pting` | 187.5 ± 38.0 | 148.1 | 273.0 | 89.92 ± 46.49 |
| `lanjian/day_06 input-aspidites` | 2.7 ± 1.7 | 0.7 | 15.0 | 1.30 ± 1.01 |
| `lanjian/day_06 input-kcen` | 2.3 ± 1.1 | 0.5 | 8.0 | 1.11 ± 0.76 |
| `lanjian/day_06 input-lanjian` | 2.1 ± 1.0 | 0.3 | 7.1 | 1.00 |
| `lanjian/day_06 input-mattcl` | 8.0 ± 8.8 | 0.6 | 64.9 | 3.86 ± 4.61 |
| `lanjian/day_06 input-pting` | 2.3 ± 1.5 | 0.6 | 12.9 | 1.10 ± 0.89 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.7 ± 1.5 | 0.7 | 16.5 | 1.30 ± 0.96 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.6 ± 1.5 | 0.7 | 11.0 | 1.26 ± 0.94 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.2 ± 1.1 | 0.5 | 11.8 | 1.05 ± 0.72 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.5 ± 2.4 | 0.5 | 29.6 | 1.19 ± 1.30 |
| `mattcl-solver/aoc run 6 input-pting` | 2.8 ± 1.2 | 0.9 | 13.4 | 1.35 ± 0.88 |
| `python pting/day06.py input-aspidites` | 51.9 ± 13.2 | 42.9 | 130.6 | 24.88 ± 13.41 |
| `python pting/day06.py input-kcen` | 60.0 ± 19.7 | 41.5 | 167.0 | 28.76 ± 16.63 |
| `python pting/day06.py input-lanjian` | 52.6 ± 15.2 | 37.7 | 146.9 | 25.22 ± 14.04 |
| `python pting/day06.py input-mattcl` | 60.7 ± 21.7 | 43.6 | 179.7 | 29.10 ± 17.32 |
| `python pting/day06.py input-pting` | 59.1 ± 16.4 | 45.1 | 129.6 | 28.32 ± 15.60 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
