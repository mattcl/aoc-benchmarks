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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 24.9 ± 5.3 | 12.9 | 40.1 | 12.54 ± 8.25 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 28.1 ± 6.4 | 14.4 | 51.6 | 14.16 ± 9.39 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 25.6 ± 4.5 | 13.6 | 38.4 | 12.90 ± 8.34 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 26.2 ± 5.7 | 13.2 | 41.6 | 13.19 ± 8.70 |
| `aspidites-solver/aoc -i input-pting -d 3` | 26.3 ± 4.0 | 13.5 | 46.1 | 13.25 ± 8.50 |
| `kcen/2022/03/solve input-aspidites` | 391.1 ± 82.4 | 318.7 | 552.5 | 196.85 ± 129.42 |
| `kcen/2022/03/solve input-kcen` | 584.2 ± 287.6 | 361.7 | 1189.9 | 294.07 ± 233.45 |
| `kcen/2022/03/solve input-lanjian` | 344.1 ± 61.6 | 290.9 | 505.4 | 173.24 ± 112.25 |
| `kcen/2022/03/solve input-mattcl` | 466.2 ± 55.4 | 398.1 | 545.3 | 234.66 ± 148.78 |
| `kcen/2022/03/solve input-pting` | 372.5 ± 40.7 | 313.1 | 437.4 | 187.53 ± 118.57 |
| `lanjian/day_03 input-aspidites` | 2.0 ± 1.2 | 0.5 | 12.0 | 1.00 |
| `lanjian/day_03 input-kcen` | 3.1 ± 1.3 | 0.6 | 10.8 | 1.56 ± 1.19 |
| `lanjian/day_03 input-lanjian` | 3.8 ± 1.5 | 1.1 | 8.8 | 1.93 ± 1.41 |
| `lanjian/day_03 input-mattcl` | 3.5 ± 1.6 | 0.7 | 14.2 | 1.77 ± 1.38 |
| `lanjian/day_03 input-pting` | 2.6 ± 1.4 | 0.7 | 8.2 | 1.33 ± 1.10 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.4 ± 1.6 | 0.8 | 9.8 | 1.70 ± 1.33 |
| `mattcl-solver/aoc run 3 input-kcen` | 3.7 ± 1.5 | 0.6 | 13.6 | 1.84 ± 1.38 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.5 ± 1.6 | 0.5 | 12.2 | 1.76 ± 1.37 |
| `mattcl-solver/aoc run 3 input-mattcl` | 4.6 ± 2.3 | 1.3 | 20.8 | 2.31 ± 1.86 |
| `mattcl-solver/aoc run 3 input-pting` | 3.3 ± 1.6 | 0.7 | 8.2 | 1.64 ± 1.29 |
| `python pting/day03.py input-aspidites` | 60.1 ± 31.4 | 42.7 | 148.2 | 30.27 ± 24.61 |
| `python pting/day03.py input-kcen` | 53.9 ± 19.7 | 38.1 | 117.7 | 27.12 ± 19.59 |
| `python pting/day03.py input-lanjian` | 65.7 ± 30.5 | 37.3 | 154.1 | 33.08 ± 25.70 |
| `python pting/day03.py input-mattcl` | 63.1 ± 32.0 | 41.1 | 202.5 | 31.74 ± 25.50 |
| `python pting/day03.py input-pting` | 48.2 ± 7.0 | 39.6 | 75.7 | 24.25 ± 15.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
