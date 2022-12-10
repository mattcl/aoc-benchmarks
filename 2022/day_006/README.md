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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 23.3 ± 3.7 | 12.7 | 28.3 | 11.54 ± 5.49 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 22.7 ± 5.1 | 12.7 | 40.3 | 11.27 ± 5.63 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.2 ± 2.4 | 14.8 | 37.8 | 12.48 ± 5.71 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 19.2 ± 5.9 | 12.8 | 34.2 | 9.52 ± 5.17 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.7 ± 2.7 | 23.3 | 38.4 | 12.74 ± 5.86 |
| `kcen/2022/06/solve input-aspidites` | 168.1 ± 14.5 | 147.4 | 204.5 | 83.37 ± 37.99 |
| `kcen/2022/06/solve input-kcen` | 172.5 ± 15.5 | 139.6 | 195.7 | 85.52 ± 39.03 |
| `kcen/2022/06/solve input-lanjian` | 159.4 ± 12.8 | 137.2 | 179.7 | 79.06 ± 35.95 |
| `kcen/2022/06/solve input-mattcl` | 174.2 ± 10.7 | 154.5 | 196.3 | 86.38 ± 39.01 |
| `kcen/2022/06/solve input-pting` | 171.8 ± 14.6 | 156.8 | 202.1 | 85.22 ± 38.82 |
| `lanjian/day_06 input-aspidites` | 2.2 ± 1.0 | 0.8 | 9.7 | 1.10 ± 0.69 |
| `lanjian/day_06 input-kcen` | 2.5 ± 1.3 | 1.0 | 12.9 | 1.25 ± 0.85 |
| `lanjian/day_06 input-lanjian` | 2.0 ± 0.9 | 0.5 | 8.6 | 1.00 |
| `lanjian/day_06 input-mattcl` | 5.1 ± 4.7 | 1.1 | 37.6 | 2.53 ± 2.58 |
| `lanjian/day_06 input-pting` | 2.4 ± 1.2 | 0.8 | 9.6 | 1.19 ± 0.82 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.8 ± 1.0 | 0.9 | 10.9 | 1.39 ± 0.79 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.5 ± 1.2 | 1.0 | 22.7 | 1.22 ± 0.79 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.7 ± 1.3 | 0.8 | 18.1 | 1.35 ± 0.87 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.5 ± 0.9 | 0.9 | 9.6 | 1.24 ± 0.72 |
| `mattcl-solver/aoc run 6 input-pting` | 2.7 ± 1.3 | 0.9 | 11.2 | 1.34 ± 0.87 |
| `python pting/day06.py input-aspidites` | 54.2 ± 7.0 | 42.8 | 73.4 | 26.86 ± 12.51 |
| `python pting/day06.py input-kcen` | 55.5 ± 6.7 | 42.0 | 78.6 | 27.54 ± 12.77 |
| `python pting/day06.py input-lanjian` | 49.7 ± 5.9 | 41.2 | 65.0 | 24.67 ± 11.42 |
| `python pting/day06.py input-mattcl` | 55.3 ± 8.9 | 44.7 | 86.4 | 27.44 ± 13.06 |
| `python pting/day06.py input-pting` | 52.8 ± 5.6 | 42.2 | 71.0 | 26.18 ± 12.03 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
