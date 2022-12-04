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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.8 ± 2.3 | 11.5 | 23.9 | 10.90 ± 5.29 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.3 ± 1.4 | 11.6 | 23.1 | 10.48 ± 4.89 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.9 ± 2.0 | 11.6 | 25.0 | 10.94 ± 5.25 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.1 ± 1.3 | 11.9 | 23.6 | 11.11 ± 5.15 |
| `aspidites-solver/aoc -i input-pting -d 3` | 14.2 ± 4.5 | 11.7 | 37.1 | 12.04 ± 6.64 |
| `kcen/2022/03/solve input-aspidites` | 228.6 ± 17.9 | 206.2 | 265.4 | 194.32 ± 89.16 |
| `kcen/2022/03/solve input-kcen` | 223.8 ± 17.0 | 204.0 | 255.0 | 190.18 ± 87.19 |
| `kcen/2022/03/solve input-lanjian` | 244.4 ± 19.9 | 213.7 | 275.9 | 207.72 ± 95.43 |
| `kcen/2022/03/solve input-mattcl` | 224.4 ± 12.3 | 201.9 | 245.3 | 190.72 ± 86.86 |
| `kcen/2022/03/solve input-pting` | 230.6 ± 12.8 | 215.9 | 260.1 | 196.01 ± 89.29 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.5 | 0.6 | 5.1 | 1.13 ± 0.65 |
| `lanjian/day_03 input-kcen` | 1.2 ± 0.5 | 0.6 | 7.1 | 1.05 ± 0.65 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.5 | 0.6 | 8.0 | 1.00 |
| `lanjian/day_03 input-mattcl` | 1.3 ± 0.4 | 0.6 | 6.9 | 1.09 ± 0.62 |
| `lanjian/day_03 input-pting` | 1.3 ± 0.5 | 0.6 | 5.7 | 1.09 ± 0.65 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.7 ± 0.9 | 0.6 | 9.8 | 1.45 ± 0.99 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.6 ± 1.0 | 0.7 | 12.4 | 1.40 ± 1.04 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.6 | 0.7 | 11.8 | 1.19 ± 0.73 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.4 ± 0.5 | 0.6 | 4.7 | 1.19 ± 0.67 |
| `mattcl-solver/aoc run 3 input-pting` | 1.4 ± 0.5 | 0.6 | 4.7 | 1.22 ± 0.69 |
| `python pting/day03.py input-aspidites` | 31.4 ± 2.6 | 27.5 | 42.0 | 26.69 ± 12.26 |
| `python pting/day03.py input-kcen` | 33.4 ± 3.4 | 27.7 | 42.9 | 28.37 ± 13.15 |
| `python pting/day03.py input-lanjian` | 39.5 ± 9.3 | 29.0 | 90.4 | 33.55 ± 17.10 |
| `python pting/day03.py input-mattcl` | 36.1 ± 6.1 | 27.5 | 64.9 | 30.65 ± 14.79 |
| `python pting/day03.py input-pting` | 37.8 ± 5.4 | 30.2 | 55.3 | 32.11 ± 15.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
