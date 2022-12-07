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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 21.0 ± 6.9 | 12.6 | 47.8 | 17.08 ± 11.80 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 18.8 ± 5.6 | 12.5 | 28.7 | 15.32 ± 10.34 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.0 ± 3.6 | 23.3 | 38.1 | 21.16 ± 13.18 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 16.6 ± 5.1 | 12.5 | 30.1 | 13.53 ± 9.22 |
| `aspidites-solver/aoc -i input-pting -d 6` | 23.5 ± 3.0 | 12.8 | 35.3 | 19.13 ± 11.87 |
| `kcen/2022/06/solve input-aspidites` | 145.8 ± 12.8 | 126.4 | 169.6 | 118.67 ± 72.77 |
| `kcen/2022/06/solve input-kcen` | 157.1 ± 20.8 | 130.9 | 200.5 | 127.84 ± 79.40 |
| `kcen/2022/06/solve input-lanjian` | 178.4 ± 25.2 | 135.3 | 219.9 | 145.25 ± 90.50 |
| `kcen/2022/06/solve input-mattcl` | 150.5 ± 9.2 | 136.1 | 176.6 | 122.53 ± 74.73 |
| `kcen/2022/06/solve input-pting` | 148.4 ± 11.5 | 135.2 | 178.2 | 120.81 ± 73.91 |
| `lanjian/day_06 input-aspidites` | 1.2 ± 0.7 | 0.3 | 10.1 | 1.00 |
| `lanjian/day_06 input-kcen` | 1.5 ± 0.8 | 0.2 | 5.2 | 1.23 ± 0.99 |
| `lanjian/day_06 input-lanjian` | 2.6 ± 1.2 | 0.6 | 13.2 | 2.11 ± 1.63 |
| `lanjian/day_06 input-mattcl` | 1.4 ± 0.8 | 0.2 | 6.9 | 1.16 ± 0.95 |
| `lanjian/day_06 input-pting` | 1.5 ± 0.7 | 0.2 | 6.0 | 1.21 ± 0.95 |
| `mattcl-solver/aoc run 6 input-aspidites` | 1.8 ± 0.8 | 0.5 | 5.3 | 1.43 ± 1.07 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.9 ± 0.9 | 0.3 | 10.2 | 1.55 ± 1.20 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.8 ± 1.1 | 0.8 | 8.1 | 2.25 ± 1.64 |
| `mattcl-solver/aoc run 6 input-mattcl` | 1.9 ± 1.0 | 0.5 | 6.8 | 1.58 ± 1.25 |
| `mattcl-solver/aoc run 6 input-pting` | 3.9 ± 4.7 | 0.7 | 66.6 | 3.17 ± 4.31 |
| `python pting/day06.py input-aspidites` | 45.0 ± 5.2 | 36.5 | 66.7 | 36.62 ± 22.62 |
| `python pting/day06.py input-kcen` | 45.7 ± 7.7 | 35.0 | 81.3 | 37.17 ± 23.40 |
| `python pting/day06.py input-lanjian` | 55.6 ± 9.1 | 42.4 | 89.4 | 45.25 ± 28.44 |
| `python pting/day06.py input-mattcl` | 44.2 ± 4.6 | 35.1 | 63.8 | 35.96 ± 22.14 |
| `python pting/day06.py input-pting` | 48.4 ± 5.2 | 41.3 | 69.3 | 39.37 ± 24.27 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
