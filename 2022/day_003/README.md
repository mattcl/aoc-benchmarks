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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 14.9 ± 4.4 | 11.9 | 29.6 | 13.22 ± 4.54 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.8 ± 3.1 | 11.8 | 25.6 | 12.25 ± 3.49 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.0 ± 0.4 | 11.5 | 13.9 | 10.69 ± 1.94 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 14.8 ± 4.0 | 11.7 | 27.3 | 13.11 ± 4.29 |
| `aspidites-solver/aoc -i input-pting -d 3` | 14.8 ± 4.2 | 11.9 | 32.1 | 13.10 ± 4.41 |
| `kcen/2022/03/solve input-aspidites` | 281.2 ± 23.7 | 223.8 | 303.1 | 249.43 ± 49.29 |
| `kcen/2022/03/solve input-kcen` | 265.0 ± 15.0 | 243.3 | 283.6 | 235.07 ± 44.06 |
| `kcen/2022/03/solve input-lanjian` | 213.6 ± 18.7 | 193.2 | 249.5 | 189.49 ± 37.70 |
| `kcen/2022/03/solve input-mattcl` | 284.1 ± 23.0 | 256.3 | 314.7 | 251.96 ± 49.42 |
| `kcen/2022/03/solve input-pting` | 268.6 ± 43.7 | 238.3 | 385.5 | 238.26 ± 57.59 |
| `lanjian/day_03 input-aspidites` | 1.8 ± 0.7 | 0.7 | 5.4 | 1.62 ± 0.67 |
| `lanjian/day_03 input-kcen` | 1.8 ± 0.6 | 0.7 | 5.0 | 1.62 ± 0.63 |
| `lanjian/day_03 input-lanjian` | 1.1 ± 0.3 | 0.7 | 5.5 | 1.00 ± 0.35 |
| `lanjian/day_03 input-mattcl` | 1.3 ± 0.6 | 0.6 | 7.4 | 1.19 ± 0.60 |
| `lanjian/day_03 input-pting` | 1.8 ± 0.8 | 0.8 | 9.2 | 1.58 ± 0.78 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.0 ± 0.7 | 0.8 | 6.2 | 1.75 ± 0.70 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.9 ± 0.7 | 0.8 | 7.1 | 1.72 ± 0.66 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.1 ± 0.2 | 0.7 | 2.6 | 1.00 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.1 ± 0.5 | 0.7 | 8.5 | 1.00 ± 0.48 |
| `mattcl-solver/aoc run 3 input-pting` | 1.8 ± 0.6 | 0.9 | 7.3 | 1.62 ± 0.63 |
| `python pting/day03.py input-aspidites` | 41.8 ± 9.3 | 31.8 | 76.4 | 37.06 ± 10.60 |
| `python pting/day03.py input-kcen` | 35.5 ± 4.9 | 29.7 | 55.5 | 31.45 ± 7.10 |
| `python pting/day03.py input-lanjian` | 35.2 ± 6.8 | 28.7 | 60.4 | 31.27 ± 8.24 |
| `python pting/day03.py input-mattcl` | 38.0 ± 6.3 | 27.9 | 65.0 | 33.68 ± 8.20 |
| `python pting/day03.py input-pting` | 41.6 ± 7.4 | 31.5 | 65.6 | 36.89 ± 9.33 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
