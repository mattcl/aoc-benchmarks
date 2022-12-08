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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 27.2 ± 6.4 | 14.7 | 68.0 | 14.37 ± 7.74 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 26.2 ± 3.5 | 23.5 | 43.9 | 13.81 ± 6.94 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 27.6 ± 7.2 | 23.3 | 68.2 | 14.57 ± 8.02 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 27.8 ± 5.7 | 12.7 | 48.7 | 14.66 ± 7.72 |
| `aspidites-solver/aoc -i input-pting -d 6` | 27.8 ± 5.8 | 23.6 | 51.3 | 14.65 ± 7.73 |
| `kcen/2022/06/solve input-aspidites` | 192.4 ± 39.5 | 156.3 | 319.8 | 101.52 ± 53.41 |
| `kcen/2022/06/solve input-kcen` | 192.3 ± 39.6 | 155.2 | 288.8 | 101.45 ± 53.42 |
| `kcen/2022/06/solve input-lanjian` | 214.6 ± 39.3 | 173.1 | 292.8 | 113.21 ± 58.65 |
| `kcen/2022/06/solve input-mattcl` | 248.2 ± 85.0 | 171.4 | 492.3 | 130.91 ± 77.69 |
| `kcen/2022/06/solve input-pting` | 191.7 ± 25.7 | 163.4 | 241.7 | 101.11 ± 50.84 |
| `lanjian/day_06 input-aspidites` | 2.4 ± 1.9 | 0.0 | 15.7 | 1.26 ± 1.19 |
| `lanjian/day_06 input-kcen` | 2.1 ± 1.2 | 0.0 | 16.2 | 1.10 ± 0.84 |
| `lanjian/day_06 input-lanjian` | 2.2 ± 1.5 | 0.0 | 12.4 | 1.14 ± 0.96 |
| `lanjian/day_06 input-mattcl` | 1.9 ± 1.5 | 0.0 | 22.3 | 1.01 ± 0.93 |
| `lanjian/day_06 input-pting` | 2.0 ± 1.6 | 0.0 | 11.3 | 1.06 ± 1.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.9 ± 1.9 | 0.0 | 19.8 | 1.51 ± 1.24 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.9 ± 0.9 | 0.3 | 6.2 | 1.00 |
| `mattcl-solver/aoc run 6 input-lanjian` | 5.5 ± 6.5 | 0.6 | 59.2 | 2.90 ± 3.73 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.6 ± 1.9 | 0.2 | 26.5 | 1.37 ± 1.22 |
| `mattcl-solver/aoc run 6 input-pting` | 3.7 ± 2.5 | 0.4 | 26.4 | 1.96 ± 1.63 |
| `python pting/day06.py input-aspidites` | 59.0 ± 8.4 | 46.6 | 76.5 | 31.11 ± 15.71 |
| `python pting/day06.py input-kcen` | 64.7 ± 22.3 | 41.8 | 181.9 | 34.14 ± 20.29 |
| `python pting/day06.py input-lanjian` | 77.4 ± 35.0 | 49.0 | 191.9 | 40.83 ± 27.08 |
| `python pting/day06.py input-mattcl` | 57.9 ± 20.9 | 43.1 | 140.1 | 30.54 ± 18.46 |
| `python pting/day06.py input-pting` | 62.5 ± 10.5 | 47.6 | 86.1 | 32.96 ± 16.90 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
