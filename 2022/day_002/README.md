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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 13.5 ± 1.8 | 11.9 | 28.6 | 7.53 ± 3.88 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 13.4 ± 1.0 | 11.7 | 17.8 | 7.51 ± 3.78 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 13.8 ± 2.6 | 12.0 | 35.1 | 7.74 ± 4.12 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.5 ± 1.7 | 11.8 | 27.4 | 7.54 ± 3.89 |
| `aspidites-solver/aoc -i input-pting -d 2` | 13.4 ± 1.1 | 12.0 | 22.3 | 7.51 ± 3.79 |
| `kcen/2022/02/solve input-aspidites` | 1.8 ± 0.9 | 0.5 | 11.2 | 1.00 |
| `kcen/2022/02/solve input-kcen` | 2.3 ± 1.2 | 0.6 | 11.0 | 1.31 ± 0.92 |
| `kcen/2022/02/solve input-lanjian` | 2.1 ± 1.0 | 0.5 | 11.9 | 1.15 ± 0.80 |
| `kcen/2022/02/solve input-mattcl` | 1.9 ± 1.1 | 0.5 | 9.3 | 1.04 ± 0.81 |
| `kcen/2022/02/solve input-pting` | 3.4 ± 2.3 | 1.0 | 21.2 | 1.89 ± 1.59 |
| `lanjian/day_02 input-aspidites` | 2.0 ± 0.7 | 0.8 | 7.1 | 1.10 ± 0.68 |
| `lanjian/day_02 input-kcen` | 3.4 ± 4.9 | 1.0 | 142.2 | 1.90 ± 2.91 |
| `lanjian/day_02 input-lanjian` | 1.9 ± 0.8 | 0.8 | 5.3 | 1.08 ± 0.70 |
| `lanjian/day_02 input-mattcl` | 3.1 ± 1.6 | 1.1 | 14.8 | 1.73 ± 1.26 |
| `lanjian/day_02 input-pting` | 2.1 ± 0.8 | 0.7 | 5.4 | 1.18 ± 0.73 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.9 ± 1.1 | 0.5 | 12.6 | 1.06 ± 0.80 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.3 ± 1.0 | 0.6 | 6.6 | 1.29 ± 0.84 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.1 ± 1.3 | 0.5 | 22.7 | 1.18 ± 0.95 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.3 ± 1.3 | 0.6 | 13.8 | 1.27 ± 0.95 |
| `mattcl-solver/aoc run 2 input-pting` | 2.0 ± 1.0 | 0.5 | 12.3 | 1.13 ± 0.79 |
| `python pting/day02.py input-aspidites` | 46.0 ± 5.5 | 36.5 | 62.6 | 25.72 ± 13.19 |
| `python pting/day02.py input-kcen` | 54.4 ± 7.9 | 43.1 | 79.1 | 30.40 ± 15.79 |
| `python pting/day02.py input-lanjian` | 45.3 ± 5.9 | 36.4 | 70.8 | 25.31 ± 13.04 |
| `python pting/day02.py input-mattcl` | 47.1 ± 5.7 | 37.4 | 67.0 | 26.36 ± 13.52 |
| `python pting/day02.py input-pting` | 49.7 ± 15.9 | 35.9 | 112.6 | 27.81 ± 16.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
