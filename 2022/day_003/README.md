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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 24.4 ± 3.5 | 12.6 | 36.0 | 13.91 ± 9.45 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 23.6 ± 4.0 | 12.8 | 29.1 | 13.46 ± 9.23 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 29.0 ± 5.6 | 23.9 | 47.6 | 16.57 ± 11.46 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 21.7 ± 5.6 | 12.6 | 38.5 | 12.41 ± 8.84 |
| `aspidites-solver/aoc -i input-pting -d 3` | 24.9 ± 2.9 | 13.1 | 33.1 | 14.20 ± 9.57 |
| `kcen/2022/03/solve input-aspidites` | 446.7 ± 111.2 | 336.7 | 641.2 | 255.13 ± 180.84 |
| `kcen/2022/03/solve input-kcen` | 403.6 ± 26.7 | 367.7 | 446.9 | 230.54 ± 153.76 |
| `kcen/2022/03/solve input-lanjian` | 399.7 ± 42.6 | 343.7 | 469.2 | 228.28 ± 153.45 |
| `kcen/2022/03/solve input-mattcl` | 372.9 ± 31.2 | 332.3 | 434.4 | 212.98 ± 142.47 |
| `kcen/2022/03/solve input-pting` | 390.8 ± 18.1 | 368.5 | 433.0 | 223.24 ± 148.52 |
| `lanjian/day_03 input-aspidites` | 1.8 ± 1.2 | 0.0 | 10.9 | 1.00 |
| `lanjian/day_03 input-kcen` | 2.3 ± 6.0 | 0.2 | 145.1 | 1.31 ± 3.55 |
| `lanjian/day_03 input-lanjian` | 2.2 ± 1.6 | 0.3 | 14.0 | 1.28 ± 1.23 |
| `lanjian/day_03 input-mattcl` | 2.4 ± 1.1 | 0.5 | 10.9 | 1.38 ± 1.10 |
| `lanjian/day_03 input-pting` | 2.8 ± 1.1 | 0.5 | 7.5 | 1.58 ± 1.22 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.4 ± 1.1 | 0.4 | 8.3 | 1.38 ± 1.11 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.5 ± 1.2 | 0.5 | 9.4 | 1.41 ± 1.16 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.9 ± 1.2 | 0.5 | 13.1 | 1.65 ± 1.30 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.7 ± 1.1 | 0.6 | 11.7 | 1.55 ± 1.22 |
| `mattcl-solver/aoc run 3 input-pting` | 2.8 ± 1.2 | 0.7 | 12.2 | 1.60 ± 1.26 |
| `python pting/day03.py input-aspidites` | 54.3 ± 8.4 | 43.7 | 84.4 | 31.01 ± 21.14 |
| `python pting/day03.py input-kcen` | 54.1 ± 6.7 | 42.2 | 83.4 | 30.92 ± 20.87 |
| `python pting/day03.py input-lanjian` | 59.5 ± 11.0 | 41.1 | 93.9 | 33.99 ± 23.41 |
| `python pting/day03.py input-mattcl` | 55.3 ± 9.1 | 41.2 | 80.4 | 31.62 ± 21.61 |
| `python pting/day03.py input-pting` | 55.0 ± 8.4 | 43.6 | 75.2 | 31.43 ± 21.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
