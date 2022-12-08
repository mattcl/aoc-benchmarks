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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.6 ± 3.2 | 23.4 | 38.0 | 18.83 ± 13.44 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.7 ± 3.8 | 13.0 | 45.4 | 18.18 ± 13.06 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.9 ± 4.6 | 22.8 | 42.2 | 19.01 ± 13.76 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 36.7 ± 23.1 | 12.7 | 119.5 | 25.97 ± 24.53 |
| `aspidites-solver/aoc -i input-pting -d 6` | 27.3 ± 4.3 | 23.7 | 46.9 | 19.35 ± 13.95 |
| `kcen/2022/06/solve input-aspidites` | 196.0 ± 24.4 | 158.1 | 240.0 | 138.68 ± 99.06 |
| `kcen/2022/06/solve input-kcen` | 176.9 ± 16.0 | 151.6 | 208.6 | 125.17 ± 88.76 |
| `kcen/2022/06/solve input-lanjian` | 205.8 ± 33.5 | 171.6 | 297.6 | 145.68 ± 105.17 |
| `kcen/2022/06/solve input-mattcl` | 201.4 ± 27.9 | 163.8 | 246.3 | 142.53 ± 102.17 |
| `kcen/2022/06/solve input-pting` | 202.8 ± 30.7 | 152.1 | 249.7 | 143.50 ± 103.24 |
| `lanjian/day_06 input-aspidites` | 1.4 ± 1.0 | 0.0 | 10.6 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.5 ± 1.3 | 0.1 | 11.1 | 1.73 ± 1.54 |
| `lanjian/day_06 input-lanjian` | 2.2 ± 1.2 | 0.2 | 12.4 | 1.54 ± 1.39 |
| `lanjian/day_06 input-mattcl` | 2.2 ± 1.3 | 0.2 | 17.4 | 1.58 ± 1.47 |
| `lanjian/day_06 input-pting` | 2.0 ± 1.1 | 0.0 | 7.4 | 1.41 ± 1.25 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.7 ± 1.3 | 0.8 | 12.9 | 1.89 ± 1.62 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.8 ± 1.2 | 0.8 | 13.1 | 1.99 ± 1.64 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.0 ± 1.2 | 0.7 | 9.7 | 2.09 ± 1.71 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.7 ± 1.4 | 0.3 | 10.8 | 1.88 ± 1.67 |
| `mattcl-solver/aoc run 6 input-pting` | 3.0 ± 1.1 | 0.3 | 9.4 | 2.12 ± 1.67 |
| `python pting/day06.py input-aspidites` | 66.2 ± 8.5 | 52.5 | 84.2 | 46.86 ± 33.51 |
| `python pting/day06.py input-kcen` | 61.5 ± 9.7 | 48.5 | 91.6 | 43.50 ± 31.35 |
| `python pting/day06.py input-lanjian` | 63.4 ± 9.8 | 49.9 | 88.6 | 44.88 ± 32.31 |
| `python pting/day06.py input-mattcl` | 65.4 ± 12.1 | 48.3 | 103.7 | 46.26 ± 33.65 |
| `python pting/day06.py input-pting` | 58.2 ± 13.1 | 43.5 | 128.3 | 41.21 ± 30.44 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
