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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.9 ± 5.2 | 11.9 | 74.9 | 15.13 ± 17.03 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 23.6 ± 19.0 | 11.2 | 102.4 | 23.99 ± 32.14 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 25.8 ± 13.7 | 12.0 | 70.4 | 26.18 ± 31.26 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 17.4 ± 6.8 | 12.5 | 58.2 | 17.72 ± 20.17 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.7 ± 2.8 | 11.8 | 26.6 | 14.92 ± 16.21 |
| `kcen/2022/02/solve input-aspidites` | 1.0 ± 1.1 | 0.0 | 11.2 | 1.00 |
| `kcen/2022/02/solve input-kcen` | 2.6 ± 2.0 | 0.1 | 35.0 | 2.67 ± 3.49 |
| `kcen/2022/02/solve input-lanjian` | 2.7 ± 1.8 | 0.0 | 21.3 | 2.78 ± 3.47 |
| `kcen/2022/02/solve input-mattcl` | 3.0 ± 1.8 | 0.3 | 19.3 | 3.02 ± 3.73 |
| `kcen/2022/02/solve input-pting` | 1.5 ± 1.2 | 0.0 | 12.8 | 1.48 ± 2.00 |
| `lanjian/day_02 input-aspidites` | 2.9 ± 1.4 | 0.6 | 15.6 | 2.96 ± 3.49 |
| `lanjian/day_02 input-kcen` | 2.6 ± 1.3 | 0.2 | 7.2 | 2.63 ± 3.12 |
| `lanjian/day_02 input-lanjian` | 2.9 ± 1.3 | 0.8 | 14.4 | 2.93 ± 3.39 |
| `lanjian/day_02 input-mattcl` | 3.9 ± 1.9 | 0.9 | 25.1 | 4.01 ± 4.71 |
| `lanjian/day_02 input-pting` | 3.0 ± 3.2 | 0.4 | 44.5 | 3.04 ± 4.61 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.3 ± 1.8 | 0.0 | 17.7 | 3.34 ± 4.02 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.3 ± 1.9 | 0.0 | 21.5 | 2.33 ± 3.18 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.8 ± 1.6 | 0.9 | 12.4 | 3.88 ± 4.44 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.4 ± 2.2 | 0.4 | 21.1 | 3.42 ± 4.31 |
| `mattcl-solver/aoc run 2 input-pting` | 3.3 ± 1.7 | 0.6 | 15.2 | 3.32 ± 3.96 |
| `python pting/day02.py input-aspidites` | 56.9 ± 15.7 | 42.5 | 130.5 | 57.82 ± 63.88 |
| `python pting/day02.py input-kcen` | 53.1 ± 8.4 | 40.9 | 76.7 | 53.96 ± 58.36 |
| `python pting/day02.py input-lanjian` | 58.7 ± 9.6 | 45.2 | 85.3 | 59.63 ± 64.53 |
| `python pting/day02.py input-mattcl` | 98.6 ± 52.8 | 46.7 | 266.0 | 100.12 ± 119.78 |
| `python pting/day02.py input-pting` | 53.7 ± 11.6 | 40.2 | 105.5 | 54.57 ± 59.54 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
