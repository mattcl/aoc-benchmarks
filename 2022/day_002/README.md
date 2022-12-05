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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.3 ± 1.5 | 11.4 | 28.1 | 10.24 ± 2.46 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.1 ± 0.4 | 11.6 | 13.8 | 10.05 ± 2.12 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.9 ± 1.6 | 11.7 | 24.8 | 10.71 ± 2.60 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.4 ± 0.5 | 11.4 | 13.9 | 10.28 ± 2.18 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.4 ± 0.8 | 11.7 | 22.8 | 10.32 ± 2.26 |
| `kcen/2022/02/solve input-aspidites` | 1.2 ± 0.3 | 0.9 | 3.0 | 1.00 |
| `kcen/2022/02/solve input-kcen` | 1.6 ± 0.5 | 0.9 | 7.0 | 1.32 ± 0.47 |
| `kcen/2022/02/solve input-lanjian` | 1.6 ± 0.7 | 0.9 | 9.3 | 1.32 ± 0.62 |
| `kcen/2022/02/solve input-mattcl` | 1.8 ± 0.7 | 0.9 | 7.5 | 1.53 ± 0.66 |
| `kcen/2022/02/solve input-pting` | 1.5 ± 0.4 | 0.8 | 4.6 | 1.24 ± 0.41 |
| `lanjian/day_02 input-aspidites` | 1.6 ± 0.3 | 1.2 | 4.0 | 1.31 ± 0.35 |
| `lanjian/day_02 input-kcen` | 2.0 ± 0.5 | 1.2 | 11.6 | 1.66 ± 0.56 |
| `lanjian/day_02 input-lanjian` | 2.2 ± 0.6 | 1.3 | 9.8 | 1.85 ± 0.60 |
| `lanjian/day_02 input-mattcl` | 2.3 ± 0.9 | 1.2 | 14.3 | 1.87 ± 0.82 |
| `lanjian/day_02 input-pting` | 1.9 ± 0.4 | 1.2 | 4.8 | 1.58 ± 0.49 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.4 ± 0.4 | 0.9 | 5.9 | 1.16 ± 0.40 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.9 ± 0.7 | 1.0 | 6.2 | 1.61 ± 0.64 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.7 ± 1.1 | 1.0 | 25.1 | 1.40 ± 0.92 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.0 ± 0.8 | 1.0 | 11.3 | 1.67 ± 0.78 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.4 | 0.8 | 3.5 | 1.37 ± 0.44 |
| `python pting/day02.py input-aspidites` | 32.2 ± 2.9 | 28.8 | 45.9 | 26.73 ± 6.08 |
| `python pting/day02.py input-kcen` | 34.5 ± 4.1 | 29.4 | 55.8 | 28.67 ± 6.86 |
| `python pting/day02.py input-lanjian` | 35.2 ± 2.9 | 30.1 | 49.2 | 29.24 ± 6.55 |
| `python pting/day02.py input-mattcl` | 39.0 ± 8.2 | 29.7 | 72.8 | 32.44 ± 9.61 |
| `python pting/day02.py input-pting` | 33.6 ± 3.1 | 29.5 | 44.5 | 27.93 ± 6.37 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
