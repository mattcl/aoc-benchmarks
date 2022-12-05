# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 3)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.0 ± 2.4 | 11.7 | 25.7 | 15.06 ± 4.79 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.0 ± 2.0 | 11.7 | 25.6 | 15.17 ± 4.53 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.6 ± 2.4 | 11.6 | 24.8 | 14.70 ± 4.67 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.5 ± 0.5 | 11.7 | 14.4 | 14.49 ± 3.75 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.7 ± 2.1 | 11.6 | 24.6 | 14.82 ± 4.53 |
| `kcen/2022/03/solve input-aspidites` | 240.5 ± 8.4 | 229.2 | 256.7 | 279.69 ± 72.28 |
| `kcen/2022/03/solve input-kcen` | 213.8 ± 9.4 | 202.2 | 232.2 | 248.58 ± 64.60 |
| `kcen/2022/03/solve input-lanjian` | 225.0 ± 13.9 | 205.7 | 248.1 | 261.70 ± 68.93 |
| `kcen/2022/03/solve input-mattcl` | 240.7 ± 16.1 | 211.8 | 269.8 | 279.90 ± 74.07 |
| `kcen/2022/03/solve input-pting` | 226.5 ± 16.5 | 209.6 | 271.8 | 263.38 ± 70.13 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.5 | 0.6 | 6.2 | 1.48 ± 0.69 |
| `lanjian/day_03 input-kcen` | 0.9 ± 0.2 | 0.5 | 2.6 | 1.00 |
| `lanjian/day_03 input-lanjian` | 1.0 ± 0.5 | 0.6 | 5.4 | 1.22 ± 0.68 |
| `lanjian/day_03 input-mattcl` | 1.3 ± 0.7 | 0.5 | 5.7 | 1.56 ± 0.87 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.5 | 0.5 | 7.5 | 1.42 ± 0.66 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.4 ± 0.4 | 0.7 | 7.6 | 1.61 ± 0.64 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.0 ± 0.4 | 0.6 | 7.3 | 1.13 ± 0.51 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.2 ± 0.5 | 0.6 | 8.6 | 1.42 ± 0.67 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.5 ± 0.7 | 0.7 | 8.7 | 1.77 ± 0.94 |
| `mattcl-solver/aoc run 3 input-pting` | 1.5 ± 0.7 | 0.7 | 12.1 | 1.70 ± 0.94 |
| `python pting/day03.py input-aspidites` | 33.4 ± 3.4 | 27.9 | 45.9 | 38.87 ± 10.72 |
| `python pting/day03.py input-kcen` | 30.4 ± 2.4 | 27.5 | 40.8 | 35.38 ± 9.48 |
| `python pting/day03.py input-lanjian` | 32.3 ± 3.6 | 28.2 | 43.6 | 37.53 ± 10.49 |
| `python pting/day03.py input-mattcl` | 33.3 ± 3.1 | 29.3 | 44.8 | 38.75 ± 10.57 |
| `python pting/day03.py input-pting` | 34.7 ± 4.1 | 29.2 | 47.8 | 40.37 ± 11.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
