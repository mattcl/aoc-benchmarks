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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 23.9 ± 5.0 | 12.5 | 47.7 | 14.05 ± 8.61 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 23.6 ± 3.2 | 12.6 | 27.6 | 13.88 ± 8.22 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.7 ± 3.5 | 22.6 | 49.2 | 15.10 ± 8.95 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.9 ± 5.2 | 12.6 | 47.0 | 14.06 ± 8.67 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.3 ± 4.6 | 23.2 | 54.8 | 15.46 ± 9.32 |
| `kcen/2022/06/solve input-aspidites` | 180.5 ± 20.7 | 150.8 | 230.8 | 106.11 ± 62.34 |
| `kcen/2022/06/solve input-kcen` | 179.8 ± 21.0 | 142.2 | 217.8 | 105.72 ± 62.15 |
| `kcen/2022/06/solve input-lanjian` | 178.4 ± 13.0 | 159.8 | 201.8 | 104.91 ± 60.93 |
| `kcen/2022/06/solve input-mattcl` | 163.7 ± 11.2 | 146.2 | 189.1 | 96.23 ± 55.84 |
| `kcen/2022/06/solve input-pting` | 174.5 ± 14.3 | 155.1 | 199.9 | 102.57 ± 59.70 |
| `lanjian/day_06 input-aspidites` | 2.0 ± 0.9 | 0.2 | 11.1 | 1.17 ± 0.86 |
| `lanjian/day_06 input-kcen` | 2.0 ± 1.4 | 0.1 | 20.0 | 1.20 ± 1.08 |
| `lanjian/day_06 input-lanjian` | 1.7 ± 1.0 | 0.2 | 9.2 | 1.00 |
| `lanjian/day_06 input-mattcl` | 4.1 ± 13.5 | 0.0 | 395.2 | 2.39 ± 8.05 |
| `lanjian/day_06 input-pting` | 2.1 ± 0.9 | 0.4 | 7.7 | 1.26 ± 0.91 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.4 ± 1.0 | 0.6 | 14.7 | 1.40 ± 1.01 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.6 ± 1.3 | 0.5 | 15.0 | 1.54 ± 1.19 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.5 ± 1.1 | 0.5 | 9.2 | 1.44 ± 1.04 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.6 ± 1.1 | 0.6 | 15.1 | 1.50 ± 1.07 |
| `mattcl-solver/aoc run 6 input-pting` | 2.2 ± 1.0 | 0.5 | 10.0 | 1.28 ± 0.94 |
| `python pting/day06.py input-aspidites` | 52.3 ± 7.1 | 42.8 | 70.0 | 30.78 ± 18.22 |
| `python pting/day06.py input-kcen` | 53.8 ± 8.6 | 42.0 | 76.9 | 31.64 ± 18.92 |
| `python pting/day06.py input-lanjian` | 59.1 ± 9.5 | 45.4 | 95.9 | 34.75 ± 20.78 |
| `python pting/day06.py input-mattcl` | 53.6 ± 7.1 | 42.7 | 71.6 | 31.49 ± 18.62 |
| `python pting/day06.py input-pting` | 56.6 ± 9.8 | 44.5 | 101.1 | 33.27 ± 20.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
