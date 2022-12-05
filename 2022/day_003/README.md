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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.4 ± 1.3 | 11.6 | 24.4 | 11.07 ± 4.52 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.6 ± 2.1 | 11.5 | 26.5 | 11.25 ± 4.81 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.5 ± 1.4 | 11.7 | 22.8 | 11.17 ± 4.57 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.3 ± 0.5 | 11.7 | 16.8 | 11.02 ± 4.36 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.7 ± 1.7 | 11.7 | 23.2 | 11.31 ± 4.70 |
| `kcen/2022/03/solve input-aspidites` | 209.6 ± 7.9 | 200.0 | 226.3 | 187.13 ± 74.00 |
| `kcen/2022/03/solve input-kcen` | 225.4 ± 22.2 | 197.8 | 281.5 | 201.26 ± 81.67 |
| `kcen/2022/03/solve input-lanjian` | 227.3 ± 17.2 | 205.8 | 269.2 | 202.95 ± 81.36 |
| `kcen/2022/03/solve input-mattcl` | 237.4 ± 10.2 | 215.4 | 255.5 | 211.96 ± 83.93 |
| `kcen/2022/03/solve input-pting` | 249.5 ± 25.0 | 213.8 | 292.8 | 222.79 ± 90.49 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.5 | 0.7 | 8.7 | 1.15 ± 0.66 |
| `lanjian/day_03 input-kcen` | 1.2 ± 0.4 | 0.7 | 6.4 | 1.05 ± 0.54 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.4 | 0.7 | 10.8 | 1.05 ± 0.57 |
| `lanjian/day_03 input-mattcl` | 1.4 ± 0.4 | 0.7 | 6.5 | 1.21 ± 0.59 |
| `lanjian/day_03 input-pting` | 1.1 ± 0.4 | 0.6 | 9.8 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.4 ± 0.7 | 0.6 | 7.5 | 1.24 ± 0.76 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.3 ± 0.3 | 0.8 | 3.8 | 1.12 ± 0.52 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.6 | 0.8 | 9.6 | 1.24 ± 0.71 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.3 ± 0.4 | 0.6 | 4.3 | 1.16 ± 0.57 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.3 | 0.7 | 3.5 | 1.19 ± 0.55 |
| `python pting/day03.py input-aspidites` | 33.2 ± 4.4 | 27.5 | 50.2 | 29.63 ± 12.30 |
| `python pting/day03.py input-kcen` | 34.6 ± 4.2 | 28.9 | 48.0 | 30.88 ± 12.73 |
| `python pting/day03.py input-lanjian` | 32.0 ± 2.9 | 28.4 | 48.9 | 28.59 ± 11.56 |
| `python pting/day03.py input-mattcl` | 35.4 ± 5.1 | 28.2 | 52.2 | 31.57 ± 13.22 |
| `python pting/day03.py input-pting` | 32.0 ± 3.7 | 27.2 | 48.4 | 28.53 ± 11.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
