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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 19.3 ± 5.6 | 12.5 | 27.7 | 16.04 ± 10.37 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 23.2 ± 4.2 | 12.8 | 29.6 | 19.26 ± 11.64 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 19.3 ± 5.9 | 12.7 | 39.3 | 16.02 ± 10.47 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 23.2 ± 4.9 | 12.7 | 35.3 | 19.28 ± 11.85 |
| `aspidites-solver/aoc -i input-pting -d 3` | 19.9 ± 5.5 | 12.5 | 28.1 | 16.54 ± 10.56 |
| `kcen/2022/03/solve input-aspidites` | 329.2 ± 24.8 | 298.1 | 370.3 | 273.64 ± 159.07 |
| `kcen/2022/03/solve input-kcen` | 332.3 ± 13.9 | 317.5 | 362.7 | 276.26 ± 159.64 |
| `kcen/2022/03/solve input-lanjian` | 325.2 ± 30.7 | 293.6 | 399.1 | 270.35 ± 157.90 |
| `kcen/2022/03/solve input-mattcl` | 336.6 ± 31.3 | 282.7 | 384.1 | 279.77 ± 163.34 |
| `kcen/2022/03/solve input-pting` | 311.9 ± 14.4 | 289.2 | 336.2 | 259.24 ± 149.90 |
| `lanjian/day_03 input-aspidites` | 1.2 ± 0.7 | 0.4 | 5.7 | 1.00 |
| `lanjian/day_03 input-kcen` | 1.6 ± 0.8 | 0.5 | 5.6 | 1.32 ± 0.99 |
| `lanjian/day_03 input-lanjian` | 1.4 ± 0.9 | 0.3 | 8.0 | 1.19 ± 1.01 |
| `lanjian/day_03 input-mattcl` | 2.5 ± 1.4 | 0.5 | 10.5 | 2.09 ± 1.67 |
| `lanjian/day_03 input-pting` | 1.7 ± 1.0 | 0.4 | 10.8 | 1.44 ± 1.18 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.6 ± 2.5 | 0.6 | 18.3 | 3.00 ± 2.70 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.8 ± 1.0 | 0.5 | 13.8 | 1.49 ± 1.18 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.4 ± 1.0 | 0.6 | 7.7 | 1.99 ± 1.43 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.0 ± 1.0 | 0.5 | 9.6 | 1.65 ± 1.28 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.8 | 0.3 | 8.1 | 1.06 ± 0.89 |
| `python pting/day03.py input-aspidites` | 43.5 ± 5.4 | 35.1 | 64.9 | 36.13 ± 21.30 |
| `python pting/day03.py input-kcen` | 47.6 ± 5.0 | 38.3 | 61.5 | 39.54 ± 23.16 |
| `python pting/day03.py input-lanjian` | 49.8 ± 6.5 | 40.1 | 70.4 | 41.36 ± 24.44 |
| `python pting/day03.py input-mattcl` | 49.9 ± 8.6 | 38.6 | 82.9 | 41.46 ± 24.94 |
| `python pting/day03.py input-pting` | 49.2 ± 6.6 | 38.6 | 66.4 | 40.90 ± 24.20 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
