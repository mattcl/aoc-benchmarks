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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.6 ± 1.3 | 11.6 | 23.0 | 10.55 ± 3.64 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.2 ± 0.6 | 11.5 | 16.5 | 10.22 ± 3.41 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.6 ± 1.3 | 11.7 | 22.6 | 10.60 ± 3.67 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.6 ± 0.5 | 11.5 | 15.8 | 10.59 ± 3.51 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.1 ± 0.5 | 11.4 | 14.3 | 10.15 ± 3.38 |
| `kcen/2022/02/solve input-aspidites` | 1.4 ± 0.5 | 0.9 | 13.7 | 1.14 ± 0.57 |
| `kcen/2022/02/solve input-kcen` | 1.4 ± 0.3 | 0.8 | 3.7 | 1.14 ± 0.46 |
| `kcen/2022/02/solve input-lanjian` | 1.2 ± 0.3 | 0.8 | 3.8 | 1.02 ± 0.43 |
| `kcen/2022/02/solve input-mattcl` | 1.5 ± 0.4 | 0.8 | 3.9 | 1.28 ± 0.55 |
| `kcen/2022/02/solve input-pting` | 1.2 ± 0.4 | 0.8 | 4.6 | 1.00 |
| `lanjian/day_02 input-aspidites` | 1.6 ± 0.4 | 1.0 | 3.8 | 1.38 ± 0.55 |
| `lanjian/day_02 input-kcen` | 1.9 ± 0.7 | 1.1 | 7.4 | 1.60 ± 0.81 |
| `lanjian/day_02 input-lanjian` | 2.2 ± 0.7 | 1.1 | 6.5 | 1.84 ± 0.86 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.4 | 1.0 | 6.8 | 1.53 ± 0.62 |
| `lanjian/day_02 input-pting` | 1.7 ± 0.4 | 1.0 | 3.8 | 1.46 ± 0.58 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.5 ± 0.5 | 0.9 | 10.0 | 1.29 ± 0.60 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.2 ± 0.3 | 0.9 | 4.3 | 1.04 ± 0.41 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 0.7 | 1.0 | 8.2 | 1.54 ± 0.78 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.7 | 0.8 | 8.6 | 1.43 ± 0.77 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.3 | 0.9 | 3.8 | 1.33 ± 0.53 |
| `python pting/day02.py input-aspidites` | 33.2 ± 3.5 | 28.7 | 50.5 | 27.84 ± 9.64 |
| `python pting/day02.py input-kcen` | 36.0 ± 5.2 | 29.4 | 64.3 | 30.21 ± 10.87 |
| `python pting/day02.py input-lanjian` | 34.0 ± 3.6 | 28.8 | 45.3 | 28.53 ± 9.87 |
| `python pting/day02.py input-mattcl` | 34.3 ± 3.4 | 28.7 | 50.6 | 28.74 ± 9.89 |
| `python pting/day02.py input-pting` | 32.7 ± 4.7 | 27.7 | 46.4 | 27.41 ± 9.86 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
