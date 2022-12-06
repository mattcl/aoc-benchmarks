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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 32.7 ± 16.4 | 12.6 | 108.0 | 25.27 ± 25.83 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 24.2 ± 3.2 | 12.1 | 39.4 | 18.74 ± 16.86 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 24.9 ± 3.2 | 13.3 | 38.9 | 19.31 ± 17.36 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.7 ± 4.5 | 22.3 | 44.6 | 19.87 ± 18.03 |
| `aspidites-solver/aoc -i input-pting -d 3` | 24.5 ± 4.0 | 11.4 | 40.5 | 18.99 ± 17.18 |
| `kcen/2022/03/solve input-aspidites` | 437.9 ± 43.4 | 364.5 | 508.2 | 338.93 ± 303.42 |
| `kcen/2022/03/solve input-kcen` | 407.9 ± 24.0 | 370.2 | 443.7 | 315.74 ± 281.53 |
| `kcen/2022/03/solve input-lanjian` | 449.7 ± 56.5 | 408.2 | 600.8 | 348.07 ± 312.75 |
| `kcen/2022/03/solve input-mattcl` | 407.0 ± 41.9 | 336.4 | 489.4 | 315.01 ± 282.15 |
| `kcen/2022/03/solve input-pting` | 403.0 ± 17.3 | 373.6 | 428.6 | 311.94 ± 277.87 |
| `lanjian/day_03 input-aspidites` | 1.8 ± 1.8 | 0.0 | 16.0 | 1.38 ± 1.84 |
| `lanjian/day_03 input-kcen` | 1.4 ± 1.7 | 0.0 | 20.6 | 1.08 ± 1.61 |
| `lanjian/day_03 input-lanjian` | 1.3 ± 2.1 | 0.0 | 20.9 | 1.04 ± 1.88 |
| `lanjian/day_03 input-mattcl` | 1.6 ± 1.2 | 0.0 | 11.6 | 1.27 ± 1.45 |
| `lanjian/day_03 input-pting` | 2.8 ± 2.4 | 0.2 | 19.6 | 2.20 ± 2.72 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.4 ± 1.0 | 0.0 | 6.1 | 1.07 ± 1.24 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.4 ± 1.2 | 0.0 | 10.7 | 1.10 ± 1.36 |
| `mattcl-solver/aoc run 3 input-lanjian` | 8.6 ± 7.7 | 0.6 | 57.4 | 6.69 ± 8.45 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.3 ± 1.1 | 0.0 | 15.1 | 1.00 |
| `mattcl-solver/aoc run 3 input-pting` | 5.6 ± 6.9 | 0.2 | 45.8 | 4.34 ± 6.59 |
| `python pting/day03.py input-aspidites` | 61.3 ± 10.5 | 43.6 | 88.0 | 47.41 ± 42.96 |
| `python pting/day03.py input-kcen` | 56.6 ± 9.9 | 40.4 | 102.9 | 43.85 ± 39.76 |
| `python pting/day03.py input-lanjian` | 62.0 ± 10.1 | 46.2 | 96.3 | 48.03 ± 43.44 |
| `python pting/day03.py input-mattcl` | 57.1 ± 8.3 | 44.6 | 82.0 | 44.18 ± 39.84 |
| `python pting/day03.py input-pting` | 62.7 ± 12.6 | 46.9 | 91.3 | 48.57 ± 44.30 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
