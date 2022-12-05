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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.4 ± 0.9 | 4.7 | 15.5 | 9.38 ± 3.18 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 13.1 ± 1.6 | 11.7 | 24.3 | 9.89 ± 3.49 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.9 ± 1.0 | 11.3 | 16.1 | 9.74 ± 3.30 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.3 ± 0.8 | 11.8 | 17.2 | 10.04 ± 3.38 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.6 ± 0.7 | 11.5 | 15.1 | 9.48 ± 3.18 |
| `kcen/2022/02/solve input-aspidites` | 1.8 ± 0.9 | 0.8 | 10.5 | 1.37 ± 0.83 |
| `kcen/2022/02/solve input-kcen` | 1.3 ± 0.4 | 0.8 | 3.6 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 1.9 ± 0.8 | 0.8 | 8.4 | 1.47 ± 0.78 |
| `kcen/2022/02/solve input-mattcl` | 1.8 ± 0.6 | 0.5 | 6.6 | 1.33 ± 0.62 |
| `kcen/2022/02/solve input-pting` | 1.7 ± 0.6 | 0.8 | 6.4 | 1.28 ± 0.64 |
| `lanjian/day_02 input-aspidites` | 2.4 ± 0.7 | 1.0 | 5.7 | 1.81 ± 0.82 |
| `lanjian/day_02 input-kcen` | 1.8 ± 0.6 | 1.0 | 4.7 | 1.37 ± 0.62 |
| `lanjian/day_02 input-lanjian` | 1.9 ± 0.6 | 1.2 | 5.3 | 1.46 ± 0.69 |
| `lanjian/day_02 input-mattcl` | 3.1 ± 1.5 | 1.0 | 15.2 | 2.37 ± 1.38 |
| `lanjian/day_02 input-pting` | 2.3 ± 0.8 | 1.3 | 6.4 | 1.70 ± 0.83 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 0.5 | 0.8 | 6.0 | 1.26 ± 0.59 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.9 ± 0.7 | 0.9 | 6.7 | 1.46 ± 0.70 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.3 ± 0.5 | 0.8 | 6.9 | 1.01 ± 0.49 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.4 ± 0.9 | 1.1 | 10.3 | 1.82 ± 0.88 |
| `mattcl-solver/aoc run 2 input-pting` | 1.7 ± 0.6 | 0.9 | 9.6 | 1.25 ± 0.63 |
| `python pting/day02.py input-aspidites` | 33.8 ± 5.4 | 27.7 | 63.3 | 25.46 ± 9.37 |
| `python pting/day02.py input-kcen` | 35.4 ± 6.0 | 27.6 | 59.0 | 26.68 ± 9.93 |
| `python pting/day02.py input-lanjian` | 35.1 ± 3.9 | 27.7 | 53.9 | 26.47 ± 9.23 |
| `python pting/day02.py input-mattcl` | 38.1 ± 8.2 | 27.5 | 71.2 | 28.76 ± 11.34 |
| `python pting/day02.py input-pting` | 38.5 ± 7.6 | 29.9 | 64.8 | 29.04 ± 11.20 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
