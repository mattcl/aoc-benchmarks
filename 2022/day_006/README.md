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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 27.0 ± 4.5 | 23.6 | 56.1 | 11.25 ± 6.92 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 26.8 ± 2.4 | 23.7 | 39.8 | 11.13 ± 6.66 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.8 ± 2.3 | 23.4 | 38.5 | 10.73 ± 6.43 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.3 ± 5.8 | 13.1 | 41.7 | 9.69 ± 6.22 |
| `aspidites-solver/aoc -i input-pting -d 6` | 44.8 ± 30.3 | 23.9 | 153.4 | 18.63 ± 16.76 |
| `kcen/2022/06/solve input-aspidites` | 188.7 ± 19.1 | 166.4 | 234.5 | 78.45 ± 47.11 |
| `kcen/2022/06/solve input-kcen` | 197.2 ± 21.1 | 162.2 | 246.1 | 81.98 ± 49.31 |
| `kcen/2022/06/solve input-lanjian` | 185.3 ± 20.1 | 147.9 | 216.3 | 77.05 ± 46.36 |
| `kcen/2022/06/solve input-mattcl` | 190.1 ± 17.4 | 162.4 | 225.1 | 79.06 ± 47.35 |
| `kcen/2022/06/solve input-pting` | 199.8 ± 22.3 | 167.8 | 252.8 | 83.06 ± 50.04 |
| `lanjian/day_06 input-aspidites` | 2.6 ± 1.2 | 0.8 | 14.4 | 1.06 ± 0.81 |
| `lanjian/day_06 input-kcen` | 2.4 ± 1.4 | 0.6 | 16.7 | 1.00 |
| `lanjian/day_06 input-lanjian` | 4.8 ± 4.6 | 0.9 | 36.6 | 2.01 ± 2.25 |
| `lanjian/day_06 input-mattcl` | 2.5 ± 1.3 | 0.5 | 17.0 | 1.05 ± 0.81 |
| `lanjian/day_06 input-pting` | 2.5 ± 1.9 | 0.8 | 20.7 | 1.04 ± 0.99 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.9 ± 1.9 | 0.9 | 29.6 | 1.21 ± 1.08 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.0 ± 1.4 | 0.9 | 16.2 | 1.25 ± 0.95 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.2 ± 1.8 | 1.0 | 20.3 | 1.33 ± 1.10 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.5 ± 1.2 | 0.7 | 15.4 | 1.03 ± 0.79 |
| `mattcl-solver/aoc run 6 input-pting` | 3.8 ± 3.9 | 1.2 | 40.2 | 1.59 ± 1.87 |
| `python pting/day06.py input-aspidites` | 57.7 ± 9.5 | 43.9 | 82.6 | 24.01 ± 14.74 |
| `python pting/day06.py input-kcen` | 57.8 ± 8.2 | 45.4 | 80.3 | 24.05 ± 14.64 |
| `python pting/day06.py input-lanjian` | 85.8 ± 36.2 | 50.0 | 181.8 | 35.66 ± 25.92 |
| `python pting/day06.py input-mattcl` | 55.3 ± 6.9 | 44.3 | 75.6 | 23.01 ± 13.92 |
| `python pting/day06.py input-pting` | 58.9 ± 7.2 | 47.5 | 72.7 | 24.50 ± 14.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
