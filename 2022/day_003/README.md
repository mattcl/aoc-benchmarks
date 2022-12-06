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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 28.1 ± 5.2 | 23.5 | 51.7 | 11.70 ± 6.46 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 27.8 ± 6.0 | 14.6 | 49.3 | 11.56 ± 6.51 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 27.1 ± 4.9 | 23.9 | 50.2 | 11.27 ± 6.21 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 26.4 ± 3.2 | 23.5 | 39.8 | 10.98 ± 5.86 |
| `aspidites-solver/aoc -i input-pting -d 3` | 25.4 ± 2.3 | 13.4 | 39.2 | 10.56 ± 5.58 |
| `kcen/2022/03/solve input-aspidites` | 441.5 ± 29.8 | 397.8 | 482.5 | 183.52 ± 96.30 |
| `kcen/2022/03/solve input-kcen` | 461.8 ± 64.8 | 405.1 | 633.5 | 191.95 ± 103.45 |
| `kcen/2022/03/solve input-lanjian` | 439.1 ± 35.4 | 396.5 | 503.7 | 182.53 ± 96.12 |
| `kcen/2022/03/solve input-mattcl` | 430.9 ± 49.9 | 370.4 | 531.0 | 179.09 ± 95.47 |
| `kcen/2022/03/solve input-pting` | 442.4 ± 56.9 | 361.4 | 521.6 | 183.90 ± 98.57 |
| `lanjian/day_03 input-aspidites` | 3.0 ± 1.5 | 0.7 | 16.4 | 1.27 ± 0.91 |
| `lanjian/day_03 input-kcen` | 2.5 ± 1.1 | 0.7 | 9.6 | 1.05 ± 0.71 |
| `lanjian/day_03 input-lanjian` | 2.6 ± 1.5 | 0.7 | 15.2 | 1.09 ± 0.85 |
| `lanjian/day_03 input-mattcl` | 2.9 ± 1.9 | 0.7 | 27.4 | 1.20 ± 1.01 |
| `lanjian/day_03 input-pting` | 2.4 ± 1.3 | 0.8 | 9.7 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.4 ± 2.0 | 1.3 | 41.2 | 1.42 ± 1.10 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.8 ± 1.3 | 0.7 | 10.4 | 1.16 ± 0.82 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.3 ± 2.0 | 1.1 | 21.4 | 1.36 ± 1.09 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.0 ± 1.5 | 0.8 | 13.9 | 1.23 ± 0.89 |
| `mattcl-solver/aoc run 3 input-pting` | 3.5 ± 1.7 | 1.2 | 20.4 | 1.46 ± 1.04 |
| `python pting/day03.py input-aspidites` | 65.9 ± 14.1 | 51.3 | 150.6 | 27.41 ± 15.42 |
| `python pting/day03.py input-kcen` | 65.7 ± 11.6 | 54.0 | 102.8 | 27.32 ± 15.02 |
| `python pting/day03.py input-lanjian` | 69.4 ± 9.3 | 48.6 | 88.9 | 28.83 ± 15.49 |
| `python pting/day03.py input-mattcl` | 61.0 ± 9.3 | 45.9 | 87.7 | 25.35 ± 13.75 |
| `python pting/day03.py input-pting` | 61.7 ± 12.5 | 47.2 | 119.7 | 25.65 ± 14.32 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
