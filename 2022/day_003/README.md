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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 25.0 ± 1.7 | 13.8 | 31.8 | 18.61 ± 12.58 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.8 ± 2.1 | 23.6 | 36.0 | 19.16 ± 12.98 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 25.4 ± 2.5 | 23.2 | 47.5 | 18.88 ± 12.83 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 23.7 ± 3.8 | 13.0 | 34.9 | 17.61 ± 12.18 |
| `aspidites-solver/aoc -i input-pting -d 3` | 26.7 ± 4.1 | 23.6 | 58.9 | 19.87 ± 13.70 |
| `kcen/2022/03/solve input-aspidites` | 389.8 ± 31.6 | 352.6 | 447.5 | 289.89 ± 196.44 |
| `kcen/2022/03/solve input-kcen` | 414.3 ± 47.2 | 360.1 | 481.9 | 308.13 ± 210.25 |
| `kcen/2022/03/solve input-lanjian` | 366.0 ± 14.3 | 351.5 | 401.0 | 272.22 ± 183.45 |
| `kcen/2022/03/solve input-mattcl` | 381.2 ± 28.4 | 344.4 | 430.1 | 283.52 ± 191.91 |
| `kcen/2022/03/solve input-pting` | 429.9 ± 32.4 | 380.7 | 472.5 | 319.76 ± 216.47 |
| `lanjian/day_03 input-aspidites` | 2.5 ± 1.3 | 0.5 | 13.3 | 1.84 ± 1.56 |
| `lanjian/day_03 input-kcen` | 2.3 ± 1.6 | 0.3 | 16.1 | 1.68 ± 1.64 |
| `lanjian/day_03 input-lanjian` | 1.3 ± 0.9 | 0.2 | 6.4 | 1.00 |
| `lanjian/day_03 input-mattcl` | 1.5 ± 0.9 | 0.3 | 6.8 | 1.11 ± 0.98 |
| `lanjian/day_03 input-pting` | 2.4 ± 1.2 | 0.6 | 11.7 | 1.78 ± 1.51 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.7 ± 3.7 | 0.5 | 31.9 | 2.76 ± 3.34 |
| `mattcl-solver/aoc run 3 input-kcen` | 3.4 ± 1.6 | 1.1 | 13.4 | 2.55 ± 2.09 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.6 ± 1.1 | 0.7 | 9.7 | 1.92 ± 1.52 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.3 ± 1.6 | 0.7 | 35.5 | 1.73 ± 1.68 |
| `mattcl-solver/aoc run 3 input-pting` | 2.5 ± 1.0 | 0.8 | 12.1 | 1.87 ± 1.47 |
| `python pting/day03.py input-aspidites` | 55.3 ± 6.2 | 45.7 | 74.7 | 41.12 ± 28.05 |
| `python pting/day03.py input-kcen` | 57.6 ± 7.8 | 46.5 | 77.8 | 42.85 ± 29.40 |
| `python pting/day03.py input-lanjian` | 56.0 ± 8.4 | 44.1 | 84.6 | 41.66 ± 28.71 |
| `python pting/day03.py input-mattcl` | 59.4 ± 14.4 | 42.7 | 137.2 | 44.17 ± 31.59 |
| `python pting/day03.py input-pting` | 60.3 ± 8.0 | 48.5 | 78.5 | 44.86 ± 30.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
