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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 24.7 ± 3.3 | 12.9 | 36.2 | 11.77 ± 7.61 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 21.9 ± 5.1 | 12.9 | 30.8 | 10.46 ± 7.05 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 24.8 ± 2.0 | 12.8 | 28.2 | 11.81 ± 7.53 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 21.2 ± 5.5 | 13.1 | 29.0 | 10.11 ± 6.92 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.1 ± 1.8 | 23.4 | 36.0 | 11.99 ± 7.63 |
| `kcen/2022/06/solve input-aspidites` | 171.5 ± 12.0 | 143.7 | 195.9 | 81.75 ± 52.06 |
| `kcen/2022/06/solve input-kcen` | 167.4 ± 17.4 | 141.7 | 199.9 | 79.81 ± 51.19 |
| `kcen/2022/06/solve input-lanjian` | 169.5 ± 18.7 | 137.8 | 198.7 | 80.83 ± 51.93 |
| `kcen/2022/06/solve input-mattcl` | 170.7 ± 15.1 | 144.9 | 201.1 | 81.39 ± 52.02 |
| `kcen/2022/06/solve input-pting` | 163.8 ± 13.7 | 141.4 | 205.1 | 78.11 ± 49.86 |
| `lanjian/day_06 input-aspidites` | 2.2 ± 1.0 | 0.6 | 12.7 | 1.07 ± 0.83 |
| `lanjian/day_06 input-kcen` | 3.7 ± 4.2 | 0.7 | 43.1 | 1.74 ± 2.28 |
| `lanjian/day_06 input-lanjian` | 2.5 ± 0.8 | 0.8 | 8.5 | 1.17 ± 0.84 |
| `lanjian/day_06 input-mattcl` | 2.1 ± 1.3 | 0.6 | 25.5 | 1.00 |
| `lanjian/day_06 input-pting` | 2.1 ± 0.8 | 0.5 | 5.8 | 1.02 ± 0.75 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.9 ± 0.9 | 1.3 | 7.1 | 1.37 ± 0.96 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.3 ± 2.8 | 0.8 | 33.6 | 1.56 ± 1.66 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.8 ± 1.0 | 0.8 | 10.4 | 1.36 ± 0.99 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.5 ± 0.9 | 0.9 | 16.4 | 1.18 ± 0.87 |
| `mattcl-solver/aoc run 6 input-pting` | 2.9 ± 0.9 | 1.2 | 9.2 | 1.38 ± 0.98 |
| `python pting/day06.py input-aspidites` | 54.6 ± 5.5 | 45.7 | 65.1 | 26.02 ± 16.68 |
| `python pting/day06.py input-kcen` | 52.1 ± 6.5 | 39.3 | 66.9 | 24.86 ± 16.04 |
| `python pting/day06.py input-lanjian` | 53.7 ± 7.9 | 41.6 | 80.8 | 25.59 ± 16.63 |
| `python pting/day06.py input-mattcl` | 52.9 ± 6.8 | 40.2 | 77.1 | 25.22 ± 16.29 |
| `python pting/day06.py input-pting` | 52.6 ± 7.3 | 41.3 | 68.8 | 25.08 ± 16.25 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
