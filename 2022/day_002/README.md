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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.6 ± 2.1 | 12.9 | 29.4 | 6.58 ± 2.78 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 15.8 ± 3.0 | 12.3 | 31.9 | 7.13 ± 3.15 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 13.8 ± 1.5 | 12.0 | 28.0 | 6.23 ± 2.57 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 22.2 ± 18.3 | 12.4 | 170.0 | 10.00 ± 9.17 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.0 ± 2.5 | 12.1 | 35.8 | 6.30 ± 2.75 |
| `kcen/2022/02/solve input-aspidites` | 2.9 ± 1.2 | 0.9 | 9.9 | 1.28 ± 0.73 |
| `kcen/2022/02/solve input-kcen` | 4.2 ± 1.6 | 1.1 | 12.8 | 1.89 ± 1.04 |
| `kcen/2022/02/solve input-lanjian` | 3.0 ± 1.2 | 1.0 | 12.2 | 1.34 ± 0.76 |
| `kcen/2022/02/solve input-mattcl` | 3.1 ± 1.8 | 1.0 | 18.1 | 1.38 ± 0.99 |
| `kcen/2022/02/solve input-pting` | 2.7 ± 1.2 | 1.0 | 10.5 | 1.21 ± 0.71 |
| `lanjian/day_02 input-aspidites` | 2.8 ± 1.1 | 1.2 | 9.4 | 1.27 ± 0.72 |
| `lanjian/day_02 input-kcen` | 4.8 ± 2.0 | 1.4 | 16.3 | 2.15 ± 1.23 |
| `lanjian/day_02 input-lanjian` | 3.6 ± 1.1 | 1.4 | 9.4 | 1.61 ± 0.82 |
| `lanjian/day_02 input-mattcl` | 2.3 ± 0.9 | 1.1 | 9.8 | 1.03 ± 0.57 |
| `lanjian/day_02 input-pting` | 3.2 ± 1.2 | 1.2 | 11.5 | 1.46 ± 0.79 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.0 ± 1.1 | 1.0 | 10.6 | 1.36 ± 0.74 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.2 ± 0.9 | 0.9 | 8.0 | 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.3 ± 0.9 | 1.0 | 9.3 | 1.02 ± 0.59 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.8 ± 1.4 | 1.4 | 17.9 | 1.70 ± 0.92 |
| `mattcl-solver/aoc run 2 input-pting` | 2.8 ± 1.1 | 1.1 | 7.1 | 1.27 ± 0.70 |
| `python pting/day02.py input-aspidites` | 49.9 ± 8.0 | 35.5 | 75.0 | 22.49 ± 9.65 |
| `python pting/day02.py input-kcen` | 61.9 ± 26.4 | 35.8 | 148.5 | 27.87 ± 16.28 |
| `python pting/day02.py input-lanjian` | 50.2 ± 8.8 | 39.2 | 81.8 | 22.61 ± 9.83 |
| `python pting/day02.py input-mattcl` | 51.2 ± 5.5 | 43.1 | 68.2 | 23.06 ± 9.51 |
| `python pting/day02.py input-pting` | 50.6 ± 9.1 | 35.6 | 73.3 | 22.81 ± 9.96 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
