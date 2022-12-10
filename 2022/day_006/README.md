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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 24.8 ± 1.9 | 13.7 | 35.0 | 14.08 ± 5.98 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 34.0 ± 14.9 | 12.5 | 107.9 | 19.27 ± 11.70 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 24.8 ± 2.6 | 13.0 | 36.1 | 14.06 ± 6.06 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 22.4 ± 5.4 | 13.1 | 35.5 | 12.74 ± 6.15 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.1 ± 2.4 | 23.3 | 44.7 | 14.26 ± 6.11 |
| `kcen/2022/06/solve input-aspidites` | 178.9 ± 19.3 | 147.8 | 216.6 | 101.49 ± 43.84 |
| `kcen/2022/06/solve input-kcen` | 176.2 ± 18.4 | 147.4 | 215.9 | 99.99 ± 43.11 |
| `kcen/2022/06/solve input-lanjian` | 167.7 ± 12.0 | 143.1 | 191.0 | 95.19 ± 40.39 |
| `kcen/2022/06/solve input-mattcl` | 179.1 ± 20.3 | 151.8 | 212.6 | 101.63 ± 44.04 |
| `kcen/2022/06/solve input-pting` | 153.5 ± 11.6 | 140.4 | 179.7 | 87.13 ± 37.04 |
| `lanjian/day_06 input-aspidites` | 2.0 ± 1.2 | 0.6 | 18.3 | 1.14 ± 0.83 |
| `lanjian/day_06 input-kcen` | 2.4 ± 1.1 | 0.7 | 14.8 | 1.36 ± 0.84 |
| `lanjian/day_06 input-lanjian` | 2.2 ± 0.9 | 0.9 | 7.2 | 1.25 ± 0.74 |
| `lanjian/day_06 input-mattcl` | 1.8 ± 0.7 | 0.4 | 9.2 | 1.00 |
| `lanjian/day_06 input-pting` | 2.0 ± 0.9 | 0.6 | 7.3 | 1.14 ± 0.72 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.4 ± 1.1 | 0.9 | 14.7 | 1.36 ± 0.85 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.5 ± 1.2 | 0.8 | 14.3 | 1.42 ± 0.90 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.9 ± 1.1 | 1.2 | 14.1 | 1.65 ± 0.94 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.4 ± 0.8 | 0.9 | 9.5 | 1.35 ± 0.74 |
| `mattcl-solver/aoc run 6 input-pting` | 2.3 ± 1.0 | 0.9 | 11.6 | 1.29 ± 0.80 |
| `python pting/day06.py input-aspidites` | 54.9 ± 7.4 | 41.7 | 81.4 | 31.14 ± 13.69 |
| `python pting/day06.py input-kcen` | 54.8 ± 8.5 | 42.5 | 83.9 | 31.11 ± 13.87 |
| `python pting/day06.py input-lanjian` | 54.9 ± 7.8 | 40.6 | 75.1 | 31.17 ± 13.77 |
| `python pting/day06.py input-mattcl` | 72.9 ± 32.3 | 43.2 | 176.6 | 41.37 ± 25.21 |
| `python pting/day06.py input-pting` | 56.1 ± 7.1 | 43.0 | 76.1 | 31.81 ± 13.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
