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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.4 ± 1.8 | 12.3 | 28.3 | 7.20 ± 4.40 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 14.9 ± 3.3 | 12.1 | 34.4 | 7.45 ± 4.76 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 14.8 ± 2.5 | 12.3 | 26.3 | 7.40 ± 4.59 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 14.5 ± 1.4 | 12.3 | 24.9 | 7.25 ± 4.39 |
| `aspidites-solver/aoc -i input-pting -d 2` | 21.4 ± 17.5 | 12.4 | 169.3 | 10.71 ± 10.86 |
| `kcen/2022/02/solve input-aspidites` | 2.6 ± 1.5 | 0.2 | 20.8 | 1.31 ± 1.08 |
| `kcen/2022/02/solve input-kcen` | 2.7 ± 2.3 | 0.4 | 24.2 | 1.33 ± 1.41 |
| `kcen/2022/02/solve input-lanjian` | 2.8 ± 1.3 | 0.3 | 11.2 | 1.40 ± 1.07 |
| `kcen/2022/02/solve input-mattcl` | 3.0 ± 1.1 | 0.5 | 6.9 | 1.49 ± 1.03 |
| `kcen/2022/02/solve input-pting` | 2.2 ± 1.1 | 0.1 | 6.6 | 1.08 ± 0.85 |
| `lanjian/day_02 input-aspidites` | 3.3 ± 1.3 | 0.4 | 10.0 | 1.63 ± 1.16 |
| `lanjian/day_02 input-kcen` | 2.4 ± 1.1 | 0.4 | 9.0 | 1.22 ± 0.92 |
| `lanjian/day_02 input-lanjian` | 3.2 ± 1.7 | 0.7 | 28.5 | 1.58 ± 1.28 |
| `lanjian/day_02 input-mattcl` | 4.0 ± 1.3 | 1.2 | 9.1 | 1.99 ± 1.35 |
| `lanjian/day_02 input-pting` | 4.1 ± 2.3 | 1.0 | 16.3 | 2.07 ± 1.67 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.1 ± 1.6 | 0.4 | 28.1 | 1.53 ± 1.21 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.0 ± 1.2 | 0.3 | 20.1 | 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.1 ± 1.7 | 0.3 | 16.4 | 1.57 ± 1.26 |
| `mattcl-solver/aoc run 2 input-mattcl` | 4.0 ± 2.1 | 0.6 | 16.6 | 2.00 ± 1.60 |
| `mattcl-solver/aoc run 2 input-pting` | 3.2 ± 1.4 | 0.8 | 14.8 | 1.61 ± 1.19 |
| `python pting/day02.py input-aspidites` | 63.7 ± 10.4 | 45.8 | 99.1 | 31.90 ± 19.77 |
| `python pting/day02.py input-kcen` | 61.0 ± 9.8 | 46.6 | 94.5 | 30.52 ± 18.89 |
| `python pting/day02.py input-lanjian` | 58.6 ± 8.4 | 44.8 | 80.6 | 29.36 ± 18.04 |
| `python pting/day02.py input-mattcl` | 65.9 ± 8.4 | 54.4 | 87.1 | 33.01 ± 20.17 |
| `python pting/day02.py input-pting` | 58.9 ± 8.1 | 47.9 | 78.6 | 29.50 ± 18.09 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
