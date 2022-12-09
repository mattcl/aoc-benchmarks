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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 22.0 ± 4.3 | 11.0 | 38.1 | 43.47 ± 88.13 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 20.7 ± 5.5 | 11.0 | 37.8 | 40.86 ± 83.14 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 23.5 ± 2.1 | 21.6 | 35.8 | 46.42 ± 93.76 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 19.2 ± 6.0 | 11.1 | 42.5 | 37.85 ± 77.27 |
| `aspidites-solver/aoc -i input-pting -d 6` | 22.8 ± 2.6 | 11.2 | 36.3 | 44.99 ± 90.92 |
| `kcen/2022/06/solve input-aspidites` | 174.5 ± 18.4 | 152.6 | 209.8 | 344.49 ± 696.02 |
| `kcen/2022/06/solve input-kcen` | 172.8 ± 17.4 | 146.2 | 210.7 | 341.16 ± 689.21 |
| `kcen/2022/06/solve input-lanjian` | 174.9 ± 18.9 | 144.4 | 205.7 | 345.23 ± 697.56 |
| `kcen/2022/06/solve input-mattcl` | 166.1 ± 20.7 | 148.5 | 236.1 | 327.83 ± 662.71 |
| `kcen/2022/06/solve input-pting` | 152.3 ± 15.4 | 128.9 | 190.0 | 300.66 ± 607.41 |
| `lanjian/day_06 input-aspidites` | 0.9 ± 1.4 | 0.0 | 26.1 | 1.82 ± 4.63 |
| `lanjian/day_06 input-kcen` | 0.8 ± 1.0 | 0.0 | 14.5 | 1.65 ± 3.83 |
| `lanjian/day_06 input-lanjian` | 0.5 ± 1.0 | 0.0 | 14.7 | 1.00 |
| `lanjian/day_06 input-mattcl` | 0.9 ± 1.2 | 0.0 | 12.0 | 1.76 ± 4.22 |
| `lanjian/day_06 input-pting` | 1.0 ± 1.0 | 0.0 | 10.4 | 1.97 ± 4.45 |
| `mattcl-solver/aoc run 6 input-aspidites` | 1.3 ± 1.7 | 0.0 | 15.8 | 2.61 ± 6.23 |
| `mattcl-solver/aoc run 6 input-kcen` | 0.8 ± 0.8 | 0.0 | 5.6 | 1.56 ± 3.51 |
| `mattcl-solver/aoc run 6 input-lanjian` | 0.8 ± 0.8 | 0.0 | 9.0 | 1.52 ± 3.48 |
| `mattcl-solver/aoc run 6 input-mattcl` | 1.0 ± 1.2 | 0.0 | 14.2 | 1.99 ± 4.71 |
| `mattcl-solver/aoc run 6 input-pting` | 0.8 ± 1.3 | 0.0 | 21.0 | 1.56 ± 4.13 |
| `python pting/day06.py input-aspidites` | 50.4 ± 8.0 | 41.0 | 76.6 | 99.51 ± 201.41 |
| `python pting/day06.py input-kcen` | 51.8 ± 7.0 | 41.8 | 77.1 | 102.15 ± 206.58 |
| `python pting/day06.py input-lanjian` | 51.7 ± 6.7 | 41.1 | 70.2 | 102.02 ± 206.27 |
| `python pting/day06.py input-mattcl` | 54.2 ± 6.3 | 44.0 | 69.1 | 107.06 ± 216.37 |
| `python pting/day06.py input-pting` | 51.4 ± 7.2 | 39.7 | 76.6 | 101.39 ± 205.08 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
