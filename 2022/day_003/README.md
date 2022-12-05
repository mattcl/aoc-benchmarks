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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.6 ± 2.7 | 11.8 | 25.1 | 11.87 ± 4.21 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.7 ± 1.5 | 11.8 | 24.4 | 11.08 ± 3.52 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.9 ± 2.0 | 11.8 | 23.5 | 11.23 ± 3.73 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.8 ± 1.6 | 11.7 | 22.9 | 11.22 ± 3.60 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.8 ± 1.5 | 11.7 | 23.2 | 11.21 ± 3.56 |
| `kcen/2022/03/solve input-aspidites` | 258.0 ± 25.0 | 232.4 | 311.6 | 225.38 ± 69.86 |
| `kcen/2022/03/solve input-kcen` | 244.9 ± 19.0 | 218.4 | 281.4 | 213.96 ± 65.15 |
| `kcen/2022/03/solve input-lanjian` | 247.7 ± 16.3 | 220.3 | 278.0 | 216.41 ± 65.31 |
| `kcen/2022/03/solve input-mattcl` | 295.5 ± 35.0 | 246.5 | 352.5 | 258.16 ± 81.94 |
| `kcen/2022/03/solve input-pting` | 260.2 ± 17.4 | 244.8 | 301.9 | 227.30 ± 68.64 |
| `lanjian/day_03 input-aspidites` | 2.0 ± 0.8 | 0.8 | 9.1 | 1.77 ± 0.88 |
| `lanjian/day_03 input-kcen` | 1.4 ± 0.5 | 0.7 | 9.0 | 1.20 ± 0.56 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.5 | 0.7 | 12.0 | 1.05 ± 0.56 |
| `lanjian/day_03 input-mattcl` | 1.1 ± 0.3 | 0.7 | 3.5 | 1.00 |
| `lanjian/day_03 input-pting` | 1.4 ± 0.4 | 0.7 | 6.6 | 1.19 ± 0.50 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.6 ± 0.9 | 0.7 | 10.9 | 1.41 ± 0.92 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.7 ± 0.7 | 0.8 | 11.6 | 1.50 ± 0.78 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.3 ± 0.4 | 0.7 | 5.0 | 1.13 ± 0.47 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.3 ± 0.4 | 0.7 | 4.1 | 1.12 ± 0.48 |
| `mattcl-solver/aoc run 3 input-pting` | 1.2 ± 0.4 | 0.7 | 4.1 | 1.08 ± 0.45 |
| `python pting/day03.py input-aspidites` | 37.9 ± 5.6 | 30.4 | 59.1 | 33.10 ± 10.89 |
| `python pting/day03.py input-kcen` | 33.8 ± 3.7 | 27.6 | 43.3 | 29.57 ± 9.30 |
| `python pting/day03.py input-lanjian` | 37.9 ± 4.9 | 30.1 | 50.6 | 33.12 ± 10.64 |
| `python pting/day03.py input-mattcl` | 38.7 ± 6.4 | 29.2 | 75.8 | 33.82 ± 11.42 |
| `python pting/day03.py input-pting` | 33.8 ± 3.8 | 29.4 | 49.0 | 29.52 ± 9.30 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
