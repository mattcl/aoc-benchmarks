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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 51.8 ± 39.8 | 23.4 | 205.1 | 19.13 ± 21.62 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 22.4 ± 6.2 | 12.2 | 39.5 | 8.27 ± 7.23 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 27.5 ± 3.5 | 24.2 | 41.7 | 10.14 ± 8.51 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.8 ± 3.7 | 14.0 | 40.6 | 9.54 ± 8.03 |
| `aspidites-solver/aoc -i input-pting -d 3` | 24.0 ± 6.2 | 12.4 | 49.2 | 8.86 ± 7.70 |
| `kcen/2022/03/solve input-aspidites` | 391.6 ± 61.4 | 327.0 | 522.7 | 144.55 ± 122.04 |
| `kcen/2022/03/solve input-kcen` | 397.3 ± 75.2 | 315.9 | 572.5 | 146.65 ± 124.79 |
| `kcen/2022/03/solve input-lanjian` | 463.6 ± 105.7 | 350.4 | 685.3 | 171.14 ± 147.24 |
| `kcen/2022/03/solve input-mattcl` | 405.2 ± 61.4 | 329.2 | 511.4 | 149.59 ± 126.16 |
| `kcen/2022/03/solve input-pting` | 416.6 ± 88.2 | 302.3 | 537.5 | 153.80 ± 131.69 |
| `lanjian/day_03 input-aspidites` | 2.9 ± 2.1 | 0.0 | 20.4 | 1.08 ± 1.17 |
| `lanjian/day_03 input-kcen` | 2.8 ± 1.8 | 0.0 | 13.3 | 1.02 ± 1.08 |
| `lanjian/day_03 input-lanjian` | 5.3 ± 8.2 | 0.4 | 100.9 | 1.97 ± 3.45 |
| `lanjian/day_03 input-mattcl` | 2.9 ± 1.9 | 0.2 | 26.8 | 1.09 ± 1.15 |
| `lanjian/day_03 input-pting` | 2.7 ± 2.3 | 0.0 | 20.4 | 1.01 ± 1.18 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.0 ± 1.7 | 0.0 | 11.7 | 1.10 ± 1.11 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.8 ± 2.0 | 0.2 | 15.6 | 1.05 ± 1.15 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.7 ± 2.2 | 0.0 | 24.1 | 1.00 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.3 ± 1.5 | 0.5 | 13.7 | 1.21 ± 1.15 |
| `mattcl-solver/aoc run 3 input-pting` | 3.1 ± 1.4 | 0.3 | 8.5 | 1.13 ± 1.08 |
| `python pting/day03.py input-aspidites` | 61.5 ± 24.4 | 41.8 | 143.8 | 22.70 ± 20.88 |
| `python pting/day03.py input-kcen` | 63.7 ± 25.3 | 41.0 | 140.0 | 23.50 ± 21.62 |
| `python pting/day03.py input-lanjian` | 51.8 ± 11.3 | 39.2 | 87.5 | 19.11 ± 16.39 |
| `python pting/day03.py input-mattcl` | 66.7 ± 23.5 | 44.2 | 141.4 | 24.62 ± 22.20 |
| `python pting/day03.py input-pting` | 54.4 ± 19.0 | 38.9 | 130.6 | 20.07 ± 18.07 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
