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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.3 ± 0.4 | 11.6 | 13.8 | 10.95 ± 3.89 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.1 ± 0.4 | 11.6 | 13.6 | 10.83 ± 3.85 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.1 ± 0.6 | 11.3 | 16.5 | 10.76 ± 3.85 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.3 ± 0.8 | 11.5 | 22.1 | 11.02 ± 3.97 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.6 ± 0.7 | 11.6 | 16.9 | 11.27 ± 4.04 |
| `kcen/2022/01/solve input-aspidites` | 97.1 ± 5.4 | 89.7 | 109.0 | 86.68 ± 31.08 |
| `kcen/2022/01/solve input-kcen` | 101.0 ± 13.5 | 88.4 | 137.5 | 90.21 ± 34.14 |
| `kcen/2022/01/solve input-lanjian` | 95.1 ± 5.2 | 86.7 | 105.9 | 84.96 ± 30.45 |
| `kcen/2022/01/solve input-mattcl` | 105.7 ± 8.0 | 90.0 | 125.2 | 94.37 ± 34.19 |
| `kcen/2022/01/solve input-pting` | 106.3 ± 11.9 | 87.7 | 131.6 | 94.93 ± 35.27 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.3 | 0.9 | 3.4 | 1.22 ± 0.50 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.4 | 0.9 | 4.5 | 1.48 ± 0.65 |
| `lanjian/day_01 input-lanjian` | 1.5 ± 0.5 | 0.9 | 6.3 | 1.31 ± 0.65 |
| `lanjian/day_01 input-mattcl` | 1.6 ± 0.4 | 1.0 | 4.1 | 1.45 ± 0.65 |
| `lanjian/day_01 input-pting` | 1.6 ± 0.4 | 1.0 | 4.7 | 1.39 ± 0.58 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.2 ± 0.3 | 0.8 | 3.2 | 1.06 ± 0.45 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 0.4 | 0.8 | 3.4 | 1.29 ± 0.56 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.1 ± 0.4 | 0.8 | 7.6 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.2 ± 0.4 | 0.8 | 7.1 | 1.08 ± 0.52 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.3 | 0.8 | 2.8 | 1.20 ± 0.49 |
| `python pting/day01.py input-aspidites` | 32.2 ± 4.0 | 27.5 | 44.4 | 28.73 ± 10.80 |
| `python pting/day01.py input-kcen` | 34.6 ± 3.7 | 28.7 | 49.2 | 30.91 ± 11.43 |
| `python pting/day01.py input-lanjian` | 34.0 ± 7.6 | 26.8 | 61.2 | 30.37 ± 12.72 |
| `python pting/day01.py input-mattcl` | 33.5 ± 4.4 | 28.6 | 46.8 | 29.94 ± 11.30 |
| `python pting/day01.py input-pting` | 29.5 ± 2.0 | 26.7 | 35.7 | 26.31 ± 9.49 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
