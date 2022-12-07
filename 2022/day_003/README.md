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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 26.3 ± 11.0 | 12.9 | 133.6 | 12.31 ± 8.40 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.6 ± 3.2 | 13.9 | 36.5 | 11.99 ± 6.65 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 26.0 ± 4.9 | 13.6 | 61.3 | 12.17 ± 6.96 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 24.5 ± 5.3 | 12.7 | 42.0 | 11.47 ± 6.67 |
| `aspidites-solver/aoc -i input-pting -d 3` | 24.1 ± 4.4 | 13.2 | 42.6 | 11.30 ± 6.44 |
| `kcen/2022/03/solve input-aspidites` | 360.8 ± 41.9 | 308.6 | 447.2 | 168.92 ± 93.30 |
| `kcen/2022/03/solve input-kcen` | 361.4 ± 25.5 | 326.9 | 409.4 | 169.21 ± 92.14 |
| `kcen/2022/03/solve input-lanjian` | 384.0 ± 34.4 | 335.4 | 433.9 | 179.82 ± 98.42 |
| `kcen/2022/03/solve input-mattcl` | 361.0 ± 23.1 | 318.1 | 393.7 | 169.04 ± 91.92 |
| `kcen/2022/03/solve input-pting` | 421.7 ± 26.0 | 378.6 | 459.0 | 197.45 ± 107.31 |
| `lanjian/day_03 input-aspidites` | 3.2 ± 1.5 | 0.7 | 9.3 | 1.48 ± 1.07 |
| `lanjian/day_03 input-kcen` | 2.5 ± 1.2 | 0.5 | 8.2 | 1.16 ± 0.85 |
| `lanjian/day_03 input-lanjian` | 2.5 ± 1.1 | 0.7 | 8.7 | 1.16 ± 0.80 |
| `lanjian/day_03 input-mattcl` | 6.1 ± 5.9 | 0.7 | 35.7 | 2.84 ± 3.16 |
| `lanjian/day_03 input-pting` | 2.5 ± 1.4 | 0.4 | 14.2 | 1.15 ± 0.89 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.3 ± 1.4 | 0.7 | 10.7 | 1.56 ± 1.07 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.1 ± 1.2 | 0.5 | 8.1 | 1.00 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.7 ± 1.2 | 0.7 | 6.7 | 1.25 ± 0.87 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.6 ± 2.1 | 0.5 | 17.3 | 1.20 ± 1.16 |
| `mattcl-solver/aoc run 3 input-pting` | 2.4 ± 1.1 | 0.7 | 8.1 | 1.12 ± 0.79 |
| `python pting/day03.py input-aspidites` | 53.4 ± 9.4 | 41.5 | 90.8 | 25.01 ± 14.20 |
| `python pting/day03.py input-kcen` | 64.4 ± 24.0 | 41.1 | 146.4 | 30.13 ± 19.79 |
| `python pting/day03.py input-lanjian` | 57.2 ± 7.1 | 45.4 | 73.6 | 26.77 ± 14.83 |
| `python pting/day03.py input-mattcl` | 55.8 ± 10.6 | 40.3 | 82.7 | 26.11 ± 14.94 |
| `python pting/day03.py input-pting` | 52.6 ± 7.4 | 38.9 | 74.0 | 24.65 ± 13.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
