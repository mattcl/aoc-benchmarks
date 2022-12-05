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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.5 ± 3.4 | 11.3 | 28.1 | 13.52 ± 7.43 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.2 ± 2.9 | 11.8 | 26.1 | 13.22 ± 7.08 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 14.3 ± 3.9 | 11.4 | 25.8 | 14.33 ± 8.04 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.0 ± 2.8 | 11.4 | 24.2 | 13.08 ± 7.00 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.7 ± 3.1 | 11.8 | 26.2 | 13.81 ± 7.45 |
| `kcen/2022/03/solve input-aspidites` | 254.5 ± 19.8 | 224.6 | 293.9 | 255.72 ± 126.72 |
| `kcen/2022/03/solve input-kcen` | 252.3 ± 16.2 | 224.0 | 281.4 | 253.52 ± 125.14 |
| `kcen/2022/03/solve input-lanjian` | 243.9 ± 17.8 | 219.0 | 276.8 | 245.02 ± 121.23 |
| `kcen/2022/03/solve input-mattcl` | 271.4 ± 35.1 | 232.4 | 364.2 | 272.68 ± 138.03 |
| `kcen/2022/03/solve input-pting` | 276.8 ± 26.5 | 219.0 | 322.2 | 278.06 ± 138.66 |
| `lanjian/day_03 input-aspidites` | 1.0 ± 0.5 | 0.4 | 6.6 | 1.00 |
| `lanjian/day_03 input-kcen` | 1.5 ± 0.6 | 0.7 | 4.5 | 1.54 ± 0.95 |
| `lanjian/day_03 input-lanjian` | 1.6 ± 0.7 | 0.5 | 6.5 | 1.59 ± 1.07 |
| `lanjian/day_03 input-mattcl` | 1.5 ± 0.7 | 0.4 | 4.5 | 1.51 ± 1.04 |
| `lanjian/day_03 input-pting` | 1.3 ± 0.7 | 0.6 | 9.9 | 1.34 ± 0.95 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.4 ± 0.7 | 0.6 | 9.9 | 1.44 ± 1.00 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.6 ± 0.5 | 0.6 | 5.3 | 1.58 ± 0.91 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.3 ± 0.4 | 0.5 | 3.9 | 1.27 ± 0.75 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.9 ± 1.0 | 0.6 | 12.2 | 1.96 ± 1.39 |
| `mattcl-solver/aoc run 3 input-pting` | 1.2 ± 0.6 | 0.5 | 4.0 | 1.21 ± 0.86 |
| `python pting/day03.py input-aspidites` | 36.4 ± 5.8 | 29.9 | 64.2 | 36.56 ± 18.82 |
| `python pting/day03.py input-kcen` | 42.3 ± 12.0 | 28.5 | 80.3 | 42.52 ± 24.04 |
| `python pting/day03.py input-lanjian` | 34.1 ± 5.0 | 28.3 | 52.0 | 34.24 ± 17.50 |
| `python pting/day03.py input-mattcl` | 36.8 ± 8.4 | 28.4 | 69.2 | 36.93 ± 19.96 |
| `python pting/day03.py input-pting` | 39.0 ± 8.0 | 28.5 | 70.1 | 39.19 ± 20.77 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
