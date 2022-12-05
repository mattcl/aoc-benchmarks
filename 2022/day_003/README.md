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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.1 ± 0.8 | 11.5 | 22.2 | 10.61 ± 2.71 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.8 ± 2.9 | 11.7 | 24.6 | 12.08 ± 3.93 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.8 ± 1.9 | 11.8 | 23.3 | 11.21 ± 3.22 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.8 ± 2.9 | 11.6 | 32.1 | 11.23 ± 3.77 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.7 ± 2.4 | 11.7 | 33.2 | 11.18 ± 3.49 |
| `kcen/2022/03/solve input-aspidites` | 219.6 ± 10.6 | 207.2 | 247.5 | 192.66 ± 48.43 |
| `kcen/2022/03/solve input-kcen` | 260.4 ± 21.1 | 241.1 | 303.7 | 228.39 ± 59.31 |
| `kcen/2022/03/solve input-lanjian` | 223.8 ± 13.3 | 209.1 | 256.7 | 196.32 ± 49.80 |
| `kcen/2022/03/solve input-mattcl` | 230.0 ± 15.1 | 205.9 | 254.3 | 201.79 ± 51.50 |
| `kcen/2022/03/solve input-pting` | 220.1 ± 8.9 | 203.5 | 237.8 | 193.07 ± 48.25 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.4 | 0.7 | 4.9 | 1.15 ± 0.44 |
| `lanjian/day_03 input-kcen` | 1.4 ± 0.9 | 0.7 | 13.2 | 1.25 ± 0.88 |
| `lanjian/day_03 input-lanjian` | 1.1 ± 0.3 | 0.6 | 3.4 | 1.00 |
| `lanjian/day_03 input-mattcl` | 1.3 ± 0.4 | 0.6 | 5.6 | 1.10 ± 0.44 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.3 | 0.6 | 3.7 | 1.03 ± 0.39 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.4 ± 0.4 | 0.6 | 3.6 | 1.22 ± 0.47 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.3 ± 0.5 | 0.7 | 5.2 | 1.12 ± 0.49 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.8 | 0.7 | 12.9 | 1.26 ± 0.78 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.5 ± 0.7 | 0.7 | 8.0 | 1.34 ± 0.70 |
| `mattcl-solver/aoc run 3 input-pting` | 1.2 ± 0.3 | 0.7 | 4.4 | 1.03 ± 0.39 |
| `python pting/day03.py input-aspidites` | 33.1 ± 2.9 | 28.6 | 44.7 | 28.99 ± 7.59 |
| `python pting/day03.py input-kcen` | 34.7 ± 4.6 | 29.0 | 53.9 | 30.47 ± 8.52 |
| `python pting/day03.py input-lanjian` | 35.4 ± 5.4 | 28.6 | 59.6 | 31.07 ± 9.02 |
| `python pting/day03.py input-mattcl` | 32.6 ± 2.5 | 28.2 | 46.4 | 28.60 ± 7.39 |
| `python pting/day03.py input-pting` | 34.9 ± 4.2 | 29.2 | 49.4 | 30.60 ± 8.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
