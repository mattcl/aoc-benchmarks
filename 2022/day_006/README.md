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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.6 ± 4.7 | 23.0 | 61.5 | 24.84 ± 23.87 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.9 ± 3.1 | 15.9 | 46.5 | 24.27 ± 23.10 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 27.0 ± 4.0 | 22.8 | 39.6 | 25.21 ± 24.11 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 26.6 ± 6.6 | 13.1 | 63.9 | 24.86 ± 24.28 |
| `aspidites-solver/aoc -i input-pting -d 6` | 27.4 ± 4.4 | 23.5 | 41.9 | 25.62 ± 24.54 |
| `kcen/2022/06/solve input-aspidites` | 187.2 ± 26.4 | 150.7 | 247.5 | 175.08 ± 167.22 |
| `kcen/2022/06/solve input-kcen` | 187.1 ± 21.2 | 156.8 | 250.6 | 175.01 ± 166.51 |
| `kcen/2022/06/solve input-lanjian` | 192.6 ± 17.9 | 163.3 | 219.4 | 180.19 ± 171.03 |
| `kcen/2022/06/solve input-mattcl` | 205.3 ± 25.9 | 175.1 | 255.1 | 192.07 ± 183.04 |
| `kcen/2022/06/solve input-pting` | 202.7 ± 21.0 | 170.1 | 242.3 | 189.63 ± 180.21 |
| `lanjian/day_06 input-aspidites` | 2.4 ± 1.9 | 0.0 | 18.4 | 2.29 ± 2.83 |
| `lanjian/day_06 input-kcen` | 1.9 ± 1.3 | 0.0 | 10.9 | 1.81 ± 2.11 |
| `lanjian/day_06 input-lanjian` | 2.2 ± 1.4 | 0.0 | 12.7 | 2.03 ± 2.32 |
| `lanjian/day_06 input-mattcl` | 1.1 ± 1.0 | 0.0 | 7.7 | 1.00 |
| `lanjian/day_06 input-pting` | 1.6 ± 1.8 | 0.0 | 22.9 | 1.52 ± 2.22 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.9 ± 1.5 | 0.3 | 14.7 | 2.69 ± 2.90 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.8 ± 1.3 | 0.6 | 13.5 | 2.58 ± 2.72 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.1 ± 1.1 | 0.0 | 6.2 | 1.97 ± 2.14 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.0 ± 1.1 | 0.1 | 8.3 | 1.90 ± 2.06 |
| `mattcl-solver/aoc run 6 input-pting` | 2.9 ± 1.7 | 0.0 | 15.3 | 2.75 ± 3.06 |
| `python pting/day06.py input-aspidites` | 61.5 ± 12.1 | 43.9 | 100.9 | 57.51 ± 55.49 |
| `python pting/day06.py input-kcen` | 56.8 ± 9.5 | 43.2 | 84.8 | 53.15 ± 50.99 |
| `python pting/day06.py input-lanjian` | 59.4 ± 9.2 | 47.6 | 89.7 | 55.55 ± 53.18 |
| `python pting/day06.py input-mattcl` | 56.8 ± 8.4 | 45.0 | 86.8 | 53.13 ± 50.80 |
| `python pting/day06.py input-pting` | 65.1 ± 14.0 | 48.0 | 103.8 | 60.85 ± 58.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
