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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.1 ± 0.8 | 11.5 | 22.0 | 13.89 ± 4.22 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.1 ± 4.3 | 11.6 | 38.6 | 16.18 ± 6.86 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.9 ± 2.3 | 11.6 | 23.8 | 14.79 ± 5.14 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.8 ± 2.6 | 11.5 | 28.3 | 14.70 ± 5.27 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.6 ± 1.8 | 11.6 | 24.1 | 14.47 ± 4.77 |
| `kcen/2022/03/solve input-aspidites` | 239.5 ± 13.7 | 214.8 | 255.9 | 275.70 ± 83.34 |
| `kcen/2022/03/solve input-kcen` | 244.8 ± 12.2 | 229.6 | 266.9 | 281.76 ± 84.80 |
| `kcen/2022/03/solve input-lanjian` | 232.8 ± 8.0 | 218.5 | 243.1 | 267.92 ± 80.05 |
| `kcen/2022/03/solve input-mattcl` | 246.8 ± 10.4 | 233.4 | 267.6 | 284.01 ± 85.15 |
| `kcen/2022/03/solve input-pting` | 243.3 ± 15.4 | 221.5 | 267.7 | 280.01 ± 84.97 |
| `lanjian/day_03 input-aspidites` | 1.1 ± 0.6 | 0.6 | 15.9 | 1.30 ± 0.75 |
| `lanjian/day_03 input-kcen` | 1.3 ± 0.6 | 0.6 | 11.5 | 1.54 ± 0.85 |
| `lanjian/day_03 input-lanjian` | 1.0 ± 0.5 | 0.5 | 7.8 | 1.12 ± 0.65 |
| `lanjian/day_03 input-mattcl` | 1.1 ± 0.4 | 0.6 | 4.3 | 1.31 ± 0.57 |
| `lanjian/day_03 input-pting` | 0.9 ± 0.3 | 0.6 | 3.1 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.1 ± 0.3 | 0.6 | 3.2 | 1.30 ± 0.53 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.4 ± 0.7 | 0.6 | 10.5 | 1.61 ± 0.90 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.5 ± 0.9 | 0.6 | 12.6 | 1.77 ± 1.13 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.2 ± 0.3 | 0.6 | 3.1 | 1.44 ± 0.56 |
| `mattcl-solver/aoc run 3 input-pting` | 1.0 ± 0.3 | 0.6 | 6.2 | 1.12 ± 0.50 |
| `python pting/day03.py input-aspidites` | 37.8 ± 4.8 | 31.4 | 53.1 | 43.52 ± 14.03 |
| `python pting/day03.py input-kcen` | 35.3 ± 3.0 | 30.6 | 44.1 | 40.59 ± 12.52 |
| `python pting/day03.py input-lanjian` | 34.4 ± 3.4 | 29.3 | 43.3 | 39.56 ± 12.38 |
| `python pting/day03.py input-mattcl` | 34.4 ± 4.0 | 29.2 | 48.6 | 39.59 ± 12.63 |
| `python pting/day03.py input-pting` | 32.6 ± 2.8 | 28.5 | 43.5 | 37.54 ± 11.58 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
