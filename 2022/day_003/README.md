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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.5 ± 1.3 | 11.8 | 22.7 | 11.17 ± 3.29 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.3 ± 1.1 | 11.5 | 22.9 | 10.99 ± 3.21 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.5 ± 1.0 | 11.8 | 22.1 | 11.10 ± 3.21 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.9 ± 2.4 | 11.8 | 26.1 | 11.53 ± 3.84 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.3 ± 2.8 | 11.9 | 29.6 | 11.83 ± 4.11 |
| `kcen/2022/03/solve input-aspidites` | 229.5 ± 8.3 | 219.0 | 241.6 | 204.34 ± 57.11 |
| `kcen/2022/03/solve input-kcen` | 239.2 ± 19.4 | 213.7 | 273.3 | 212.96 ± 61.48 |
| `kcen/2022/03/solve input-lanjian` | 237.3 ± 16.7 | 210.7 | 267.0 | 211.27 ± 60.40 |
| `kcen/2022/03/solve input-mattcl` | 236.3 ± 17.8 | 216.1 | 265.1 | 210.39 ± 60.42 |
| `kcen/2022/03/solve input-pting` | 255.7 ± 21.8 | 223.1 | 293.6 | 227.64 ± 66.00 |
| `lanjian/day_03 input-aspidites` | 1.1 ± 0.3 | 0.6 | 4.3 | 1.00 |
| `lanjian/day_03 input-kcen` | 1.4 ± 0.7 | 0.6 | 10.4 | 1.29 ± 0.72 |
| `lanjian/day_03 input-lanjian` | 1.3 ± 0.3 | 0.5 | 3.8 | 1.12 ± 0.44 |
| `lanjian/day_03 input-mattcl` | 1.3 ± 0.5 | 0.5 | 4.6 | 1.14 ± 0.55 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.3 | 0.6 | 3.3 | 1.06 ± 0.41 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.3 ± 0.5 | 0.7 | 7.6 | 1.15 ± 0.52 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.4 ± 0.5 | 0.7 | 5.1 | 1.21 ± 0.55 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.3 ± 0.4 | 0.8 | 4.0 | 1.18 ± 0.46 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.4 ± 0.6 | 0.7 | 6.6 | 1.23 ± 0.65 |
| `mattcl-solver/aoc run 3 input-pting` | 1.2 ± 0.5 | 0.7 | 7.2 | 1.05 ± 0.50 |
| `python pting/day03.py input-aspidites` | 32.1 ± 3.9 | 27.5 | 53.3 | 28.54 ± 8.63 |
| `python pting/day03.py input-kcen` | 34.0 ± 2.8 | 29.9 | 42.5 | 30.31 ± 8.77 |
| `python pting/day03.py input-lanjian` | 36.7 ± 5.7 | 28.8 | 58.2 | 32.64 ± 10.37 |
| `python pting/day03.py input-mattcl` | 40.7 ± 11.2 | 30.9 | 94.4 | 36.23 ± 14.14 |
| `python pting/day03.py input-pting` | 34.0 ± 2.4 | 29.6 | 40.2 | 30.25 ± 8.66 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
