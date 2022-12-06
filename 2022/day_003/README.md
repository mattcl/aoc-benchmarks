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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 26.1 ± 2.2 | 23.6 | 39.2 | 11.29 ± 5.64 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.2 ± 3.0 | 13.6 | 29.3 | 10.87 ± 5.51 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 24.2 ± 3.4 | 13.7 | 36.0 | 10.44 ± 5.35 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.4 ± 3.8 | 12.9 | 44.7 | 10.97 ± 5.64 |
| `aspidites-solver/aoc -i input-pting -d 3` | 25.8 ± 3.2 | 13.1 | 37.2 | 11.16 ± 5.67 |
| `kcen/2022/03/solve input-aspidites` | 346.5 ± 19.9 | 322.4 | 390.0 | 149.63 ± 74.18 |
| `kcen/2022/03/solve input-kcen` | 378.6 ± 38.9 | 334.4 | 472.5 | 163.47 ± 82.23 |
| `kcen/2022/03/solve input-lanjian` | 371.5 ± 35.5 | 311.8 | 420.3 | 160.39 ± 80.46 |
| `kcen/2022/03/solve input-mattcl` | 366.6 ± 35.8 | 315.7 | 430.7 | 158.31 ± 79.48 |
| `kcen/2022/03/solve input-pting` | 351.3 ± 30.1 | 314.8 | 408.5 | 151.67 ± 75.81 |
| `lanjian/day_03 input-aspidites` | 2.4 ± 1.0 | 0.5 | 7.1 | 1.05 ± 0.68 |
| `lanjian/day_03 input-kcen` | 2.3 ± 1.1 | 0.6 | 13.9 | 1.00 |
| `lanjian/day_03 input-lanjian` | 2.3 ± 1.0 | 0.6 | 11.6 | 1.00 ± 0.66 |
| `lanjian/day_03 input-mattcl` | 2.7 ± 1.1 | 0.6 | 12.6 | 1.15 ± 0.74 |
| `lanjian/day_03 input-pting` | 3.1 ± 3.9 | 0.7 | 77.1 | 1.33 ± 1.83 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.6 ± 1.2 | 0.9 | 16.4 | 1.12 ± 0.76 |
| `mattcl-solver/aoc run 3 input-kcen` | 3.2 ± 2.3 | 0.7 | 23.3 | 1.36 ± 1.19 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.9 ± 1.5 | 1.1 | 19.2 | 1.25 ± 0.88 |
| `mattcl-solver/aoc run 3 input-mattcl` | 5.0 ± 5.7 | 0.9 | 42.9 | 2.17 ± 2.68 |
| `mattcl-solver/aoc run 3 input-pting` | 3.3 ± 1.3 | 1.0 | 12.0 | 1.43 ± 0.91 |
| `python pting/day03.py input-aspidites` | 60.1 ± 11.0 | 42.3 | 86.9 | 25.97 ± 13.64 |
| `python pting/day03.py input-kcen` | 60.0 ± 11.4 | 43.0 | 83.1 | 25.91 ± 13.68 |
| `python pting/day03.py input-lanjian` | 52.8 ± 8.1 | 43.9 | 81.8 | 22.80 ± 11.76 |
| `python pting/day03.py input-mattcl` | 54.0 ± 9.2 | 41.6 | 75.4 | 23.33 ± 12.16 |
| `python pting/day03.py input-pting` | 54.7 ± 9.5 | 42.8 | 85.4 | 23.62 ± 12.34 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
