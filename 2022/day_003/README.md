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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 25.2 ± 2.8 | 12.9 | 37.9 | 11.31 ± 5.13 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.8 ± 1.9 | 23.7 | 38.1 | 11.56 ± 5.15 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 25.5 ± 3.1 | 13.5 | 47.2 | 11.40 ± 5.20 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.0 ± 1.7 | 14.8 | 30.0 | 11.19 ± 4.98 |
| `aspidites-solver/aoc -i input-pting -d 3` | 25.8 ± 1.8 | 23.6 | 39.7 | 11.54 ± 5.13 |
| `kcen/2022/03/solve input-aspidites` | 403.4 ± 29.0 | 356.1 | 444.9 | 180.68 ± 80.49 |
| `kcen/2022/03/solve input-kcen` | 426.9 ± 44.4 | 371.3 | 492.7 | 191.19 ± 86.38 |
| `kcen/2022/03/solve input-lanjian` | 407.3 ± 25.6 | 371.1 | 447.3 | 182.41 ± 81.00 |
| `kcen/2022/03/solve input-mattcl` | 393.8 ± 35.1 | 325.6 | 453.4 | 176.35 ± 79.10 |
| `kcen/2022/03/solve input-pting` | 395.9 ± 39.4 | 356.2 | 459.0 | 177.29 ± 79.91 |
| `lanjian/day_03 input-aspidites` | 2.2 ± 1.0 | 0.7 | 14.1 | 1.00 |
| `lanjian/day_03 input-kcen` | 2.5 ± 1.3 | 0.6 | 14.6 | 1.11 ± 0.75 |
| `lanjian/day_03 input-lanjian` | 2.5 ± 1.2 | 0.8 | 15.1 | 1.11 ± 0.73 |
| `lanjian/day_03 input-mattcl` | 2.4 ± 1.2 | 0.7 | 15.8 | 1.06 ± 0.71 |
| `lanjian/day_03 input-pting` | 2.4 ± 1.0 | 0.8 | 10.0 | 1.10 ± 0.65 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.4 ± 0.9 | 1.0 | 9.2 | 1.10 ± 0.64 |
| `mattcl-solver/aoc run 3 input-kcen` | 3.0 ± 1.4 | 1.0 | 11.6 | 1.33 ± 0.84 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.5 ± 1.8 | 1.1 | 22.7 | 1.58 ± 1.07 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.2 ± 1.4 | 1.0 | 19.6 | 1.44 ± 0.89 |
| `mattcl-solver/aoc run 3 input-pting` | 2.7 ± 1.1 | 0.9 | 11.0 | 1.21 ± 0.74 |
| `python pting/day03.py input-aspidites` | 55.3 ± 6.9 | 44.5 | 74.6 | 24.78 ± 11.33 |
| `python pting/day03.py input-kcen` | 71.3 ± 17.9 | 43.7 | 117.9 | 31.95 ± 16.17 |
| `python pting/day03.py input-lanjian` | 62.9 ± 9.4 | 44.2 | 82.6 | 28.19 ± 13.08 |
| `python pting/day03.py input-mattcl` | 60.4 ± 20.9 | 42.0 | 125.9 | 27.06 ± 15.13 |
| `python pting/day03.py input-pting` | 60.4 ± 9.2 | 46.9 | 93.6 | 27.04 ± 12.58 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
