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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.1 ± 0.9 | 11.4 | 22.8 | 9.68 ± 3.03 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.4 ± 1.1 | 11.4 | 19.6 | 9.89 ± 3.14 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.1 ± 0.4 | 11.4 | 13.5 | 9.64 ± 2.95 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.1 ± 0.8 | 5.5 | 14.4 | 9.71 ± 3.01 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.1 ± 0.3 | 11.6 | 13.2 | 9.70 ± 2.96 |
| `kcen/2022/02/solve input-aspidites` | 1.7 ± 1.0 | 0.8 | 16.3 | 1.32 ± 0.93 |
| `kcen/2022/02/solve input-kcen` | 1.6 ± 0.5 | 0.8 | 7.6 | 1.26 ± 0.55 |
| `kcen/2022/02/solve input-lanjian` | 1.5 ± 0.4 | 0.8 | 5.8 | 1.23 ± 0.50 |
| `kcen/2022/02/solve input-mattcl` | 1.5 ± 0.5 | 0.8 | 12.2 | 1.17 ± 0.55 |
| `kcen/2022/02/solve input-pting` | 1.3 ± 0.4 | 0.7 | 7.4 | 1.00 |
| `lanjian/day_02 input-aspidites` | 2.1 ± 0.9 | 1.1 | 11.6 | 1.65 ± 0.87 |
| `lanjian/day_02 input-kcen` | 2.1 ± 0.6 | 1.1 | 8.7 | 1.69 ± 0.73 |
| `lanjian/day_02 input-lanjian` | 1.8 ± 0.8 | 1.0 | 16.7 | 1.45 ± 0.76 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.5 | 1.1 | 4.0 | 1.42 ± 0.56 |
| `lanjian/day_02 input-pting` | 1.6 ± 0.4 | 1.1 | 4.0 | 1.29 ± 0.48 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.6 ± 0.4 | 0.9 | 3.8 | 1.25 ± 0.49 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.9 ± 0.7 | 0.9 | 8.0 | 1.49 ± 0.72 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 0.4 | 0.9 | 3.9 | 1.21 ± 0.48 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.6 ± 0.4 | 0.9 | 3.7 | 1.27 ± 0.51 |
| `mattcl-solver/aoc run 2 input-pting` | 1.3 ± 0.3 | 0.9 | 4.1 | 1.05 ± 0.41 |
| `python pting/day02.py input-aspidites` | 36.1 ± 3.8 | 30.5 | 46.3 | 28.85 ± 9.29 |
| `python pting/day02.py input-kcen` | 35.1 ± 3.7 | 30.2 | 49.5 | 28.07 ± 9.02 |
| `python pting/day02.py input-lanjian` | 35.8 ± 3.9 | 29.6 | 45.8 | 28.64 ± 9.25 |
| `python pting/day02.py input-mattcl` | 37.5 ± 4.2 | 30.2 | 48.5 | 30.02 ± 9.72 |
| `python pting/day02.py input-pting` | 34.7 ± 4.6 | 29.4 | 54.8 | 27.75 ± 9.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
