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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 16.1 ± 5.2 | 11.9 | 35.0 | 15.56 ± 6.61 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.5 ± 4.2 | 11.8 | 35.4 | 14.07 ± 5.62 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.9 ± 4.1 | 11.5 | 31.2 | 13.41 ± 5.38 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.2 ± 3.1 | 11.5 | 24.8 | 12.74 ± 4.57 |
| `aspidites-solver/aoc -i input-pting -d 3` | 14.7 ± 4.4 | 11.5 | 26.4 | 14.21 ± 5.74 |
| `kcen/2022/03/solve input-aspidites` | 270.4 ± 37.1 | 227.7 | 372.3 | 261.52 ± 80.01 |
| `kcen/2022/03/solve input-kcen` | 238.4 ± 26.0 | 197.5 | 298.8 | 230.59 ± 67.86 |
| `kcen/2022/03/solve input-lanjian` | 240.1 ± 28.7 | 207.1 | 292.2 | 232.29 ± 69.30 |
| `kcen/2022/03/solve input-mattcl` | 247.1 ± 21.5 | 217.0 | 275.8 | 239.00 ± 68.56 |
| `kcen/2022/03/solve input-pting` | 266.3 ± 27.3 | 236.3 | 309.8 | 257.56 ± 75.21 |
| `lanjian/day_03 input-aspidites` | 2.3 ± 0.9 | 0.8 | 15.3 | 2.18 ± 1.08 |
| `lanjian/day_03 input-kcen` | 1.6 ± 0.7 | 0.8 | 6.6 | 1.57 ± 0.78 |
| `lanjian/day_03 input-lanjian` | 1.1 ± 0.3 | 0.7 | 4.4 | 1.04 ± 0.43 |
| `lanjian/day_03 input-mattcl` | 1.7 ± 0.6 | 0.8 | 4.8 | 1.66 ± 0.74 |
| `lanjian/day_03 input-pting` | 1.4 ± 0.6 | 0.6 | 7.1 | 1.36 ± 0.68 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.1 ± 1.2 | 0.9 | 14.4 | 2.03 ± 1.27 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.4 ± 0.9 | 0.9 | 9.5 | 2.36 ± 1.09 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.8 ± 0.8 | 0.8 | 7.9 | 1.75 ± 0.93 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.0 ± 0.3 | 0.7 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 3 input-pting` | 1.7 ± 0.9 | 0.7 | 9.3 | 1.67 ± 0.96 |
| `python pting/day03.py input-aspidites` | 41.1 ± 10.4 | 29.9 | 74.0 | 39.76 ± 14.80 |
| `python pting/day03.py input-kcen` | 40.8 ± 8.4 | 28.2 | 60.8 | 39.46 ± 13.53 |
| `python pting/day03.py input-lanjian` | 37.2 ± 7.3 | 27.5 | 63.8 | 35.98 ± 12.12 |
| `python pting/day03.py input-mattcl` | 36.6 ± 9.5 | 26.7 | 80.1 | 35.41 ± 13.38 |
| `python pting/day03.py input-pting` | 35.6 ± 7.6 | 28.2 | 70.4 | 34.48 ± 11.96 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
