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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.7 ± 3.8 | 11.6 | 29.3 | 11.50 ± 5.68 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.4 ± 3.6 | 11.4 | 24.7 | 11.31 ± 5.53 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.0 ± 2.8 | 11.5 | 25.0 | 10.96 ± 5.07 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.5 ± 3.3 | 11.5 | 25.3 | 11.41 ± 5.42 |
| `aspidites-solver/aoc -i input-pting -d 3` | 14.8 ± 4.7 | 11.4 | 26.3 | 12.49 ± 6.45 |
| `kcen/2022/03/solve input-aspidites` | 239.8 ± 20.8 | 217.6 | 296.8 | 202.09 ± 84.36 |
| `kcen/2022/03/solve input-kcen` | 243.1 ± 24.0 | 215.2 | 292.6 | 204.89 ± 86.07 |
| `kcen/2022/03/solve input-lanjian` | 238.7 ± 17.8 | 212.1 | 271.4 | 201.14 ± 83.49 |
| `kcen/2022/03/solve input-mattcl` | 228.4 ± 23.0 | 201.0 | 271.9 | 192.43 ± 80.93 |
| `kcen/2022/03/solve input-pting` | 227.4 ± 10.9 | 213.4 | 253.5 | 191.64 ± 78.79 |
| `lanjian/day_03 input-aspidites` | 1.4 ± 0.5 | 0.6 | 3.2 | 1.15 ± 0.65 |
| `lanjian/day_03 input-kcen` | 2.0 ± 0.7 | 0.6 | 5.0 | 1.68 ± 0.89 |
| `lanjian/day_03 input-lanjian` | 1.3 ± 0.6 | 0.6 | 5.9 | 1.11 ± 0.65 |
| `lanjian/day_03 input-mattcl` | 1.3 ± 0.6 | 0.5 | 9.0 | 1.06 ± 0.64 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.5 | 0.5 | 6.0 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.2 ± 0.7 | 0.6 | 12.3 | 1.03 ± 0.71 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.8 ± 0.8 | 0.7 | 5.6 | 1.55 ± 0.92 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.5 ± 1.0 | 0.6 | 8.4 | 1.28 ± 0.99 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.6 ± 0.6 | 0.6 | 5.3 | 1.35 ± 0.77 |
| `mattcl-solver/aoc run 3 input-pting` | 1.5 ± 0.9 | 0.7 | 17.2 | 1.23 ± 0.94 |
| `python pting/day03.py input-aspidites` | 36.9 ± 5.9 | 30.7 | 64.5 | 31.14 ± 13.64 |
| `python pting/day03.py input-kcen` | 38.7 ± 6.7 | 27.5 | 62.7 | 32.57 ± 14.45 |
| `python pting/day03.py input-lanjian` | 37.3 ± 7.9 | 28.8 | 71.9 | 31.41 ± 14.47 |
| `python pting/day03.py input-mattcl` | 36.0 ± 4.4 | 28.6 | 57.3 | 30.33 ± 12.94 |
| `python pting/day03.py input-pting` | 33.2 ± 4.9 | 27.6 | 60.5 | 27.98 ± 12.14 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
