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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.9 ± 1.9 | 23.5 | 36.5 | 13.11 ± 7.03 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.8 ± 2.1 | 23.2 | 38.8 | 13.09 ± 7.03 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 27.5 ± 4.7 | 24.0 | 55.9 | 13.92 ± 7.77 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 41.3 ± 33.8 | 13.6 | 227.1 | 20.90 ± 20.38 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.0 ± 3.0 | 23.7 | 39.4 | 13.18 ± 7.16 |
| `kcen/2022/06/solve input-aspidites` | 199.8 ± 22.3 | 164.6 | 231.6 | 101.19 ± 54.92 |
| `kcen/2022/06/solve input-kcen` | 180.0 ± 24.6 | 145.8 | 228.0 | 91.17 ± 50.00 |
| `kcen/2022/06/solve input-lanjian` | 199.7 ± 23.3 | 159.7 | 236.1 | 101.14 ± 55.00 |
| `kcen/2022/06/solve input-mattcl` | 170.0 ± 8.2 | 152.2 | 183.2 | 86.06 ± 45.90 |
| `kcen/2022/06/solve input-pting` | 181.1 ± 20.5 | 154.6 | 223.8 | 91.70 ± 49.80 |
| `lanjian/day_06 input-aspidites` | 2.0 ± 1.0 | 0.4 | 9.3 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.7 ± 1.1 | 0.8 | 13.3 | 1.36 ± 0.92 |
| `lanjian/day_06 input-lanjian` | 2.6 ± 0.9 | 0.7 | 6.2 | 1.30 ± 0.83 |
| `lanjian/day_06 input-mattcl` | 2.2 ± 1.7 | 0.5 | 27.1 | 1.10 ± 1.04 |
| `lanjian/day_06 input-pting` | 2.6 ± 1.6 | 0.5 | 21.6 | 1.32 ± 1.06 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.7 ± 1.2 | 0.8 | 12.4 | 1.34 ± 0.93 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.8 ± 1.1 | 1.0 | 13.8 | 1.40 ± 0.93 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.6 ± 1.2 | 0.6 | 15.1 | 1.30 ± 0.93 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.1 ± 1.5 | 0.7 | 17.0 | 1.57 ± 1.14 |
| `mattcl-solver/aoc run 6 input-pting` | 2.6 ± 1.1 | 0.8 | 8.5 | 1.34 ± 0.91 |
| `python pting/day06.py input-aspidites` | 59.1 ± 10.0 | 46.2 | 95.4 | 29.93 ± 16.69 |
| `python pting/day06.py input-kcen` | 62.0 ± 13.4 | 43.6 | 102.6 | 31.38 ± 17.99 |
| `python pting/day06.py input-lanjian` | 63.8 ± 12.1 | 49.1 | 92.1 | 32.31 ± 18.22 |
| `python pting/day06.py input-mattcl` | 53.1 ± 8.7 | 42.1 | 79.9 | 26.91 ± 14.96 |
| `python pting/day06.py input-pting` | 56.3 ± 8.5 | 45.9 | 89.7 | 28.50 ± 15.74 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
