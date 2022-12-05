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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.6 ± 1.7 | 11.7 | 23.6 | 11.43 ± 4.01 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.8 ± 1.8 | 11.7 | 24.5 | 11.57 ± 4.09 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.7 ± 1.2 | 11.9 | 22.8 | 11.47 ± 3.85 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.5 ± 2.0 | 11.6 | 24.4 | 11.37 ± 4.08 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.7 ± 2.2 | 11.7 | 22.8 | 11.54 ± 4.23 |
| `kcen/2022/03/solve input-aspidites` | 256.6 ± 11.9 | 238.7 | 276.6 | 232.61 ± 75.96 |
| `kcen/2022/03/solve input-kcen` | 241.3 ± 8.2 | 228.0 | 252.2 | 218.75 ± 71.10 |
| `kcen/2022/03/solve input-lanjian` | 236.0 ± 19.4 | 211.1 | 267.8 | 213.95 ± 71.35 |
| `kcen/2022/03/solve input-mattcl` | 218.9 ± 8.1 | 206.0 | 235.1 | 198.43 ± 64.56 |
| `kcen/2022/03/solve input-pting` | 229.7 ± 11.4 | 214.8 | 252.4 | 208.29 ± 68.12 |
| `lanjian/day_03 input-aspidites` | 1.2 ± 0.5 | 0.6 | 4.5 | 1.07 ± 0.54 |
| `lanjian/day_03 input-kcen` | 1.4 ± 0.4 | 0.6 | 7.3 | 1.22 ± 0.56 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.3 | 0.7 | 2.8 | 1.04 ± 0.44 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.3 | 0.6 | 3.4 | 1.08 ± 0.44 |
| `lanjian/day_03 input-pting` | 1.4 ± 0.9 | 0.6 | 14.7 | 1.31 ± 0.95 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.5 ± 0.4 | 0.7 | 5.8 | 1.36 ± 0.59 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.5 ± 0.5 | 0.7 | 6.5 | 1.39 ± 0.63 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.4 | 0.7 | 6.9 | 1.24 ± 0.55 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.1 ± 0.4 | 0.6 | 3.6 | 1.00 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.8 | 0.7 | 10.0 | 1.15 ± 0.81 |
| `python pting/day03.py input-aspidites` | 36.8 ± 5.8 | 29.4 | 56.8 | 33.39 ± 12.01 |
| `python pting/day03.py input-kcen` | 34.7 ± 2.9 | 30.0 | 48.6 | 31.46 ± 10.51 |
| `python pting/day03.py input-lanjian` | 33.9 ± 3.8 | 28.6 | 47.7 | 30.71 ± 10.52 |
| `python pting/day03.py input-mattcl` | 33.4 ± 3.1 | 29.4 | 44.4 | 30.27 ± 10.19 |
| `python pting/day03.py input-pting` | 36.1 ± 4.1 | 30.6 | 49.0 | 32.73 ± 11.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
