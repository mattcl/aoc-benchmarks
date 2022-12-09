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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.6 ± 5.8 | 13.3 | 54.6 | 12.33 ± 6.16 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 24.5 ± 3.9 | 13.3 | 36.8 | 11.34 ± 5.40 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.3 ± 3.7 | 23.4 | 50.4 | 12.19 ± 5.73 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 24.8 ± 7.7 | 13.4 | 68.2 | 11.47 ± 6.26 |
| `aspidites-solver/aoc -i input-pting -d 6` | 27.9 ± 5.4 | 23.4 | 48.2 | 12.93 ± 6.32 |
| `kcen/2022/06/solve input-aspidites` | 193.4 ± 23.9 | 159.2 | 253.1 | 89.55 ± 41.70 |
| `kcen/2022/06/solve input-kcen` | 196.5 ± 36.2 | 159.0 | 281.5 | 90.98 ± 44.14 |
| `kcen/2022/06/solve input-lanjian` | 192.7 ± 13.8 | 175.1 | 226.7 | 89.23 ± 40.56 |
| `kcen/2022/06/solve input-mattcl` | 198.3 ± 27.5 | 169.6 | 271.3 | 91.84 ± 43.14 |
| `kcen/2022/06/solve input-pting` | 213.4 ± 40.4 | 143.1 | 283.1 | 98.83 ± 48.15 |
| `lanjian/day_06 input-aspidites` | 2.2 ± 1.1 | 0.6 | 8.6 | 1.03 ± 0.70 |
| `lanjian/day_06 input-kcen` | 2.2 ± 1.0 | 0.7 | 8.1 | 1.00 |
| `lanjian/day_06 input-lanjian` | 2.9 ± 1.8 | 0.9 | 14.1 | 1.36 ± 1.02 |
| `lanjian/day_06 input-mattcl` | 2.4 ± 1.1 | 0.7 | 10.9 | 1.12 ± 0.73 |
| `lanjian/day_06 input-pting` | 3.1 ± 1.5 | 0.8 | 11.7 | 1.43 ± 0.93 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.9 ± 1.4 | 1.0 | 17.7 | 1.34 ± 0.88 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.5 ± 1.1 | 0.7 | 8.1 | 1.17 ± 0.72 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.0 ± 1.4 | 0.9 | 18.4 | 1.37 ± 0.90 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.1 ± 1.6 | 1.0 | 18.1 | 1.42 ± 0.97 |
| `mattcl-solver/aoc run 6 input-pting` | 3.6 ± 2.4 | 1.0 | 44.4 | 1.66 ± 1.34 |
| `python pting/day06.py input-aspidites` | 54.7 ± 12.1 | 42.4 | 101.3 | 25.31 ± 12.66 |
| `python pting/day06.py input-kcen` | 56.5 ± 14.7 | 42.3 | 121.1 | 26.19 ± 13.58 |
| `python pting/day06.py input-lanjian` | 165.0 ± 70.4 | 77.9 | 401.7 | 76.43 ± 47.32 |
| `python pting/day06.py input-mattcl` | 61.0 ± 21.5 | 42.7 | 118.9 | 28.24 ± 16.13 |
| `python pting/day06.py input-pting` | 65.0 ± 25.3 | 43.2 | 169.2 | 30.08 ± 17.87 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
