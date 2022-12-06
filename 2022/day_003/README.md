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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 24.5 ± 1.6 | 12.5 | 29.4 | 16.45 ± 14.52 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.2 ± 3.7 | 12.9 | 47.1 | 16.94 ± 15.11 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 27.9 ± 10.0 | 23.2 | 90.3 | 18.74 ± 17.79 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 24.7 ± 3.6 | 12.2 | 37.2 | 16.60 ± 14.81 |
| `aspidites-solver/aoc -i input-pting -d 3` | 25.0 ± 2.0 | 22.9 | 37.5 | 16.76 ± 14.81 |
| `kcen/2022/03/solve input-aspidites` | 400.3 ± 34.2 | 348.0 | 458.9 | 268.64 ± 237.52 |
| `kcen/2022/03/solve input-kcen` | 390.2 ± 30.1 | 338.3 | 426.9 | 261.85 ± 231.31 |
| `kcen/2022/03/solve input-lanjian` | 474.8 ± 102.8 | 404.7 | 697.5 | 318.59 ± 288.73 |
| `kcen/2022/03/solve input-mattcl` | 418.1 ± 24.2 | 381.2 | 448.2 | 280.60 ± 247.46 |
| `kcen/2022/03/solve input-pting` | 423.1 ± 32.6 | 380.0 | 490.9 | 283.91 ± 250.80 |
| `lanjian/day_03 input-aspidites` | 1.5 ± 1.3 | 0.0 | 15.7 | 1.00 |
| `lanjian/day_03 input-kcen` | 1.8 ± 1.5 | 0.0 | 18.8 | 1.22 ± 1.49 |
| `lanjian/day_03 input-lanjian` | 1.9 ± 1.3 | 0.0 | 11.0 | 1.31 ± 1.43 |
| `lanjian/day_03 input-mattcl` | 2.0 ± 2.0 | 0.0 | 25.6 | 1.33 ± 1.77 |
| `lanjian/day_03 input-pting` | 1.8 ± 1.3 | 0.0 | 14.2 | 1.23 ± 1.40 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.7 ± 1.2 | 0.1 | 8.0 | 1.12 ± 1.25 |
| `mattcl-solver/aoc run 3 input-kcen` | 3.6 ± 4.4 | 0.1 | 36.7 | 2.40 ± 3.61 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.1 ± 1.3 | 0.2 | 9.4 | 1.43 ± 1.54 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.1 ± 1.3 | 0.2 | 12.6 | 1.41 ± 1.52 |
| `mattcl-solver/aoc run 3 input-pting` | 2.1 ± 1.2 | 0.0 | 9.4 | 1.41 ± 1.49 |
| `python pting/day03.py input-aspidites` | 57.0 ± 5.9 | 43.2 | 75.1 | 38.26 ± 33.91 |
| `python pting/day03.py input-kcen` | 59.9 ± 8.6 | 45.5 | 78.6 | 40.16 ± 35.81 |
| `python pting/day03.py input-lanjian` | 61.5 ± 7.7 | 49.0 | 85.5 | 41.29 ± 36.71 |
| `python pting/day03.py input-mattcl` | 65.5 ± 13.6 | 48.8 | 105.5 | 43.97 ± 39.75 |
| `python pting/day03.py input-pting` | 56.6 ± 6.5 | 45.2 | 79.9 | 38.01 ± 33.73 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
