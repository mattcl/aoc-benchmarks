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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 27.0 ± 7.9 | 13.0 | 58.6 | 15.18 ± 13.04 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 27.8 ± 7.0 | 13.2 | 41.3 | 15.65 ± 13.24 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 27.7 ± 6.7 | 23.2 | 50.3 | 15.57 ± 13.13 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 25.3 ± 9.5 | 13.1 | 63.0 | 14.23 ± 12.68 |
| `aspidites-solver/aoc -i input-pting -d 6` | 30.0 ± 8.8 | 23.3 | 63.4 | 16.91 ± 14.53 |
| `kcen/2022/06/solve input-aspidites` | 180.6 ± 40.0 | 133.7 | 263.8 | 101.70 ± 85.15 |
| `kcen/2022/06/solve input-kcen` | 197.2 ± 44.8 | 158.9 | 337.5 | 111.01 ± 93.12 |
| `kcen/2022/06/solve input-lanjian` | 210.7 ± 63.7 | 153.5 | 350.4 | 118.66 ± 102.30 |
| `kcen/2022/06/solve input-mattcl` | 183.2 ± 44.9 | 151.8 | 332.6 | 103.15 ± 87.03 |
| `kcen/2022/06/solve input-pting` | 189.0 ± 72.0 | 147.4 | 450.2 | 106.39 ± 94.99 |
| `lanjian/day_06 input-aspidites` | 3.3 ± 2.0 | 0.8 | 18.8 | 1.87 ± 1.87 |
| `lanjian/day_06 input-kcen` | 2.5 ± 1.7 | 0.5 | 23.3 | 1.43 ± 1.51 |
| `lanjian/day_06 input-lanjian` | 1.8 ± 1.4 | 0.6 | 13.8 | 1.00 |
| `lanjian/day_06 input-mattcl` | 3.2 ± 1.7 | 0.8 | 11.2 | 1.78 ± 1.73 |
| `lanjian/day_06 input-pting` | 3.1 ± 1.5 | 0.8 | 10.5 | 1.74 ± 1.63 |
| `mattcl-solver/aoc run 6 input-aspidites` | 3.3 ± 1.6 | 1.2 | 9.8 | 1.86 ± 1.74 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.9 ± 1.6 | 1.2 | 10.7 | 2.19 ± 1.99 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.2 ± 1.2 | 0.7 | 7.7 | 1.23 ± 1.21 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.1 ± 1.6 | 0.7 | 12.3 | 1.75 ± 1.69 |
| `mattcl-solver/aoc run 6 input-pting` | 3.5 ± 1.7 | 0.9 | 14.8 | 1.95 ± 1.85 |
| `python pting/day06.py input-aspidites` | 54.5 ± 17.6 | 42.7 | 127.0 | 30.67 ± 26.66 |
| `python pting/day06.py input-kcen` | 69.7 ± 44.2 | 42.5 | 189.2 | 39.23 ± 40.27 |
| `python pting/day06.py input-lanjian` | 60.8 ± 27.2 | 40.0 | 170.5 | 34.26 ± 31.61 |
| `python pting/day06.py input-mattcl` | 68.0 ± 39.5 | 35.0 | 177.1 | 38.31 ± 38.11 |
| `python pting/day06.py input-pting` | 66.3 ± 25.8 | 43.6 | 139.3 | 37.31 ± 33.44 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
