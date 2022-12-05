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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.0 ± 2.2 | 11.8 | 24.4 | 13.19 ± 4.04 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.1 ± 2.2 | 12.0 | 24.5 | 13.33 ± 4.05 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.0 ± 2.2 | 11.7 | 24.1 | 13.16 ± 4.05 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.6 ± 1.9 | 11.8 | 22.7 | 12.76 ± 3.78 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.9 ± 4.2 | 11.8 | 38.6 | 14.11 ± 5.57 |
| `kcen/2022/03/solve input-aspidites` | 243.3 ± 25.3 | 211.2 | 296.1 | 246.75 ± 68.30 |
| `kcen/2022/03/solve input-kcen` | 236.2 ± 10.5 | 217.6 | 253.1 | 239.57 ± 62.36 |
| `kcen/2022/03/solve input-lanjian` | 238.9 ± 12.7 | 219.0 | 259.9 | 242.26 ± 63.45 |
| `kcen/2022/03/solve input-mattcl` | 225.7 ± 14.0 | 207.8 | 248.6 | 228.91 ± 60.40 |
| `kcen/2022/03/solve input-pting` | 260.0 ± 25.1 | 222.2 | 298.4 | 263.66 ± 72.25 |
| `lanjian/day_03 input-aspidites` | 1.1 ± 0.3 | 0.7 | 4.2 | 1.12 ± 0.42 |
| `lanjian/day_03 input-kcen` | 1.2 ± 0.6 | 0.7 | 9.3 | 1.26 ± 0.73 |
| `lanjian/day_03 input-lanjian` | 1.4 ± 0.4 | 0.8 | 10.1 | 1.44 ± 0.57 |
| `lanjian/day_03 input-mattcl` | 1.0 ± 0.3 | 0.7 | 6.6 | 1.00 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.4 | 0.8 | 4.3 | 1.24 ± 0.48 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.2 ± 0.5 | 0.7 | 7.8 | 1.24 ± 0.63 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.2 ± 0.4 | 0.7 | 5.1 | 1.25 ± 0.51 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.9 ± 1.1 | 0.8 | 12.0 | 1.96 ± 1.23 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.2 ± 0.3 | 0.8 | 4.6 | 1.20 ± 0.42 |
| `mattcl-solver/aoc run 3 input-pting` | 1.4 ± 0.4 | 0.8 | 4.1 | 1.42 ± 0.51 |
| `python pting/day03.py input-aspidites` | 32.8 ± 2.9 | 28.5 | 46.6 | 33.23 ± 9.03 |
| `python pting/day03.py input-kcen` | 38.6 ± 5.3 | 30.3 | 51.5 | 39.14 ± 11.40 |
| `python pting/day03.py input-lanjian` | 35.5 ± 3.6 | 30.4 | 47.0 | 36.04 ± 9.92 |
| `python pting/day03.py input-mattcl` | 31.7 ± 2.9 | 28.0 | 45.3 | 32.15 ± 8.75 |
| `python pting/day03.py input-pting` | 36.7 ± 4.4 | 29.3 | 49.7 | 37.18 ± 10.53 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
