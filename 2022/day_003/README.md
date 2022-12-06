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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 26.4 ± 1.6 | 15.1 | 30.8 | 11.67 ± 6.49 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 24.5 ± 4.7 | 12.8 | 47.1 | 10.85 ± 6.34 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 25.8 ± 3.3 | 13.6 | 38.1 | 11.42 ± 6.47 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 30.5 ± 14.2 | 13.7 | 114.5 | 13.49 ± 9.73 |
| `aspidites-solver/aoc -i input-pting -d 3` | 26.3 ± 1.9 | 24.0 | 38.6 | 11.62 ± 6.48 |
| `kcen/2022/03/solve input-aspidites` | 398.1 ± 57.2 | 339.7 | 525.6 | 175.97 ± 100.51 |
| `kcen/2022/03/solve input-kcen` | 356.5 ± 28.5 | 308.1 | 402.8 | 157.58 ± 88.01 |
| `kcen/2022/03/solve input-lanjian` | 366.4 ± 25.6 | 332.5 | 418.2 | 161.95 ± 90.23 |
| `kcen/2022/03/solve input-mattcl` | 377.4 ± 37.7 | 329.6 | 455.3 | 166.81 ± 93.69 |
| `kcen/2022/03/solve input-pting` | 391.2 ± 24.2 | 343.1 | 419.9 | 172.91 ± 96.17 |
| `lanjian/day_03 input-aspidites` | 3.1 ± 1.2 | 0.9 | 13.4 | 1.37 ± 0.91 |
| `lanjian/day_03 input-kcen` | 2.3 ± 1.3 | 0.9 | 20.2 | 1.00 |
| `lanjian/day_03 input-lanjian` | 2.9 ± 1.4 | 0.8 | 10.9 | 1.27 ± 0.92 |
| `lanjian/day_03 input-mattcl` | 3.1 ± 1.3 | 1.0 | 11.0 | 1.38 ± 0.95 |
| `lanjian/day_03 input-pting` | 2.5 ± 1.0 | 0.9 | 10.6 | 1.10 ± 0.75 |
| `mattcl-solver/aoc run 3 input-aspidites` | 4.4 ± 3.5 | 1.3 | 27.6 | 1.94 ± 1.89 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.8 ± 1.1 | 0.9 | 10.1 | 1.23 ± 0.82 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.2 ± 1.2 | 1.0 | 13.2 | 1.40 ± 0.94 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.2 ± 1.4 | 0.9 | 8.9 | 1.40 ± 0.99 |
| `mattcl-solver/aoc run 3 input-pting` | 3.4 ± 1.2 | 1.2 | 8.8 | 1.50 ± 0.99 |
| `python pting/day03.py input-aspidites` | 67.2 ± 10.7 | 51.5 | 99.2 | 29.69 ± 17.08 |
| `python pting/day03.py input-kcen` | 54.4 ± 5.6 | 45.4 | 72.4 | 24.06 ± 13.53 |
| `python pting/day03.py input-lanjian` | 53.0 ± 7.5 | 43.2 | 72.2 | 23.45 ± 13.37 |
| `python pting/day03.py input-mattcl` | 52.0 ± 7.2 | 43.0 | 86.9 | 22.98 ± 13.10 |
| `python pting/day03.py input-pting` | 59.2 ± 9.4 | 44.9 | 89.2 | 26.17 ± 15.05 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
