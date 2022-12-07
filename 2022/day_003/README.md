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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 25.6 ± 3.2 | 13.8 | 39.0 | 10.56 ± 5.24 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.1 ± 4.1 | 13.2 | 39.2 | 10.36 ± 5.24 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 25.9 ± 3.6 | 14.1 | 47.9 | 10.68 ± 5.33 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.5 ± 2.9 | 13.5 | 31.1 | 10.54 ± 5.20 |
| `aspidites-solver/aoc -i input-pting -d 3` | 25.7 ± 2.9 | 14.7 | 36.0 | 10.63 ± 5.24 |
| `kcen/2022/03/solve input-aspidites` | 360.1 ± 40.1 | 314.7 | 434.6 | 148.72 ± 73.22 |
| `kcen/2022/03/solve input-kcen` | 370.9 ± 27.2 | 345.5 | 434.1 | 153.19 ± 74.32 |
| `kcen/2022/03/solve input-lanjian` | 380.5 ± 23.5 | 336.7 | 407.5 | 157.17 ± 75.99 |
| `kcen/2022/03/solve input-mattcl` | 367.9 ± 28.0 | 321.5 | 413.6 | 151.94 ± 73.77 |
| `kcen/2022/03/solve input-pting` | 387.5 ± 35.3 | 338.0 | 432.8 | 160.03 ± 78.11 |
| `lanjian/day_03 input-aspidites` | 2.6 ± 1.3 | 0.7 | 9.3 | 1.07 ± 0.73 |
| `lanjian/day_03 input-kcen` | 2.8 ± 1.6 | 0.8 | 15.4 | 1.15 ± 0.86 |
| `lanjian/day_03 input-lanjian` | 3.0 ± 1.5 | 0.9 | 15.5 | 1.25 ± 0.86 |
| `lanjian/day_03 input-mattcl` | 2.8 ± 1.3 | 0.5 | 18.0 | 1.15 ± 0.78 |
| `lanjian/day_03 input-pting` | 2.4 ± 1.2 | 0.9 | 9.8 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.5 ± 1.7 | 0.8 | 17.0 | 1.43 ± 0.98 |
| `mattcl-solver/aoc run 3 input-kcen` | 5.4 ± 5.1 | 0.8 | 40.0 | 2.25 ± 2.38 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.9 ± 1.5 | 0.9 | 15.2 | 1.20 ± 0.86 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.4 ± 2.5 | 0.7 | 48.6 | 1.39 ± 1.24 |
| `mattcl-solver/aoc run 3 input-pting` | 2.7 ± 1.0 | 1.0 | 6.5 | 1.10 ± 0.67 |
| `python pting/day03.py input-aspidites` | 55.4 ± 6.3 | 45.4 | 71.7 | 22.88 ± 11.27 |
| `python pting/day03.py input-kcen` | 57.4 ± 7.8 | 44.8 | 80.7 | 23.69 ± 11.81 |
| `python pting/day03.py input-lanjian` | 59.7 ± 11.8 | 45.8 | 106.2 | 24.66 ± 12.79 |
| `python pting/day03.py input-mattcl` | 56.6 ± 10.1 | 41.8 | 85.2 | 23.38 ± 11.96 |
| `python pting/day03.py input-pting` | 58.7 ± 10.9 | 44.1 | 99.7 | 24.26 ± 12.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
