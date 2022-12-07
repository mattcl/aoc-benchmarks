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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 15.6 ± 3.1 | 12.6 | 32.8 | 5.53 ± 3.98 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 16.1 ± 3.1 | 12.5 | 29.8 | 5.68 ± 4.09 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 14.9 ± 2.5 | 12.4 | 26.7 | 5.27 ± 3.76 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.0 ± 2.2 | 12.5 | 27.1 | 5.31 ± 3.76 |
| `aspidites-solver/aoc -i input-pting -d 2` | 15.5 ± 2.6 | 12.2 | 28.2 | 5.46 ± 3.89 |
| `kcen/2022/02/solve input-aspidites` | 3.5 ± 1.6 | 1.1 | 10.9 | 1.22 ± 1.03 |
| `kcen/2022/02/solve input-kcen` | 4.0 ± 1.8 | 0.9 | 14.9 | 1.40 ± 1.17 |
| `kcen/2022/02/solve input-lanjian` | 3.7 ± 2.3 | 0.8 | 24.5 | 1.31 ± 1.23 |
| `kcen/2022/02/solve input-mattcl` | 3.8 ± 2.3 | 1.1 | 25.5 | 1.35 ± 1.23 |
| `kcen/2022/02/solve input-pting` | 3.6 ± 2.4 | 0.9 | 22.5 | 1.26 ± 1.21 |
| `lanjian/day_02 input-aspidites` | 5.8 ± 2.9 | 1.9 | 15.9 | 2.04 ± 1.74 |
| `lanjian/day_02 input-kcen` | 2.8 ± 2.0 | 0.8 | 10.8 | 1.00 |
| `lanjian/day_02 input-lanjian` | 4.6 ± 2.2 | 1.6 | 13.6 | 1.63 ± 1.38 |
| `lanjian/day_02 input-mattcl` | 3.8 ± 2.1 | 0.7 | 11.7 | 1.35 ± 1.20 |
| `lanjian/day_02 input-pting` | 6.7 ± 10.2 | 0.8 | 137.3 | 2.38 ± 3.95 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.8 ± 2.1 | 1.0 | 20.2 | 1.33 ± 1.19 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.5 ± 2.0 | 1.0 | 22.5 | 1.24 ± 1.10 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.5 ± 2.1 | 0.6 | 18.5 | 1.22 ± 1.13 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.1 ± 1.6 | 0.7 | 10.8 | 1.08 ± 0.94 |
| `mattcl-solver/aoc run 2 input-pting` | 3.3 ± 2.2 | 0.5 | 20.4 | 1.15 ± 1.10 |
| `python pting/day02.py input-aspidites` | 57.6 ± 21.8 | 39.3 | 142.5 | 20.34 ± 16.06 |
| `python pting/day02.py input-kcen` | 55.3 ± 27.0 | 35.8 | 167.0 | 19.54 ± 16.55 |
| `python pting/day02.py input-lanjian` | 54.9 ± 23.4 | 37.5 | 129.1 | 19.39 ± 15.77 |
| `python pting/day02.py input-mattcl` | 63.5 ± 29.6 | 41.9 | 174.5 | 22.43 ± 18.72 |
| `python pting/day02.py input-pting` | 69.6 ± 30.6 | 41.3 | 159.0 | 24.58 ± 20.17 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
