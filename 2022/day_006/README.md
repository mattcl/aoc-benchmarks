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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 11.1 ± 0.1 | 10.9 | 11.5 | 20.81 ± 2.37 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 11.0 ± 0.1 | 10.8 | 12.0 | 20.74 ± 2.36 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 11.1 ± 0.1 | 10.8 | 11.4 | 20.79 ± 2.36 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 11.0 ± 0.1 | 10.9 | 11.6 | 20.75 ± 2.36 |
| `aspidites-solver/aoc -i input-pting -d 6` | 11.1 ± 0.1 | 10.9 | 11.6 | 20.80 ± 2.37 |
| `kcen/2022/06/solve input-aspidites` | 67.9 ± 0.9 | 65.8 | 69.7 | 127.56 ± 14.53 |
| `kcen/2022/06/solve input-kcen` | 67.8 ± 0.8 | 66.2 | 70.2 | 127.53 ± 14.53 |
| `kcen/2022/06/solve input-lanjian` | 68.2 ± 1.1 | 66.5 | 74.1 | 128.23 ± 14.68 |
| `kcen/2022/06/solve input-mattcl` | 68.2 ± 0.8 | 66.7 | 70.2 | 128.13 ± 14.59 |
| `kcen/2022/06/solve input-pting` | 67.9 ± 0.9 | 66.4 | 70.7 | 127.75 ± 14.56 |
| `lanjian/day_06 input-aspidites` | 0.6 ± 0.1 | 0.4 | 3.2 | 1.05 ± 0.25 |
| `lanjian/day_06 input-kcen` | 0.5 ± 0.1 | 0.4 | 1.0 | 1.00 |
| `lanjian/day_06 input-lanjian` | 0.5 ± 0.1 | 0.4 | 6.1 | 1.02 ± 0.26 |
| `lanjian/day_06 input-mattcl` | 0.5 ± 0.1 | 0.4 | 2.4 | 1.00 ± 0.17 |
| `lanjian/day_06 input-pting` | 0.5 ± 0.1 | 0.4 | 2.6 | 1.01 ± 0.18 |
| `mattcl-solver/aoc run 6 input-aspidites` | 0.6 ± 0.1 | 0.5 | 1.0 | 1.19 ± 0.18 |
| `mattcl-solver/aoc run 6 input-kcen` | 0.6 ± 0.1 | 0.5 | 1.9 | 1.16 ± 0.18 |
| `mattcl-solver/aoc run 6 input-lanjian` | 0.6 ± 0.1 | 0.5 | 1.3 | 1.16 ± 0.18 |
| `mattcl-solver/aoc run 6 input-mattcl` | 0.6 ± 0.1 | 0.5 | 2.5 | 1.16 ± 0.19 |
| `mattcl-solver/aoc run 6 input-pting` | 0.6 ± 0.1 | 0.5 | 5.5 | 1.17 ± 0.26 |
| `python pting/day06/day06.py input-aspidites` | 20.7 ± 0.3 | 20.0 | 22.4 | 38.89 ± 4.45 |
| `python pting/day06/day06.py input-kcen` | 20.6 ± 0.4 | 19.9 | 22.1 | 38.67 ± 4.43 |
| `python pting/day06/day06.py input-lanjian` | 21.5 ± 0.7 | 20.5 | 28.2 | 40.42 ± 4.77 |
| `python pting/day06/day06.py input-mattcl` | 20.3 ± 0.5 | 19.4 | 22.2 | 38.19 ± 4.41 |
| `python pting/day06/day06.py input-pting` | 21.1 ± 0.4 | 20.4 | 23.0 | 39.70 ± 4.56 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
