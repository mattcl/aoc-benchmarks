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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 25.2 ± 4.2 | 13.1 | 44.3 | 11.37 ± 6.15 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.0 ± 2.9 | 13.2 | 40.3 | 11.27 ± 5.94 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 25.5 ± 1.6 | 23.5 | 36.2 | 11.50 ± 5.96 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 26.4 ± 2.2 | 23.4 | 37.5 | 11.90 ± 6.20 |
| `aspidites-solver/aoc -i input-pting -d 3` | 26.2 ± 3.0 | 23.8 | 45.4 | 11.79 ± 6.21 |
| `kcen/2022/03/solve input-aspidites` | 369.5 ± 41.4 | 313.5 | 447.1 | 166.58 ± 87.67 |
| `kcen/2022/03/solve input-kcen` | 420.6 ± 36.5 | 370.3 | 479.5 | 189.61 ± 98.88 |
| `kcen/2022/03/solve input-lanjian` | 427.5 ± 34.1 | 367.8 | 479.2 | 192.71 ± 100.29 |
| `kcen/2022/03/solve input-mattcl` | 422.6 ± 27.8 | 387.6 | 474.3 | 190.49 ± 98.76 |
| `kcen/2022/03/solve input-pting` | 399.3 ± 20.9 | 365.6 | 434.2 | 180.00 ± 93.04 |
| `lanjian/day_03 input-aspidites` | 2.2 ± 1.1 | 0.6 | 8.4 | 1.00 |
| `lanjian/day_03 input-kcen` | 2.5 ± 1.0 | 0.5 | 10.1 | 1.11 ± 0.74 |
| `lanjian/day_03 input-lanjian` | 2.5 ± 0.9 | 0.8 | 7.5 | 1.13 ± 0.71 |
| `lanjian/day_03 input-mattcl` | 3.2 ± 1.5 | 0.5 | 18.7 | 1.43 ± 0.98 |
| `lanjian/day_03 input-pting` | 2.4 ± 1.2 | 0.4 | 9.5 | 1.07 ± 0.76 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.5 ± 1.3 | 1.2 | 13.6 | 1.60 ± 1.01 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.6 ± 1.1 | 0.9 | 15.3 | 1.18 ± 0.78 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.3 ± 1.1 | 0.7 | 13.1 | 1.48 ± 0.91 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.0 ± 1.0 | 0.9 | 8.6 | 1.36 ± 0.83 |
| `mattcl-solver/aoc run 3 input-pting` | 2.6 ± 1.3 | 0.5 | 9.9 | 1.17 ± 0.84 |
| `python pting/day03.py input-aspidites` | 56.9 ± 7.3 | 44.7 | 76.7 | 25.67 ± 13.60 |
| `python pting/day03.py input-kcen` | 55.0 ± 6.6 | 43.9 | 74.9 | 24.78 ± 13.09 |
| `python pting/day03.py input-lanjian` | 79.6 ± 22.1 | 53.7 | 129.2 | 35.89 ± 20.98 |
| `python pting/day03.py input-mattcl` | 60.3 ± 8.4 | 46.5 | 76.6 | 27.17 ± 14.47 |
| `python pting/day03.py input-pting` | 64.4 ± 22.1 | 41.3 | 133.4 | 29.02 ± 17.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
