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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 25.0 ± 4.3 | 12.7 | 54.7 | 16.71 ± 11.52 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 24.3 ± 3.5 | 12.7 | 30.7 | 16.20 ± 11.07 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 22.8 ± 5.2 | 12.5 | 34.5 | 15.21 ± 10.74 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 20.4 ± 6.2 | 11.8 | 30.8 | 13.59 ± 9.97 |
| `aspidites-solver/aoc -i input-pting -d 3` | 25.8 ± 3.8 | 14.6 | 55.7 | 17.24 ± 11.80 |
| `kcen/2022/03/solve input-aspidites` | 349.6 ± 30.1 | 306.4 | 411.0 | 233.31 ± 157.09 |
| `kcen/2022/03/solve input-kcen` | 482.7 ± 153.2 | 358.5 | 777.2 | 322.11 ± 238.17 |
| `kcen/2022/03/solve input-lanjian` | 341.1 ± 33.5 | 294.0 | 405.7 | 227.66 ± 153.66 |
| `kcen/2022/03/solve input-mattcl` | 375.3 ± 31.3 | 329.3 | 434.4 | 250.44 ± 168.54 |
| `kcen/2022/03/solve input-pting` | 383.3 ± 35.0 | 321.2 | 433.9 | 255.82 ± 172.42 |
| `lanjian/day_03 input-aspidites` | 1.5 ± 1.0 | 0.0 | 7.8 | 1.00 |
| `lanjian/day_03 input-kcen` | 1.9 ± 1.2 | 0.0 | 10.0 | 1.26 ± 1.16 |
| `lanjian/day_03 input-lanjian` | 2.1 ± 1.3 | 0.0 | 7.4 | 1.40 ± 1.28 |
| `lanjian/day_03 input-mattcl` | 1.8 ± 1.4 | 0.0 | 16.2 | 1.22 ± 1.25 |
| `lanjian/day_03 input-pting` | 2.4 ± 1.3 | 0.2 | 9.7 | 1.60 ± 1.36 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.5 ± 1.1 | 0.0 | 5.9 | 1.02 ± 1.01 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.8 ± 1.3 | 0.3 | 11.2 | 1.90 ± 1.52 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.5 ± 1.6 | 0.2 | 11.5 | 1.69 ± 1.56 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.6 ± 1.2 | 0.0 | 10.3 | 1.04 ± 1.08 |
| `mattcl-solver/aoc run 3 input-pting` | 2.1 ± 1.2 | 0.2 | 6.5 | 1.39 ± 1.24 |
| `python pting/day03.py input-aspidites` | 46.2 ± 7.6 | 33.7 | 62.4 | 30.81 ± 21.19 |
| `python pting/day03.py input-kcen` | 58.1 ± 8.9 | 41.8 | 88.2 | 38.76 ± 26.56 |
| `python pting/day03.py input-lanjian` | 49.1 ± 8.8 | 38.0 | 88.8 | 32.74 ± 22.65 |
| `python pting/day03.py input-mattcl` | 87.9 ± 67.2 | 36.4 | 337.9 | 58.64 ± 59.56 |
| `python pting/day03.py input-pting` | 55.9 ± 8.3 | 44.0 | 76.4 | 37.31 ± 25.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
