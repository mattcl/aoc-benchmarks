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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.4 ± 1.2 | 11.7 | 23.3 | 13.42 ± 3.88 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.0 ± 2.3 | 11.7 | 24.2 | 14.06 ± 4.55 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.7 ± 2.0 | 11.7 | 23.8 | 13.76 ± 4.34 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.7 ± 1.4 | 11.9 | 25.8 | 13.72 ± 4.00 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.1 ± 2.5 | 11.8 | 33.9 | 14.15 ± 4.71 |
| `kcen/2022/03/solve input-aspidites` | 223.3 ± 19.0 | 198.8 | 268.3 | 241.71 ± 68.77 |
| `kcen/2022/03/solve input-kcen` | 218.1 ± 6.7 | 207.8 | 231.7 | 236.13 ± 64.52 |
| `kcen/2022/03/solve input-lanjian` | 230.8 ± 14.4 | 211.2 | 260.4 | 249.88 ± 69.60 |
| `kcen/2022/03/solve input-mattcl` | 248.2 ± 17.2 | 227.1 | 275.7 | 268.75 ± 75.31 |
| `kcen/2022/03/solve input-pting` | 250.6 ± 16.5 | 234.9 | 280.1 | 271.35 ± 75.82 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.4 | 0.6 | 4.1 | 1.42 ± 0.61 |
| `lanjian/day_03 input-kcen` | 1.1 ± 0.3 | 0.7 | 7.1 | 1.18 ± 0.49 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.5 | 0.6 | 6.6 | 1.30 ± 0.66 |
| `lanjian/day_03 input-mattcl` | 0.9 ± 0.3 | 0.6 | 3.3 | 1.00 |
| `lanjian/day_03 input-pting` | 1.1 ± 0.3 | 0.6 | 5.2 | 1.21 ± 0.49 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.5 ± 0.5 | 0.7 | 7.5 | 1.62 ± 0.67 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.4 ± 0.4 | 0.7 | 4.6 | 1.57 ± 0.60 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.3 ± 0.3 | 0.8 | 3.4 | 1.38 ± 0.53 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.3 ± 0.5 | 0.6 | 5.4 | 1.40 ± 0.69 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.3 | 0.7 | 3.6 | 1.40 ± 0.52 |
| `python pting/day03.py input-aspidites` | 34.1 ± 3.7 | 29.8 | 50.9 | 36.94 ± 10.82 |
| `python pting/day03.py input-kcen` | 34.0 ± 4.6 | 28.8 | 50.1 | 36.82 ± 11.18 |
| `python pting/day03.py input-lanjian` | 34.1 ± 3.0 | 29.9 | 44.9 | 36.96 ± 10.55 |
| `python pting/day03.py input-mattcl` | 33.0 ± 3.8 | 28.6 | 44.4 | 35.73 ± 10.52 |
| `python pting/day03.py input-pting` | 32.5 ± 2.8 | 29.2 | 46.8 | 35.17 ± 10.01 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
