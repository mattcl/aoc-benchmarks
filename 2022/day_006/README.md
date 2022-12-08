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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.8 ± 3.5 | 24.0 | 41.2 | 12.43 ± 6.55 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 26.7 ± 3.3 | 23.5 | 43.4 | 12.39 ± 6.51 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.5 ± 3.5 | 23.6 | 48.7 | 12.27 ± 6.48 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 25.1 ± 3.7 | 13.7 | 41.0 | 11.62 ± 6.18 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.9 ± 4.0 | 24.0 | 58.1 | 12.46 ± 6.63 |
| `kcen/2022/06/solve input-aspidites` | 202.0 ± 16.5 | 183.4 | 233.2 | 93.66 ± 48.44 |
| `kcen/2022/06/solve input-kcen` | 192.9 ± 24.2 | 158.0 | 236.1 | 89.41 ± 47.02 |
| `kcen/2022/06/solve input-lanjian` | 201.1 ± 31.1 | 165.2 | 248.0 | 93.20 ± 49.74 |
| `kcen/2022/06/solve input-mattcl` | 185.6 ± 23.0 | 155.3 | 219.8 | 86.05 ± 45.22 |
| `kcen/2022/06/solve input-pting` | 267.3 ± 66.4 | 196.0 | 387.7 | 123.92 ± 70.37 |
| `lanjian/day_06 input-aspidites` | 2.6 ± 1.2 | 0.4 | 11.3 | 1.18 ± 0.82 |
| `lanjian/day_06 input-kcen` | 2.2 ± 1.1 | 0.4 | 9.4 | 1.00 |
| `lanjian/day_06 input-lanjian` | 5.2 ± 5.6 | 0.7 | 36.0 | 2.40 ± 2.87 |
| `lanjian/day_06 input-mattcl` | 2.3 ± 1.8 | 0.4 | 27.7 | 1.08 ± 1.00 |
| `lanjian/day_06 input-pting` | 3.6 ± 3.4 | 0.4 | 47.3 | 1.66 ± 1.81 |
| `mattcl-solver/aoc run 6 input-aspidites` | 3.0 ± 1.5 | 0.6 | 13.7 | 1.37 ± 0.99 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.9 ± 1.6 | 0.9 | 17.2 | 1.34 ± 1.00 |
| `mattcl-solver/aoc run 6 input-lanjian` | 5.4 ± 5.9 | 1.3 | 59.3 | 2.49 ± 3.02 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.0 ± 1.7 | 0.7 | 21.1 | 1.38 ± 1.05 |
| `mattcl-solver/aoc run 6 input-pting` | 3.9 ± 2.9 | 1.0 | 23.8 | 1.83 ± 1.64 |
| `python pting/day06.py input-aspidites` | 60.7 ± 9.9 | 49.2 | 93.0 | 28.15 ± 15.09 |
| `python pting/day06.py input-kcen` | 56.6 ± 8.4 | 42.6 | 75.3 | 26.23 ± 13.94 |
| `python pting/day06.py input-lanjian` | 62.1 ± 8.7 | 40.2 | 87.5 | 28.77 ± 15.24 |
| `python pting/day06.py input-mattcl` | 63.7 ± 7.3 | 49.8 | 79.9 | 29.52 ± 15.45 |
| `python pting/day06.py input-pting` | 65.2 ± 15.1 | 47.7 | 118.4 | 30.24 ± 16.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
