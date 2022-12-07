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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 28.9 ± 5.3 | 24.8 | 55.2 | 9.10 ± 4.03 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 27.9 ± 3.8 | 24.7 | 50.5 | 8.79 ± 3.75 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 28.4 ± 5.5 | 24.3 | 58.8 | 8.94 ± 4.00 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 26.9 ± 2.5 | 14.7 | 40.0 | 8.46 ± 3.51 |
| `aspidites-solver/aoc -i input-pting -d 6` | 31.1 ± 7.5 | 24.3 | 78.1 | 9.78 ± 4.60 |
| `kcen/2022/06/solve input-aspidites` | 218.7 ± 25.1 | 175.9 | 267.9 | 68.82 ± 28.90 |
| `kcen/2022/06/solve input-kcen` | 230.5 ± 21.0 | 190.6 | 274.0 | 72.55 ± 30.04 |
| `kcen/2022/06/solve input-lanjian` | 208.5 ± 34.7 | 166.9 | 273.3 | 65.62 ± 28.67 |
| `kcen/2022/06/solve input-mattcl` | 224.6 ± 37.6 | 180.6 | 298.0 | 70.67 ± 30.90 |
| `kcen/2022/06/solve input-pting` | 236.3 ± 37.4 | 171.1 | 308.1 | 74.34 ± 32.26 |
| `lanjian/day_06 input-aspidites` | 3.2 ± 1.3 | 0.7 | 13.2 | 1.00 |
| `lanjian/day_06 input-kcen` | 4.3 ± 2.0 | 1.5 | 20.1 | 1.37 ± 0.83 |
| `lanjian/day_06 input-lanjian` | 9.3 ± 10.6 | 1.8 | 75.6 | 2.92 ± 3.53 |
| `lanjian/day_06 input-mattcl` | 3.3 ± 1.6 | 0.8 | 17.8 | 1.05 ± 0.65 |
| `lanjian/day_06 input-pting` | 3.8 ± 1.8 | 1.3 | 17.9 | 1.21 ± 0.76 |
| `mattcl-solver/aoc run 6 input-aspidites` | 4.2 ± 2.4 | 1.1 | 26.2 | 1.32 ± 0.93 |
| `mattcl-solver/aoc run 6 input-kcen` | 4.0 ± 1.7 | 1.2 | 19.7 | 1.24 ± 0.74 |
| `mattcl-solver/aoc run 6 input-lanjian` | 5.2 ± 7.1 | 1.0 | 89.6 | 1.64 ± 2.32 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.4 ± 1.4 | 1.0 | 15.3 | 1.07 ± 0.61 |
| `mattcl-solver/aoc run 6 input-pting` | 3.6 ± 1.8 | 1.3 | 21.0 | 1.14 ± 0.72 |
| `python pting/day06.py input-aspidites` | 68.7 ± 14.5 | 53.4 | 124.3 | 21.63 ± 9.86 |
| `python pting/day06.py input-kcen` | 76.8 ± 12.8 | 56.1 | 108.1 | 24.17 ± 10.56 |
| `python pting/day06.py input-lanjian` | 72.3 ± 11.9 | 53.9 | 99.2 | 22.75 ± 9.92 |
| `python pting/day06.py input-mattcl` | 69.6 ± 10.1 | 52.1 | 96.7 | 21.90 ± 9.40 |
| `python pting/day06.py input-pting` | 76.8 ± 14.9 | 53.7 | 137.2 | 24.17 ± 10.83 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
