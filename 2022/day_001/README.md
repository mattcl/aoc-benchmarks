# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 1)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.2 ± 0.7 | 11.4 | 17.3 | 12.04 ± 3.52 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 11.9 ± 1.6 | 11.1 | 24.4 | 11.80 ± 3.75 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.0 ± 0.4 | 11.4 | 13.6 | 11.85 ± 3.44 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.5 ± 1.0 | 11.5 | 17.4 | 12.36 ± 3.69 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.2 ± 0.6 | 11.4 | 14.7 | 12.12 ± 3.53 |
| `kcen/2022/01/solve input-aspidites` | 124.0 ± 20.4 | 100.0 | 170.5 | 122.62 ± 40.69 |
| `kcen/2022/01/solve input-kcen` | 99.1 ± 8.0 | 87.8 | 119.2 | 98.01 ± 29.31 |
| `kcen/2022/01/solve input-lanjian` | 114.0 ± 21.2 | 94.1 | 163.1 | 112.81 ± 38.65 |
| `kcen/2022/01/solve input-mattcl` | 103.5 ± 7.1 | 92.2 | 120.5 | 102.37 ± 30.30 |
| `kcen/2022/01/solve input-pting` | 101.4 ± 10.1 | 90.3 | 135.5 | 100.30 ± 30.56 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.6 | 0.8 | 11.7 | 1.69 ± 0.79 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.6 | 0.8 | 5.6 | 1.45 ± 0.74 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.4 | 0.9 | 4.3 | 1.68 ± 0.63 |
| `lanjian/day_01 input-mattcl` | 1.5 ± 0.5 | 0.8 | 5.1 | 1.52 ± 0.66 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.4 | 0.8 | 4.6 | 1.35 ± 0.56 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.2 ± 0.3 | 0.7 | 3.8 | 1.15 ± 0.47 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.4 | 0.7 | 7.6 | 1.32 ± 0.57 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.5 ± 0.5 | 0.7 | 6.8 | 1.44 ± 0.61 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.2 ± 0.8 | 0.6 | 21.3 | 1.23 ± 0.90 |
| `mattcl-solver/aoc run 1 input-pting` | 1.0 ± 0.3 | 0.7 | 4.0 | 1.00 |
| `python pting/day01.py input-aspidites` | 30.6 ± 2.5 | 27.3 | 43.2 | 30.31 ± 9.08 |
| `python pting/day01.py input-kcen` | 33.0 ± 4.5 | 27.7 | 54.0 | 32.66 ± 10.38 |
| `python pting/day01.py input-lanjian` | 33.2 ± 3.4 | 28.5 | 46.4 | 32.86 ± 10.05 |
| `python pting/day01.py input-mattcl` | 34.4 ± 4.2 | 27.8 | 56.3 | 34.00 ± 10.65 |
| `python pting/day01.py input-pting` | 30.6 ± 1.9 | 27.0 | 40.0 | 30.29 ± 8.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
