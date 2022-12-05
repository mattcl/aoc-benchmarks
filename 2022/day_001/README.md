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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.0 ± 0.5 | 11.2 | 13.8 | 9.98 ± 3.26 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.4 ± 0.5 | 11.5 | 15.1 | 10.30 ± 3.37 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.3 ± 0.5 | 11.6 | 16.2 | 10.23 ± 3.34 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.1 ± 0.4 | 11.5 | 13.7 | 10.02 ± 3.27 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.3 ± 0.4 | 11.6 | 14.4 | 10.18 ± 3.32 |
| `kcen/2022/01/solve input-aspidites` | 94.2 ± 8.2 | 85.1 | 120.8 | 78.12 ± 26.22 |
| `kcen/2022/01/solve input-kcen` | 105.6 ± 5.7 | 92.8 | 114.7 | 87.62 ± 28.79 |
| `kcen/2022/01/solve input-lanjian` | 103.4 ± 7.1 | 91.4 | 120.1 | 85.80 ± 28.43 |
| `kcen/2022/01/solve input-mattcl` | 104.0 ± 7.5 | 92.7 | 125.9 | 86.30 ± 28.66 |
| `kcen/2022/01/solve input-pting` | 99.1 ± 6.0 | 92.3 | 112.9 | 82.21 ± 27.11 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 0.7 | 0.8 | 6.1 | 1.47 ± 0.74 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.4 | 1.0 | 4.4 | 1.31 ± 0.53 |
| `lanjian/day_01 input-lanjian` | 1.8 ± 0.8 | 0.9 | 11.6 | 1.49 ± 0.83 |
| `lanjian/day_01 input-mattcl` | 1.4 ± 0.4 | 0.9 | 3.7 | 1.15 ± 0.48 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.4 | 0.8 | 7.4 | 1.19 ± 0.51 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 0.8 | 0.7 | 13.4 | 1.21 ± 0.75 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.3 | 0.8 | 3.0 | 1.09 ± 0.43 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.5 ± 0.5 | 0.8 | 7.1 | 1.21 ± 0.55 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.4 | 0.8 | 3.6 | 1.10 ± 0.47 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 0.4 | 0.7 | 5.2 | 1.00 |
| `python pting/day01.py input-aspidites` | 33.8 ± 4.8 | 27.8 | 49.4 | 28.01 ± 9.92 |
| `python pting/day01.py input-kcen` | 36.9 ± 5.3 | 29.2 | 53.6 | 30.60 ± 10.83 |
| `python pting/day01.py input-lanjian` | 34.0 ± 3.0 | 29.7 | 42.2 | 28.21 ± 9.48 |
| `python pting/day01.py input-mattcl` | 33.3 ± 5.2 | 28.3 | 68.2 | 27.61 ± 9.94 |
| `python pting/day01.py input-pting` | 32.0 ± 2.8 | 28.0 | 43.5 | 26.51 ± 8.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
