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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.3 ± 2.2 | 12.9 | 36.2 | 13.26 ± 6.75 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 21.5 ± 5.4 | 12.6 | 30.0 | 11.27 ± 6.32 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 24.9 ± 2.5 | 22.6 | 36.5 | 13.04 ± 6.67 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 21.7 ± 5.7 | 12.6 | 36.3 | 11.36 ± 6.43 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.5 ± 3.6 | 12.6 | 42.2 | 13.39 ± 6.97 |
| `kcen/2022/06/solve input-aspidites` | 171.0 ± 19.0 | 148.1 | 213.7 | 89.63 ± 46.04 |
| `kcen/2022/06/solve input-kcen` | 158.2 ± 10.6 | 146.0 | 184.5 | 82.95 ± 41.96 |
| `kcen/2022/06/solve input-lanjian` | 169.6 ± 16.9 | 146.6 | 211.7 | 88.89 ± 45.45 |
| `kcen/2022/06/solve input-mattcl` | 172.8 ± 14.4 | 144.4 | 198.8 | 90.58 ± 46.05 |
| `kcen/2022/06/solve input-pting` | 265.9 ± 71.0 | 164.6 | 360.8 | 139.40 ± 79.19 |
| `lanjian/day_06 input-aspidites` | 2.7 ± 1.4 | 0.8 | 14.7 | 1.42 ± 1.03 |
| `lanjian/day_06 input-kcen` | 2.3 ± 0.9 | 0.4 | 9.7 | 1.19 ± 0.77 |
| `lanjian/day_06 input-lanjian` | 4.0 ± 4.9 | 0.4 | 50.5 | 2.11 ± 2.79 |
| `lanjian/day_06 input-mattcl` | 2.2 ± 1.1 | 0.5 | 10.7 | 1.17 ± 0.82 |
| `lanjian/day_06 input-pting` | 1.9 ± 1.0 | 0.4 | 9.6 | 1.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.9 ± 1.6 | 1.0 | 15.0 | 1.53 ± 1.14 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.8 ± 1.0 | 0.9 | 15.0 | 1.48 ± 0.92 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.0 ± 0.9 | 0.6 | 7.9 | 1.06 ± 0.73 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.3 ± 1.4 | 0.6 | 13.3 | 1.19 ± 0.93 |
| `mattcl-solver/aoc run 6 input-pting` | 2.2 ± 1.1 | 0.7 | 15.2 | 1.17 ± 0.81 |
| `python pting/day06.py input-aspidites` | 58.9 ± 7.1 | 47.7 | 77.4 | 30.90 ± 15.94 |
| `python pting/day06.py input-kcen` | 49.1 ± 6.2 | 38.5 | 63.9 | 25.75 ± 13.32 |
| `python pting/day06.py input-lanjian` | 49.0 ± 5.5 | 41.2 | 64.1 | 25.71 ± 13.21 |
| `python pting/day06.py input-mattcl` | 60.1 ± 10.1 | 41.2 | 103.5 | 31.52 ± 16.67 |
| `python pting/day06.py input-pting` | 53.2 ± 6.8 | 41.7 | 72.1 | 27.88 ± 14.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
