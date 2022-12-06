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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 15.9 ± 4.2 | 12.6 | 37.2 | 6.38 ± 3.67 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 14.7 ± 2.1 | 12.8 | 34.0 | 5.89 ± 3.13 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 14.5 ± 1.8 | 12.7 | 24.7 | 5.81 ± 3.06 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 14.3 ± 2.8 | 12.6 | 36.3 | 5.73 ± 3.13 |
| `aspidites-solver/aoc -i input-pting -d 2` | 24.8 ± 25.1 | 13.3 | 174.6 | 9.94 ± 11.27 |
| `kcen/2022/02/solve input-aspidites` | 3.4 ± 1.5 | 1.0 | 15.4 | 1.38 ± 0.94 |
| `kcen/2022/02/solve input-kcen` | 3.2 ± 5.6 | 0.9 | 142.2 | 1.27 ± 2.33 |
| `kcen/2022/02/solve input-lanjian` | 3.6 ± 9.1 | 1.0 | 223.2 | 1.44 ± 3.71 |
| `kcen/2022/02/solve input-mattcl` | 2.8 ± 1.1 | 1.0 | 12.7 | 1.10 ± 0.72 |
| `kcen/2022/02/solve input-pting` | 4.4 ± 4.8 | 1.0 | 51.4 | 1.77 ± 2.13 |
| `lanjian/day_02 input-aspidites` | 3.6 ± 1.3 | 1.5 | 13.7 | 1.44 ± 0.90 |
| `lanjian/day_02 input-kcen` | 3.9 ± 1.4 | 1.7 | 14.8 | 1.57 ± 0.98 |
| `lanjian/day_02 input-lanjian` | 3.1 ± 1.3 | 1.3 | 11.7 | 1.24 ± 0.81 |
| `lanjian/day_02 input-mattcl` | 3.4 ± 1.1 | 1.4 | 11.9 | 1.38 ± 0.84 |
| `lanjian/day_02 input-pting` | 3.7 ± 1.5 | 1.4 | 22.5 | 1.49 ± 0.98 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.5 ± 1.4 | 1.2 | 12.4 | 1.42 ± 0.93 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.9 ± 1.3 | 1.1 | 23.8 | 1.16 ± 0.79 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.2 ± 1.2 | 1.2 | 10.5 | 1.29 ± 0.83 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.5 ± 1.3 | 0.9 | 15.7 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 4.1 ± 1.8 | 1.6 | 13.5 | 1.65 ± 1.10 |
| `python pting/day02.py input-aspidites` | 54.6 ± 8.8 | 41.4 | 78.7 | 21.86 ± 11.72 |
| `python pting/day02.py input-kcen` | 58.6 ± 7.1 | 49.1 | 78.9 | 23.45 ± 12.33 |
| `python pting/day02.py input-lanjian` | 58.6 ± 11.0 | 44.2 | 93.9 | 23.43 ± 12.77 |
| `python pting/day02.py input-mattcl` | 56.1 ± 11.9 | 43.1 | 82.1 | 22.45 ± 12.43 |
| `python pting/day02.py input-pting` | 56.5 ± 9.7 | 46.5 | 93.9 | 22.62 ± 12.21 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
