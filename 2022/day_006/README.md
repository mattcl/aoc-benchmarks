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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 27.6 ± 5.3 | 23.4 | 47.3 | 14.61 ± 7.98 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.3 ± 4.5 | 13.7 | 66.2 | 13.40 ± 7.26 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.8 ± 4.4 | 15.9 | 47.4 | 13.65 ± 7.37 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 22.2 ± 5.3 | 12.8 | 37.3 | 11.74 ± 6.64 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.1 ± 1.9 | 23.1 | 34.7 | 13.28 ± 6.87 |
| `kcen/2022/06/solve input-aspidites` | 186.5 ± 25.6 | 150.7 | 227.0 | 98.64 ± 52.29 |
| `kcen/2022/06/solve input-kcen` | 171.3 ± 14.3 | 157.4 | 209.6 | 90.63 ± 47.02 |
| `kcen/2022/06/solve input-lanjian` | 184.5 ± 18.9 | 156.9 | 225.8 | 97.60 ± 50.96 |
| `kcen/2022/06/solve input-mattcl` | 182.9 ± 15.9 | 160.9 | 217.0 | 96.77 ± 50.26 |
| `kcen/2022/06/solve input-pting` | 195.6 ± 13.8 | 165.9 | 217.0 | 103.46 ± 53.48 |
| `lanjian/day_06 input-aspidites` | 2.1 ± 1.3 | 0.3 | 18.2 | 1.09 ± 0.87 |
| `lanjian/day_06 input-kcen` | 2.0 ± 1.3 | 0.2 | 15.5 | 1.08 ± 0.87 |
| `lanjian/day_06 input-lanjian` | 2.4 ± 1.6 | 0.6 | 17.2 | 1.27 ± 1.08 |
| `lanjian/day_06 input-mattcl` | 1.9 ± 1.0 | 0.6 | 11.6 | 1.00 |
| `lanjian/day_06 input-pting` | 2.1 ± 0.9 | 0.6 | 9.5 | 1.11 ± 0.75 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.6 ± 1.2 | 0.8 | 15.9 | 1.37 ± 0.93 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.7 ± 1.1 | 0.9 | 10.9 | 1.44 ± 0.95 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.7 ± 1.4 | 0.9 | 14.6 | 1.41 ± 1.02 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.9 ± 1.0 | 1.1 | 16.0 | 1.54 ± 0.96 |
| `mattcl-solver/aoc run 6 input-pting` | 2.4 ± 1.4 | 0.9 | 20.8 | 1.25 ± 0.98 |
| `python pting/day06.py input-aspidites` | 57.3 ± 7.3 | 45.1 | 89.7 | 30.30 ± 15.98 |
| `python pting/day06.py input-kcen` | 53.7 ± 6.2 | 42.2 | 70.8 | 28.42 ± 14.92 |
| `python pting/day06.py input-lanjian` | 78.5 ± 22.8 | 44.0 | 144.5 | 41.55 ± 24.47 |
| `python pting/day06.py input-mattcl` | 58.0 ± 7.6 | 47.2 | 79.2 | 30.70 ± 16.23 |
| `python pting/day06.py input-pting` | 61.2 ± 9.9 | 46.3 | 88.6 | 32.39 ± 17.38 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
