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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.6 ± 4.3 | 13.3 | 56.7 | 10.94 ± 6.47 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 29.0 ± 17.9 | 14.7 | 203.8 | 12.40 ± 10.38 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.1 ± 1.6 | 23.0 | 35.3 | 10.72 ± 6.12 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.5 ± 5.3 | 13.1 | 35.7 | 10.06 ± 6.13 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.9 ± 8.1 | 23.4 | 83.3 | 11.50 ± 7.39 |
| `kcen/2022/06/solve input-aspidites` | 164.6 ± 14.4 | 143.4 | 199.1 | 70.30 ± 40.35 |
| `kcen/2022/06/solve input-kcen` | 191.8 ± 18.4 | 161.4 | 227.9 | 81.96 ± 47.15 |
| `kcen/2022/06/solve input-lanjian` | 170.2 ± 14.5 | 151.6 | 200.8 | 72.72 ± 41.71 |
| `kcen/2022/06/solve input-mattcl` | 239.6 ± 77.2 | 150.2 | 393.4 | 102.36 ± 66.76 |
| `kcen/2022/06/solve input-pting` | 185.5 ± 12.3 | 162.9 | 210.4 | 79.25 ± 45.26 |
| `lanjian/day_06 input-aspidites` | 2.8 ± 1.3 | 0.8 | 11.6 | 1.20 ± 0.87 |
| `lanjian/day_06 input-kcen` | 2.9 ± 5.9 | 0.9 | 81.9 | 1.23 ± 2.60 |
| `lanjian/day_06 input-lanjian` | 2.3 ± 1.3 | 0.7 | 19.0 | 1.00 |
| `lanjian/day_06 input-mattcl` | 2.5 ± 1.2 | 0.9 | 11.4 | 1.08 ± 0.78 |
| `lanjian/day_06 input-pting` | 3.1 ± 2.8 | 0.7 | 35.8 | 1.32 ± 1.40 |
| `mattcl-solver/aoc run 6 input-aspidites` | 3.3 ± 1.3 | 1.3 | 13.7 | 1.42 ± 0.97 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.8 ± 1.4 | 1.1 | 12.5 | 1.20 ± 0.89 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.0 ± 9.0 | 0.9 | 256.0 | 1.27 ± 3.93 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.0 ± 1.3 | 0.9 | 13.0 | 1.28 ± 0.92 |
| `mattcl-solver/aoc run 6 input-pting` | 2.8 ± 1.1 | 0.9 | 9.0 | 1.21 ± 0.84 |
| `python pting/day06.py input-aspidites` | 55.9 ± 5.7 | 48.3 | 73.7 | 23.87 ± 13.76 |
| `python pting/day06.py input-kcen` | 56.8 ± 8.6 | 42.3 | 75.0 | 24.26 ± 14.24 |
| `python pting/day06.py input-lanjian` | 57.1 ± 6.1 | 46.8 | 73.7 | 24.41 ± 14.09 |
| `python pting/day06.py input-mattcl` | 50.3 ± 4.1 | 43.7 | 60.5 | 21.50 ± 12.32 |
| `python pting/day06.py input-pting` | 57.7 ± 9.0 | 42.1 | 88.6 | 24.64 ± 14.49 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
