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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.9 ± 1.8 | 11.8 | 25.5 | 11.12 ± 4.21 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.4 ± 4.4 | 11.7 | 34.0 | 12.39 ± 5.75 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.3 ± 1.4 | 11.6 | 24.3 | 10.63 ± 3.93 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.8 ± 1.7 | 11.8 | 23.0 | 11.02 ± 4.14 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.2 ± 2.8 | 11.6 | 24.2 | 11.41 ± 4.67 |
| `kcen/2022/03/solve input-aspidites` | 250.2 ± 34.6 | 211.6 | 326.1 | 215.61 ± 81.32 |
| `kcen/2022/03/solve input-kcen` | 251.0 ± 14.6 | 229.4 | 274.2 | 216.24 ± 76.91 |
| `kcen/2022/03/solve input-lanjian` | 251.2 ± 16.0 | 235.9 | 284.2 | 216.49 ± 77.20 |
| `kcen/2022/03/solve input-mattcl` | 248.4 ± 15.0 | 220.0 | 268.1 | 214.05 ± 76.20 |
| `kcen/2022/03/solve input-pting` | 248.7 ± 21.1 | 225.1 | 286.3 | 214.26 ± 77.35 |
| `lanjian/day_03 input-aspidites` | 1.5 ± 0.5 | 0.7 | 8.4 | 1.29 ± 0.61 |
| `lanjian/day_03 input-kcen` | 1.3 ± 0.3 | 0.7 | 3.5 | 1.15 ± 0.49 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.4 | 0.6 | 3.1 | 1.06 ± 0.48 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.4 | 0.6 | 4.9 | 1.00 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.4 | 0.7 | 3.9 | 1.01 ± 0.48 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.7 ± 0.5 | 0.6 | 4.2 | 1.43 ± 0.65 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.4 ± 0.4 | 0.8 | 5.4 | 1.25 ± 0.56 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.4 | 0.7 | 4.7 | 1.22 ± 0.57 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.2 ± 0.4 | 0.8 | 5.3 | 1.07 ± 0.52 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.4 | 0.7 | 5.0 | 1.13 ± 0.51 |
| `python pting/day03.py input-aspidites` | 36.6 ± 4.9 | 29.8 | 62.1 | 31.52 ± 11.82 |
| `python pting/day03.py input-kcen` | 33.7 ± 3.8 | 28.7 | 46.4 | 29.00 ± 10.68 |
| `python pting/day03.py input-lanjian` | 34.8 ± 4.9 | 28.0 | 52.3 | 29.99 ± 11.34 |
| `python pting/day03.py input-mattcl` | 38.5 ± 8.8 | 28.9 | 84.7 | 33.21 ± 13.92 |
| `python pting/day03.py input-pting` | 33.7 ± 3.3 | 28.3 | 44.6 | 29.02 ± 10.57 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
