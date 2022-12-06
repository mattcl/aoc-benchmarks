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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.6 ± 2.2 | 12.5 | 31.3 | 4.97 ± 2.01 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 14.8 ± 2.0 | 12.7 | 31.1 | 5.03 ± 2.01 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.5 ± 2.8 | 12.9 | 34.6 | 5.26 ± 2.20 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.4 ± 2.2 | 12.9 | 28.0 | 5.25 ± 2.11 |
| `aspidites-solver/aoc -i input-pting -d 2` | 15.3 ± 2.4 | 12.8 | 27.8 | 5.21 ± 2.12 |
| `kcen/2022/02/solve input-aspidites` | 2.9 ± 1.4 | 1.1 | 16.9 | 1.00 ± 0.61 |
| `kcen/2022/02/solve input-kcen` | 2.9 ± 1.1 | 1.0 | 10.7 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 3.5 ± 1.5 | 1.1 | 14.2 | 1.20 ± 0.68 |
| `kcen/2022/02/solve input-mattcl` | 4.3 ± 2.4 | 1.2 | 29.2 | 1.46 ± 0.99 |
| `kcen/2022/02/solve input-pting` | 3.5 ± 1.5 | 1.0 | 15.7 | 1.19 ± 0.67 |
| `lanjian/day_02 input-aspidites` | 3.8 ± 1.7 | 1.5 | 12.5 | 1.28 ± 0.76 |
| `lanjian/day_02 input-kcen` | 3.6 ± 1.2 | 1.6 | 10.5 | 1.23 ± 0.61 |
| `lanjian/day_02 input-lanjian` | 4.0 ± 1.2 | 1.7 | 15.1 | 1.35 ± 0.66 |
| `lanjian/day_02 input-mattcl` | 3.9 ± 1.5 | 1.5 | 13.1 | 1.33 ± 0.72 |
| `lanjian/day_02 input-pting` | 4.2 ± 1.4 | 1.3 | 16.9 | 1.42 ± 0.71 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.7 ± 1.3 | 1.5 | 12.9 | 1.26 ± 0.66 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.7 ± 1.0 | 1.5 | 10.1 | 1.24 ± 0.58 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.7 ± 1.1 | 1.5 | 9.3 | 1.24 ± 0.61 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.5 ± 1.4 | 1.2 | 14.8 | 1.18 ± 0.66 |
| `mattcl-solver/aoc run 2 input-pting` | 3.6 ± 1.2 | 1.1 | 11.6 | 1.21 ± 0.61 |
| `python pting/day02.py input-aspidites` | 62.1 ± 7.2 | 51.3 | 85.5 | 21.11 ± 8.31 |
| `python pting/day02.py input-kcen` | 59.0 ± 5.6 | 48.8 | 76.0 | 20.07 ± 7.78 |
| `python pting/day02.py input-lanjian` | 65.3 ± 10.4 | 46.6 | 94.4 | 22.20 ± 9.07 |
| `python pting/day02.py input-mattcl` | 66.0 ± 13.6 | 47.4 | 113.0 | 22.46 ± 9.63 |
| `python pting/day02.py input-pting` | 60.1 ± 6.5 | 49.7 | 80.8 | 20.44 ± 8.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
