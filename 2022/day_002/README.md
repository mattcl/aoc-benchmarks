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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.7 ± 2.7 | 12.2 | 33.9 | 6.56 ± 4.92 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 14.4 ± 2.7 | 12.2 | 26.3 | 6.41 ± 4.82 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.1 ± 2.5 | 12.5 | 27.4 | 6.71 ± 5.01 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.4 ± 3.6 | 12.1 | 30.6 | 6.85 ± 5.25 |
| `aspidites-solver/aoc -i input-pting -d 2` | 15.0 ± 2.9 | 12.4 | 33.8 | 6.69 ± 5.04 |
| `kcen/2022/02/solve input-aspidites` | 5.2 ± 6.0 | 0.2 | 55.1 | 2.31 ± 3.17 |
| `kcen/2022/02/solve input-kcen` | 2.7 ± 1.3 | 0.0 | 10.6 | 1.19 ± 1.04 |
| `kcen/2022/02/solve input-lanjian` | 2.2 ± 1.6 | 0.1 | 16.4 | 1.00 |
| `kcen/2022/02/solve input-mattcl` | 2.6 ± 2.1 | 0.0 | 30.7 | 1.18 ± 1.28 |
| `kcen/2022/02/solve input-pting` | 2.4 ± 1.3 | 0.4 | 8.1 | 1.07 ± 0.96 |
| `lanjian/day_02 input-aspidites` | 2.8 ± 1.2 | 0.6 | 9.9 | 1.25 ± 1.07 |
| `lanjian/day_02 input-kcen` | 3.0 ± 1.4 | 0.9 | 10.1 | 1.34 ± 1.16 |
| `lanjian/day_02 input-lanjian` | 3.3 ± 1.5 | 0.8 | 14.0 | 1.49 ± 1.26 |
| `lanjian/day_02 input-mattcl` | 3.3 ± 2.1 | 0.9 | 22.5 | 1.49 ± 1.44 |
| `lanjian/day_02 input-pting` | 2.3 ± 1.3 | 0.5 | 12.1 | 1.02 ± 0.94 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.8 ± 1.7 | 0.6 | 16.1 | 1.24 ± 1.19 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.2 ± 1.4 | 0.7 | 12.0 | 1.42 ± 1.20 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.4 ± 1.2 | 0.4 | 10.2 | 1.07 ± 0.95 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.4 ± 1.5 | 0.8 | 11.2 | 1.53 ± 1.31 |
| `mattcl-solver/aoc run 2 input-pting` | 2.7 ± 1.5 | 0.4 | 9.6 | 1.21 ± 1.12 |
| `python pting/day02.py input-aspidites` | 51.8 ± 6.6 | 38.8 | 67.5 | 23.06 ± 17.06 |
| `python pting/day02.py input-kcen` | 53.1 ± 9.9 | 40.6 | 86.2 | 23.65 ± 17.78 |
| `python pting/day02.py input-lanjian` | 57.6 ± 10.2 | 44.3 | 84.7 | 25.68 ± 19.25 |
| `python pting/day02.py input-mattcl` | 57.7 ± 10.0 | 39.6 | 89.8 | 25.70 ± 19.24 |
| `python pting/day02.py input-pting` | 52.2 ± 7.8 | 43.3 | 86.2 | 23.25 ± 17.29 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
