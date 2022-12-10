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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.2 ± 2.9 | 23.6 | 39.1 | 12.16 ± 4.78 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.4 ± 1.8 | 13.5 | 34.7 | 11.80 ± 4.54 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.6 ± 2.7 | 23.3 | 45.1 | 11.87 ± 4.66 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 25.2 ± 2.6 | 13.6 | 35.1 | 11.68 ± 4.57 |
| `aspidites-solver/aoc -i input-pting -d 6` | 37.2 ± 18.9 | 22.6 | 123.1 | 17.26 ± 10.95 |
| `kcen/2022/06/solve input-aspidites` | 194.8 ± 24.0 | 163.7 | 243.0 | 90.50 ± 35.97 |
| `kcen/2022/06/solve input-kcen` | 186.8 ± 23.3 | 156.2 | 239.0 | 86.76 ± 34.54 |
| `kcen/2022/06/solve input-lanjian` | 190.8 ± 23.7 | 150.0 | 227.5 | 88.63 ± 35.26 |
| `kcen/2022/06/solve input-mattcl` | 196.9 ± 24.3 | 162.9 | 244.7 | 91.45 ± 36.37 |
| `kcen/2022/06/solve input-pting` | 197.6 ± 20.0 | 162.1 | 221.3 | 91.79 ± 35.92 |
| `lanjian/day_06 input-aspidites` | 2.7 ± 1.1 | 1.1 | 12.1 | 1.27 ± 0.70 |
| `lanjian/day_06 input-kcen` | 2.2 ± 0.8 | 0.6 | 6.6 | 1.00 |
| `lanjian/day_06 input-lanjian` | 2.6 ± 1.6 | 0.7 | 31.6 | 1.22 ± 0.86 |
| `lanjian/day_06 input-mattcl` | 2.4 ± 0.8 | 1.0 | 8.8 | 1.10 ± 0.56 |
| `lanjian/day_06 input-pting` | 2.3 ± 1.0 | 0.7 | 11.7 | 1.05 ± 0.61 |
| `mattcl-solver/aoc run 6 input-aspidites` | 3.0 ± 1.1 | 0.9 | 11.6 | 1.38 ± 0.72 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.8 ± 1.2 | 1.2 | 11.5 | 1.31 ± 0.74 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.8 ± 1.3 | 0.9 | 25.8 | 1.30 ± 0.78 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.4 ± 0.9 | 0.9 | 8.7 | 1.11 ± 0.58 |
| `mattcl-solver/aoc run 6 input-pting` | 2.6 ± 0.8 | 1.1 | 5.9 | 1.23 ± 0.59 |
| `python pting/day06.py input-aspidites` | 56.6 ± 9.1 | 43.7 | 73.2 | 26.27 ± 10.78 |
| `python pting/day06.py input-kcen` | 55.3 ± 8.9 | 44.2 | 95.0 | 25.70 ± 10.56 |
| `python pting/day06.py input-lanjian` | 54.9 ± 7.0 | 44.1 | 71.8 | 25.50 ± 10.17 |
| `python pting/day06.py input-mattcl` | 59.6 ± 7.7 | 46.5 | 77.8 | 27.66 ± 11.05 |
| `python pting/day06.py input-pting` | 63.5 ± 9.1 | 49.9 | 81.0 | 29.50 ± 11.92 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
