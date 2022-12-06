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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 23.3 ± 8.8 | 12.6 | 48.5 | 12.10 ± 7.02 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 27.1 ± 3.4 | 24.2 | 44.7 | 14.04 ± 6.44 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 28.1 ± 4.8 | 23.9 | 55.5 | 14.55 ± 6.90 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 24.6 ± 5.7 | 13.2 | 48.3 | 12.74 ± 6.36 |
| `aspidites-solver/aoc -i input-pting -d 3` | 27.5 ± 4.9 | 13.8 | 46.4 | 14.29 ± 6.80 |
| `kcen/2022/03/solve input-aspidites` | 348.3 ± 28.3 | 300.2 | 386.0 | 180.66 ± 81.16 |
| `kcen/2022/03/solve input-kcen` | 382.8 ± 38.2 | 337.9 | 445.1 | 198.54 ± 89.93 |
| `kcen/2022/03/solve input-lanjian` | 360.7 ± 61.0 | 294.3 | 505.2 | 187.12 ± 88.53 |
| `kcen/2022/03/solve input-mattcl` | 368.1 ± 69.1 | 302.2 | 497.9 | 190.96 ± 91.67 |
| `kcen/2022/03/solve input-pting` | 502.8 ± 188.5 | 357.2 | 962.6 | 260.82 ± 151.11 |
| `lanjian/day_03 input-aspidites` | 3.7 ± 1.9 | 1.2 | 18.1 | 1.90 ± 1.31 |
| `lanjian/day_03 input-kcen` | 3.1 ± 1.4 | 0.8 | 9.5 | 1.60 ± 1.03 |
| `lanjian/day_03 input-lanjian` | 3.1 ± 1.6 | 0.9 | 15.8 | 1.63 ± 1.10 |
| `lanjian/day_03 input-mattcl` | 3.4 ± 1.5 | 0.9 | 10.9 | 1.78 ± 1.12 |
| `lanjian/day_03 input-pting` | 2.5 ± 1.4 | 0.6 | 8.4 | 1.28 ± 0.93 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.9 ± 1.6 | 0.8 | 13.0 | 1.52 ± 1.08 |
| `mattcl-solver/aoc run 3 input-kcen` | 4.0 ± 2.1 | 1.0 | 15.9 | 2.07 ± 1.42 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.7 ± 1.4 | 1.5 | 13.7 | 1.91 ± 1.13 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.0 ± 1.5 | 1.0 | 13.5 | 1.55 ± 1.03 |
| `mattcl-solver/aoc run 3 input-pting` | 1.9 ± 0.9 | 0.7 | 7.8 | 1.00 |
| `python pting/day03.py input-aspidites` | 56.7 ± 24.1 | 38.8 | 165.0 | 29.42 ± 18.05 |
| `python pting/day03.py input-kcen` | 59.6 ± 20.4 | 39.0 | 159.3 | 30.94 ± 17.29 |
| `python pting/day03.py input-lanjian` | 59.8 ± 29.9 | 42.8 | 192.2 | 31.02 ± 20.69 |
| `python pting/day03.py input-mattcl` | 70.1 ± 34.0 | 45.1 | 161.3 | 36.35 ± 23.86 |
| `python pting/day03.py input-pting` | 59.9 ± 21.5 | 38.4 | 149.7 | 31.05 ± 17.68 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
