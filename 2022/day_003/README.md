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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 27.9 ± 6.0 | 20.0 | 69.7 | 8.44 ± 4.30 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 28.2 ± 3.9 | 22.2 | 48.1 | 8.54 ± 4.11 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 27.4 ± 5.7 | 13.7 | 56.3 | 8.30 ± 4.20 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 44.7 ± 52.6 | 25.1 | 315.3 | 13.52 ± 17.08 |
| `aspidites-solver/aoc -i input-pting -d 3` | 27.5 ± 3.4 | 20.8 | 41.5 | 8.30 ± 3.97 |
| `kcen/2022/03/solve input-aspidites` | 412.4 ± 21.6 | 376.6 | 439.4 | 124.75 ± 57.92 |
| `kcen/2022/03/solve input-kcen` | 442.3 ± 44.4 | 385.7 | 507.3 | 133.77 ± 63.16 |
| `kcen/2022/03/solve input-lanjian` | 387.6 ± 30.2 | 341.8 | 435.6 | 117.23 ± 54.85 |
| `kcen/2022/03/solve input-mattcl` | 496.7 ± 238.5 | 342.4 | 956.9 | 150.23 ± 100.02 |
| `kcen/2022/03/solve input-pting` | 413.0 ± 35.3 | 358.9 | 457.1 | 124.92 ± 58.61 |
| `lanjian/day_03 input-aspidites` | 3.4 ± 1.3 | 1.0 | 14.4 | 1.02 ± 0.62 |
| `lanjian/day_03 input-kcen` | 3.7 ± 1.7 | 1.2 | 26.0 | 1.12 ± 0.74 |
| `lanjian/day_03 input-lanjian` | 3.3 ± 1.1 | 1.2 | 9.0 | 1.01 ± 0.57 |
| `lanjian/day_03 input-mattcl` | 3.3 ± 1.5 | 1.1 | 22.2 | 1.00 |
| `lanjian/day_03 input-pting` | 3.8 ± 2.2 | 0.9 | 18.5 | 1.14 ± 0.85 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.5 ± 1.4 | 1.0 | 14.5 | 1.05 ± 0.64 |
| `mattcl-solver/aoc run 3 input-kcen` | 3.7 ± 1.5 | 1.2 | 13.2 | 1.11 ± 0.69 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.5 ± 1.7 | 1.4 | 20.3 | 1.07 ± 0.72 |
| `mattcl-solver/aoc run 3 input-mattcl` | 4.1 ± 1.3 | 1.6 | 11.6 | 1.25 ± 0.70 |
| `mattcl-solver/aoc run 3 input-pting` | 4.3 ± 1.8 | 1.6 | 15.3 | 1.30 ± 0.81 |
| `python pting/day03.py input-aspidites` | 61.6 ± 12.2 | 45.1 | 106.2 | 18.64 ± 9.35 |
| `python pting/day03.py input-kcen` | 63.8 ± 8.6 | 51.1 | 79.4 | 19.29 ± 9.27 |
| `python pting/day03.py input-lanjian` | 60.3 ± 8.3 | 43.0 | 88.4 | 18.23 ± 8.77 |
| `python pting/day03.py input-mattcl` | 57.8 ± 9.5 | 45.4 | 94.2 | 17.47 ± 8.56 |
| `python pting/day03.py input-pting` | 54.3 ± 7.4 | 42.8 | 76.6 | 16.42 ± 7.90 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
