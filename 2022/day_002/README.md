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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 11.9 ± 0.8 | 10.9 | 16.1 | 9.15 ± 3.51 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.3 ± 0.8 | 11.0 | 16.1 | 9.48 ± 3.64 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 13.0 ± 0.9 | 11.1 | 17.8 | 10.03 ± 3.85 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.9 ± 0.7 | 11.4 | 15.3 | 9.96 ± 3.80 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.4 ± 1.3 | 11.4 | 27.4 | 9.59 ± 3.75 |
| `kcen/2022/02/solve input-aspidites` | 1.6 ± 0.8 | 0.7 | 6.6 | 1.21 ± 0.79 |
| `kcen/2022/02/solve input-kcen` | 1.9 ± 0.9 | 0.7 | 5.7 | 1.50 ± 0.92 |
| `kcen/2022/02/solve input-lanjian` | 1.9 ± 1.0 | 0.7 | 7.4 | 1.50 ± 0.96 |
| `kcen/2022/02/solve input-mattcl` | 2.1 ± 0.9 | 0.7 | 6.3 | 1.61 ± 0.92 |
| `kcen/2022/02/solve input-pting` | 1.7 ± 1.0 | 0.7 | 15.7 | 1.32 ± 0.89 |
| `lanjian/day_02 input-aspidites` | 2.3 ± 1.0 | 0.9 | 7.1 | 1.81 ± 1.01 |
| `lanjian/day_02 input-kcen` | 1.6 ± 0.6 | 0.9 | 5.5 | 1.24 ± 0.68 |
| `lanjian/day_02 input-lanjian` | 2.3 ± 0.8 | 1.0 | 5.0 | 1.76 ± 0.93 |
| `lanjian/day_02 input-mattcl` | 2.0 ± 0.9 | 0.9 | 5.3 | 1.56 ± 0.91 |
| `lanjian/day_02 input-pting` | 2.2 ± 0.8 | 1.1 | 9.2 | 1.68 ± 0.88 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.8 ± 0.8 | 0.8 | 6.7 | 1.37 ± 0.79 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.5 | 0.8 | 5.3 | 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.9 ± 0.9 | 0.8 | 8.9 | 1.50 ± 0.90 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.0 ± 1.0 | 0.8 | 14.5 | 1.51 ± 0.96 |
| `mattcl-solver/aoc run 2 input-pting` | 1.7 ± 0.9 | 0.7 | 14.6 | 1.33 ± 0.87 |
| `python pting/day02.py input-aspidites` | 42.6 ± 11.0 | 29.6 | 72.6 | 32.80 ± 14.99 |
| `python pting/day02.py input-kcen` | 33.3 ± 6.6 | 26.9 | 62.2 | 25.66 ± 10.93 |
| `python pting/day02.py input-lanjian` | 40.6 ± 11.4 | 29.1 | 88.2 | 31.26 ± 14.69 |
| `python pting/day02.py input-mattcl` | 36.3 ± 9.1 | 28.0 | 81.2 | 27.95 ± 12.66 |
| `python pting/day02.py input-pting` | 34.5 ± 7.0 | 28.3 | 67.7 | 26.63 ± 11.41 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
