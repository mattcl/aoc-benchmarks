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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.9 ± 1.5 | 11.8 | 23.4 | 12.74 ± 4.24 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.8 ± 1.8 | 11.7 | 24.0 | 12.72 ± 4.35 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.0 ± 3.0 | 11.5 | 33.9 | 12.91 ± 4.99 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.9 ± 1.6 | 11.8 | 25.6 | 12.74 ± 4.28 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.6 ± 1.5 | 11.6 | 23.0 | 12.51 ± 4.20 |
| `kcen/2022/03/solve input-aspidites` | 254.3 ± 21.1 | 237.4 | 302.0 | 251.88 ± 81.59 |
| `kcen/2022/03/solve input-kcen` | 237.4 ± 14.6 | 210.3 | 250.7 | 235.19 ± 75.06 |
| `kcen/2022/03/solve input-lanjian` | 211.7 ± 6.3 | 201.7 | 223.6 | 209.74 ± 65.97 |
| `kcen/2022/03/solve input-mattcl` | 252.2 ± 26.8 | 213.4 | 305.3 | 249.82 ± 82.60 |
| `kcen/2022/03/solve input-pting` | 232.0 ± 13.3 | 209.7 | 251.5 | 229.82 ± 73.16 |
| `lanjian/day_03 input-aspidites` | 1.1 ± 0.4 | 0.6 | 7.0 | 1.07 ± 0.50 |
| `lanjian/day_03 input-kcen` | 1.0 ± 0.3 | 0.6 | 3.8 | 1.01 ± 0.46 |
| `lanjian/day_03 input-lanjian` | 1.0 ± 0.3 | 0.6 | 4.3 | 1.00 |
| `lanjian/day_03 input-mattcl` | 1.1 ± 0.5 | 0.6 | 4.6 | 1.08 ± 0.60 |
| `lanjian/day_03 input-pting` | 1.4 ± 0.8 | 0.6 | 11.2 | 1.42 ± 0.89 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.2 ± 0.4 | 0.7 | 3.6 | 1.22 ± 0.52 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.0 ± 0.3 | 0.6 | 2.7 | 1.01 ± 0.46 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.7 | 0.7 | 9.5 | 1.39 ± 0.79 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.6 ± 0.7 | 0.7 | 7.6 | 1.55 ± 0.83 |
| `mattcl-solver/aoc run 3 input-pting` | 1.6 ± 0.8 | 0.7 | 10.6 | 1.62 ± 0.96 |
| `python pting/day03.py input-aspidites` | 36.0 ± 4.7 | 28.9 | 57.7 | 35.62 ± 12.10 |
| `python pting/day03.py input-kcen` | 34.5 ± 3.6 | 30.0 | 51.2 | 34.14 ± 11.28 |
| `python pting/day03.py input-lanjian` | 34.6 ± 3.8 | 29.2 | 44.3 | 34.23 ± 11.37 |
| `python pting/day03.py input-mattcl` | 33.3 ± 3.3 | 29.5 | 48.6 | 32.95 ± 10.82 |
| `python pting/day03.py input-pting` | 35.2 ± 2.6 | 30.6 | 41.4 | 34.91 ± 11.23 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
