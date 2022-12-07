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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.6 ± 3.1 | 22.5 | 42.6 | 16.11 ± 15.93 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 26.3 ± 3.0 | 23.4 | 37.4 | 16.56 ± 16.36 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.8 ± 7.8 | 18.8 | 94.9 | 16.88 ± 17.28 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 24.0 ± 4.0 | 12.3 | 37.7 | 15.11 ± 15.05 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.4 ± 4.2 | 20.8 | 46.1 | 16.63 ± 16.53 |
| `kcen/2022/06/solve input-aspidites` | 204.4 ± 26.2 | 158.0 | 265.1 | 128.75 ± 127.45 |
| `kcen/2022/06/solve input-kcen` | 209.8 ± 29.8 | 178.1 | 272.5 | 132.15 ± 131.06 |
| `kcen/2022/06/solve input-lanjian` | 202.6 ± 20.2 | 169.7 | 242.7 | 127.64 ± 125.94 |
| `kcen/2022/06/solve input-mattcl` | 188.9 ± 20.8 | 153.3 | 235.1 | 118.98 ± 117.52 |
| `kcen/2022/06/solve input-pting` | 189.3 ± 21.0 | 159.5 | 229.6 | 119.23 ± 117.79 |
| `lanjian/day_06 input-aspidites` | 1.9 ± 1.4 | 0.0 | 10.4 | 1.20 ± 1.46 |
| `lanjian/day_06 input-kcen` | 1.8 ± 1.3 | 0.0 | 13.1 | 1.14 ± 1.38 |
| `lanjian/day_06 input-lanjian` | 1.8 ± 1.3 | 0.0 | 10.4 | 1.11 ± 1.35 |
| `lanjian/day_06 input-mattcl` | 2.1 ± 1.8 | 0.0 | 15.3 | 1.34 ± 1.76 |
| `lanjian/day_06 input-pting` | 1.6 ± 1.6 | 0.0 | 17.3 | 1.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 1.8 ± 1.3 | 0.0 | 13.4 | 1.13 ± 1.37 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.9 ± 1.1 | 0.0 | 6.3 | 1.21 ± 1.37 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.7 ± 2.0 | 0.0 | 17.4 | 1.69 ± 2.07 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.2 ± 2.7 | 0.1 | 21.5 | 2.00 ± 2.60 |
| `mattcl-solver/aoc run 6 input-pting` | 2.0 ± 2.4 | 0.0 | 37.4 | 1.29 ± 1.96 |
| `python pting/day06.py input-aspidites` | 93.1 ± 62.6 | 44.2 | 350.7 | 58.66 ± 69.80 |
| `python pting/day06.py input-kcen` | 65.1 ± 11.8 | 46.1 | 102.6 | 41.03 ± 40.96 |
| `python pting/day06.py input-lanjian` | 61.5 ± 11.4 | 45.9 | 120.4 | 38.74 ± 38.70 |
| `python pting/day06.py input-mattcl` | 61.8 ± 11.1 | 43.0 | 85.3 | 38.95 ± 38.86 |
| `python pting/day06.py input-pting` | 57.9 ± 10.9 | 41.5 | 94.0 | 36.46 ± 36.44 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
