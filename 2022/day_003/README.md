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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 25.0 ± 2.4 | 22.7 | 39.8 | 11.16 ± 6.34 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 38.8 ± 19.3 | 23.4 | 107.4 | 17.35 ± 12.97 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 24.8 ± 3.8 | 12.7 | 46.6 | 11.08 ± 6.43 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.0 ± 3.6 | 13.1 | 38.9 | 11.19 ± 6.46 |
| `aspidites-solver/aoc -i input-pting -d 3` | 26.9 ± 4.6 | 23.1 | 46.7 | 12.04 ± 7.05 |
| `kcen/2022/03/solve input-aspidites` | 448.4 ± 30.5 | 389.3 | 489.5 | 200.39 ± 112.99 |
| `kcen/2022/03/solve input-kcen` | 430.8 ± 37.7 | 389.0 | 505.7 | 192.50 ± 109.06 |
| `kcen/2022/03/solve input-lanjian` | 413.3 ± 43.7 | 357.6 | 498.1 | 184.69 ± 105.20 |
| `kcen/2022/03/solve input-mattcl` | 432.2 ± 70.3 | 347.5 | 571.4 | 193.14 ± 112.57 |
| `kcen/2022/03/solve input-pting` | 452.5 ± 81.6 | 385.1 | 672.0 | 202.24 ± 118.93 |
| `lanjian/day_03 input-aspidites` | 3.3 ± 2.8 | 0.8 | 32.7 | 1.49 ± 1.52 |
| `lanjian/day_03 input-kcen` | 2.2 ± 1.3 | 0.2 | 15.1 | 1.00 |
| `lanjian/day_03 input-lanjian` | 2.5 ± 1.4 | 0.1 | 13.9 | 1.10 ± 0.89 |
| `lanjian/day_03 input-mattcl` | 2.3 ± 1.5 | 0.0 | 23.5 | 1.02 ± 0.89 |
| `lanjian/day_03 input-pting` | 2.3 ± 1.1 | 0.3 | 13.9 | 1.03 ± 0.77 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.7 ± 1.7 | 0.4 | 17.5 | 1.21 ± 1.01 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.5 ± 1.1 | 0.3 | 9.4 | 1.11 ± 0.78 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.2 ± 1.8 | 0.7 | 22.2 | 1.43 ± 1.14 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.6 ± 1.6 | 0.4 | 15.9 | 1.16 ± 0.98 |
| `mattcl-solver/aoc run 3 input-pting` | 2.9 ± 1.5 | 0.2 | 16.0 | 1.28 ± 0.97 |
| `python pting/day03.py input-aspidites` | 80.6 ± 12.4 | 64.8 | 123.8 | 36.00 ± 20.90 |
| `python pting/day03.py input-kcen` | 68.7 ± 14.6 | 50.4 | 139.7 | 30.72 ± 18.39 |
| `python pting/day03.py input-lanjian` | 61.9 ± 10.7 | 43.3 | 89.7 | 27.65 ± 16.20 |
| `python pting/day03.py input-mattcl` | 60.8 ± 10.7 | 45.0 | 107.8 | 27.19 ± 15.95 |
| `python pting/day03.py input-pting` | 61.4 ± 9.2 | 48.0 | 89.2 | 27.43 ± 15.90 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
