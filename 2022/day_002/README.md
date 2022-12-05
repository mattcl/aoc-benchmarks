# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 2)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.7 ± 0.7 | 11.5 | 15.2 | 10.66 ± 5.09 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.2 ± 0.7 | 10.9 | 14.7 | 10.27 ± 4.90 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.3 ± 1.1 | 10.9 | 24.6 | 10.33 ± 4.98 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 11.9 ± 1.3 | 10.9 | 22.8 | 10.00 ± 4.85 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.3 ± 0.8 | 11.1 | 14.8 | 10.34 ± 4.94 |
| `kcen/2022/02/solve input-aspidites` | 2.0 ± 0.7 | 0.9 | 4.8 | 1.72 ± 1.03 |
| `kcen/2022/02/solve input-kcen` | 1.8 ± 0.7 | 0.9 | 4.5 | 1.53 ± 0.94 |
| `kcen/2022/02/solve input-lanjian` | 1.3 ± 0.8 | 0.5 | 7.9 | 1.07 ± 0.84 |
| `kcen/2022/02/solve input-mattcl` | 1.2 ± 0.6 | 0.5 | 5.0 | 1.00 |
| `kcen/2022/02/solve input-pting` | 1.5 ± 0.8 | 0.6 | 5.3 | 1.26 ± 0.89 |
| `lanjian/day_02 input-aspidites` | 2.2 ± 0.9 | 0.9 | 5.1 | 1.89 ± 1.18 |
| `lanjian/day_02 input-kcen` | 1.8 ± 0.9 | 0.8 | 8.8 | 1.50 ± 1.02 |
| `lanjian/day_02 input-lanjian` | 1.4 ± 0.5 | 0.9 | 3.9 | 1.17 ± 0.70 |
| `lanjian/day_02 input-mattcl` | 2.5 ± 1.2 | 0.9 | 14.9 | 2.07 ± 1.42 |
| `lanjian/day_02 input-pting` | 2.0 ± 0.8 | 0.9 | 7.1 | 1.67 ± 1.05 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.2 ± 1.1 | 0.7 | 9.7 | 1.86 ± 1.31 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.8 | 0.6 | 9.0 | 1.13 ± 0.84 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 0.5 | 0.7 | 3.9 | 1.24 ± 0.73 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.4 ± 0.5 | 0.7 | 4.7 | 1.17 ± 0.71 |
| `mattcl-solver/aoc run 2 input-pting` | 1.8 ± 0.7 | 0.8 | 6.1 | 1.51 ± 0.93 |
| `python pting/day02.py input-aspidites` | 34.9 ± 6.4 | 27.9 | 59.4 | 29.40 ± 14.94 |
| `python pting/day02.py input-kcen` | 37.8 ± 9.3 | 27.4 | 75.5 | 31.79 ± 16.98 |
| `python pting/day02.py input-lanjian` | 36.0 ± 6.0 | 30.4 | 61.3 | 30.32 ± 15.23 |
| `python pting/day02.py input-mattcl` | 36.6 ± 6.9 | 28.2 | 62.3 | 30.81 ± 15.71 |
| `python pting/day02.py input-pting` | 34.7 ± 5.1 | 28.4 | 59.1 | 29.18 ± 14.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
