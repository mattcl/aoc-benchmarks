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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.6 ± 1.5 | 11.6 | 23.7 | 13.65 ± 4.26 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.2 ± 0.8 | 11.6 | 22.2 | 13.15 ± 3.89 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.7 ± 1.7 | 11.7 | 23.0 | 13.70 ± 4.38 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.7 ± 2.7 | 11.6 | 35.8 | 13.74 ± 4.95 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.0 ± 1.9 | 11.8 | 23.7 | 14.00 ± 4.53 |
| `kcen/2022/03/solve input-aspidites` | 249.9 ± 16.0 | 222.5 | 282.1 | 269.69 ± 79.81 |
| `kcen/2022/03/solve input-kcen` | 235.1 ± 12.3 | 217.2 | 255.4 | 253.76 ± 74.50 |
| `kcen/2022/03/solve input-lanjian` | 218.3 ± 12.2 | 202.9 | 239.3 | 235.58 ± 69.32 |
| `kcen/2022/03/solve input-mattcl` | 214.2 ± 7.2 | 202.9 | 223.9 | 231.19 ± 67.24 |
| `kcen/2022/03/solve input-pting` | 247.2 ± 16.7 | 227.1 | 287.3 | 266.76 ± 79.14 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.6 | 0.6 | 8.2 | 1.36 ± 0.78 |
| `lanjian/day_03 input-kcen` | 1.1 ± 0.5 | 0.6 | 8.3 | 1.21 ± 0.64 |
| `lanjian/day_03 input-lanjian` | 1.1 ± 0.4 | 0.6 | 3.8 | 1.22 ± 0.53 |
| `lanjian/day_03 input-mattcl` | 1.1 ± 0.7 | 0.5 | 16.3 | 1.21 ± 0.80 |
| `lanjian/day_03 input-pting` | 0.9 ± 0.3 | 0.6 | 2.8 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.3 ± 0.6 | 0.6 | 8.1 | 1.39 ± 0.75 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.3 ± 0.4 | 0.6 | 8.4 | 1.35 ± 0.61 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.2 ± 0.5 | 0.7 | 9.6 | 1.29 ± 0.69 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.3 ± 0.4 | 0.7 | 4.3 | 1.41 ± 0.59 |
| `mattcl-solver/aoc run 3 input-pting` | 1.2 ± 0.4 | 0.7 | 5.1 | 1.31 ± 0.57 |
| `python pting/day03.py input-aspidites` | 33.7 ± 3.7 | 29.7 | 52.9 | 36.38 ± 11.25 |
| `python pting/day03.py input-kcen` | 33.9 ± 3.9 | 29.2 | 45.2 | 36.54 ± 11.35 |
| `python pting/day03.py input-lanjian` | 35.8 ± 4.3 | 30.2 | 53.8 | 38.68 ± 12.12 |
| `python pting/day03.py input-mattcl` | 34.1 ± 3.7 | 29.8 | 44.8 | 36.75 ± 11.34 |
| `python pting/day03.py input-pting` | 34.8 ± 3.7 | 29.1 | 53.0 | 37.61 ± 11.59 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
