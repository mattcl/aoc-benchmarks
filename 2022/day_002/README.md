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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.4 ± 1.8 | 12.0 | 26.0 | 6.31 ± 3.37 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 15.1 ± 2.6 | 12.7 | 32.9 | 6.66 ± 3.64 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 14.8 ± 2.3 | 12.6 | 27.5 | 6.51 ± 3.53 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 16.4 ± 4.0 | 12.5 | 39.2 | 7.21 ± 4.14 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.7 ± 2.5 | 12.6 | 34.8 | 6.48 ± 3.54 |
| `kcen/2022/02/solve input-aspidites` | 2.7 ± 1.1 | 0.6 | 8.7 | 1.19 ± 0.79 |
| `kcen/2022/02/solve input-kcen` | 3.7 ± 2.8 | 0.6 | 25.4 | 1.61 ± 1.48 |
| `kcen/2022/02/solve input-lanjian` | 3.2 ± 1.4 | 0.8 | 10.5 | 1.39 ± 0.95 |
| `kcen/2022/02/solve input-mattcl` | 2.3 ± 1.2 | 0.5 | 13.7 | 1.00 |
| `kcen/2022/02/solve input-pting` | 2.6 ± 1.1 | 0.7 | 8.5 | 1.16 ± 0.77 |
| `lanjian/day_02 input-aspidites` | 3.2 ± 1.2 | 1.1 | 11.2 | 1.41 ± 0.89 |
| `lanjian/day_02 input-kcen` | 3.3 ± 1.3 | 1.0 | 13.0 | 1.45 ± 0.94 |
| `lanjian/day_02 input-lanjian` | 3.3 ± 1.4 | 1.0 | 10.9 | 1.43 ± 0.96 |
| `lanjian/day_02 input-mattcl` | 3.2 ± 1.4 | 1.3 | 12.4 | 1.40 ± 0.96 |
| `lanjian/day_02 input-pting` | 2.7 ± 1.1 | 0.9 | 6.6 | 1.19 ± 0.78 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.8 ± 1.3 | 0.8 | 9.5 | 1.21 ± 0.85 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.6 ± 1.6 | 0.9 | 18.6 | 1.56 ± 1.07 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.6 ± 1.3 | 0.6 | 13.9 | 1.15 ± 0.83 |
| `mattcl-solver/aoc run 2 input-mattcl` | 5.4 ± 4.5 | 0.9 | 31.1 | 2.38 ± 2.32 |
| `mattcl-solver/aoc run 2 input-pting` | 2.3 ± 1.2 | 0.7 | 13.8 | 1.00 ± 0.76 |
| `python pting/day02.py input-aspidites` | 55.7 ± 10.1 | 43.0 | 91.7 | 24.49 ± 13.47 |
| `python pting/day02.py input-kcen` | 53.3 ± 8.6 | 41.5 | 74.3 | 23.41 ± 12.73 |
| `python pting/day02.py input-lanjian` | 55.3 ± 9.1 | 40.1 | 78.9 | 24.32 ± 13.24 |
| `python pting/day02.py input-mattcl` | 51.0 ± 6.4 | 40.0 | 77.3 | 22.40 ± 11.97 |
| `python pting/day02.py input-pting` | 57.0 ± 9.2 | 43.7 | 79.0 | 25.06 ± 13.63 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
