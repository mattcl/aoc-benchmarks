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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 15.0 ± 2.6 | 12.9 | 28.7 | 4.75 ± 2.07 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 16.1 ± 4.8 | 12.9 | 46.7 | 5.11 ± 2.53 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.6 ± 3.4 | 12.8 | 36.1 | 4.94 ± 2.24 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 14.9 ± 2.8 | 12.8 | 37.8 | 4.73 ± 2.08 |
| `aspidites-solver/aoc -i input-pting -d 2` | 15.8 ± 3.7 | 12.9 | 37.2 | 5.00 ± 2.32 |
| `kcen/2022/02/solve input-aspidites` | 3.5 ± 1.6 | 1.5 | 16.4 | 1.11 ± 0.67 |
| `kcen/2022/02/solve input-kcen` | 3.2 ± 2.0 | 1.1 | 17.9 | 1.00 ± 0.76 |
| `kcen/2022/02/solve input-lanjian` | 3.3 ± 1.6 | 1.1 | 13.2 | 1.04 ± 0.66 |
| `kcen/2022/02/solve input-mattcl` | 3.6 ± 1.5 | 1.5 | 23.5 | 1.14 ± 0.66 |
| `kcen/2022/02/solve input-pting` | 4.7 ± 2.5 | 1.3 | 17.9 | 1.50 ± 0.99 |
| `lanjian/day_02 input-aspidites` | 3.6 ± 1.6 | 1.7 | 23.5 | 1.15 ± 0.70 |
| `lanjian/day_02 input-kcen` | 4.3 ± 2.1 | 1.8 | 17.0 | 1.37 ± 0.85 |
| `lanjian/day_02 input-lanjian` | 4.3 ± 1.7 | 1.9 | 12.0 | 1.35 ± 0.77 |
| `lanjian/day_02 input-mattcl` | 4.4 ± 2.0 | 2.1 | 16.4 | 1.39 ± 0.84 |
| `lanjian/day_02 input-pting` | 4.5 ± 1.7 | 2.1 | 12.2 | 1.44 ± 0.78 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.3 ± 1.5 | 1.2 | 15.5 | 1.04 ± 0.62 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.5 ± 1.4 | 1.3 | 15.4 | 1.11 ± 0.62 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.6 ± 1.6 | 1.1 | 26.6 | 1.13 ± 0.68 |
| `mattcl-solver/aoc run 2 input-mattcl` | 4.1 ± 2.0 | 1.5 | 16.8 | 1.31 ± 0.83 |
| `mattcl-solver/aoc run 2 input-pting` | 3.2 ± 1.3 | 1.1 | 11.9 | 1.00 |
| `python pting/day02.py input-aspidites` | 58.4 ± 7.4 | 46.2 | 81.8 | 18.49 ± 7.72 |
| `python pting/day02.py input-kcen` | 61.8 ± 15.5 | 49.7 | 159.7 | 19.55 ± 9.19 |
| `python pting/day02.py input-lanjian` | 60.6 ± 9.1 | 44.3 | 98.1 | 19.18 ± 8.15 |
| `python pting/day02.py input-mattcl` | 65.0 ± 10.0 | 45.7 | 100.4 | 20.58 ± 8.78 |
| `python pting/day02.py input-pting` | 77.9 ± 18.6 | 50.5 | 126.0 | 24.64 ± 11.44 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
