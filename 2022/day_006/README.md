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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.3 ± 2.9 | 13.0 | 37.2 | 14.61 ± 6.52 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 23.6 ± 5.6 | 12.8 | 64.0 | 13.64 ± 6.70 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 24.8 ± 2.2 | 23.0 | 44.2 | 14.34 ± 6.30 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 18.9 ± 5.6 | 12.7 | 26.8 | 10.96 ± 5.72 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.5 ± 4.4 | 23.4 | 45.4 | 15.34 ± 7.07 |
| `kcen/2022/06/solve input-aspidites` | 180.1 ± 21.4 | 146.8 | 217.7 | 104.18 ± 46.52 |
| `kcen/2022/06/solve input-kcen` | 163.6 ± 12.4 | 145.7 | 186.6 | 94.66 ± 41.38 |
| `kcen/2022/06/solve input-lanjian` | 181.6 ± 15.2 | 154.9 | 222.4 | 105.04 ± 46.06 |
| `kcen/2022/06/solve input-mattcl` | 156.1 ± 8.1 | 136.8 | 172.7 | 90.31 ± 39.15 |
| `kcen/2022/06/solve input-pting` | 227.8 ± 81.6 | 139.3 | 355.0 | 131.80 ± 73.80 |
| `lanjian/day_06 input-aspidites` | 1.7 ± 0.7 | 0.4 | 8.1 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.5 ± 1.3 | 0.9 | 18.2 | 1.47 ± 0.97 |
| `lanjian/day_06 input-lanjian` | 3.7 ± 4.0 | 0.6 | 54.1 | 2.13 ± 2.50 |
| `lanjian/day_06 input-mattcl` | 2.0 ± 1.2 | 0.7 | 18.8 | 1.18 ± 0.84 |
| `lanjian/day_06 input-pting` | 2.0 ± 1.0 | 0.6 | 11.7 | 1.17 ± 0.75 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.4 ± 0.9 | 0.9 | 7.8 | 1.39 ± 0.79 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.8 ± 1.2 | 0.9 | 9.8 | 1.63 ± 0.98 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.3 ± 0.8 | 0.7 | 7.3 | 1.32 ± 0.73 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.6 ± 1.0 | 1.0 | 8.1 | 1.52 ± 0.88 |
| `mattcl-solver/aoc run 6 input-pting` | 2.4 ± 0.9 | 1.0 | 13.1 | 1.40 ± 0.79 |
| `python pting/day06.py input-aspidites` | 52.7 ± 5.0 | 43.9 | 63.5 | 30.50 ± 13.45 |
| `python pting/day06.py input-kcen` | 55.6 ± 6.9 | 45.8 | 70.1 | 32.19 ± 14.42 |
| `python pting/day06.py input-lanjian` | 54.1 ± 7.5 | 39.2 | 73.4 | 31.31 ± 14.15 |
| `python pting/day06.py input-mattcl` | 52.2 ± 6.1 | 41.8 | 67.3 | 30.20 ± 13.47 |
| `python pting/day06.py input-pting` | 52.4 ± 5.4 | 43.2 | 66.7 | 30.32 ± 13.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
