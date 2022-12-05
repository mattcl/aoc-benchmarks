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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.8 ± 0.8 | 11.4 | 16.2 | 9.68 ± 3.52 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 13.1 ± 1.8 | 11.5 | 27.4 | 9.91 ± 3.80 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.7 ± 1.1 | 11.4 | 22.9 | 9.62 ± 3.55 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.0 ± 1.0 | 11.5 | 23.1 | 9.80 ± 3.59 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.9 ± 0.9 | 11.4 | 22.7 | 9.79 ± 3.57 |
| `kcen/2022/01/solve input-aspidites` | 117.2 ± 22.3 | 87.8 | 166.7 | 88.67 ± 35.97 |
| `kcen/2022/01/solve input-kcen` | 112.6 ± 8.8 | 101.1 | 131.1 | 85.18 ± 31.26 |
| `kcen/2022/01/solve input-lanjian` | 130.3 ± 31.4 | 95.5 | 225.6 | 98.61 ± 42.60 |
| `kcen/2022/01/solve input-mattcl` | 102.3 ± 10.1 | 85.5 | 126.3 | 77.45 ± 28.79 |
| `kcen/2022/01/solve input-pting` | 119.5 ± 15.8 | 92.3 | 155.0 | 90.43 ± 34.55 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.7 | 0.6 | 6.2 | 1.05 ± 0.62 |
| `lanjian/day_01 input-kcen` | 1.8 ± 0.7 | 0.9 | 5.0 | 1.34 ± 0.74 |
| `lanjian/day_01 input-lanjian` | 2.4 ± 1.5 | 0.7 | 13.9 | 1.79 ± 1.30 |
| `lanjian/day_01 input-mattcl` | 2.1 ± 0.9 | 0.8 | 7.9 | 1.56 ± 0.88 |
| `lanjian/day_01 input-pting` | 2.0 ± 0.7 | 0.7 | 6.8 | 1.54 ± 0.75 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.0 ± 1.1 | 0.7 | 17.6 | 1.55 ± 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.1 ± 1.3 | 0.6 | 16.8 | 1.56 ± 1.16 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.5 ± 1.6 | 0.6 | 17.2 | 1.86 ± 1.37 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.4 ± 0.7 | 0.6 | 6.2 | 1.08 ± 0.63 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.5 | 0.5 | 5.1 | 1.00 |
| `python pting/day01.py input-aspidites` | 37.3 ± 6.1 | 31.0 | 61.9 | 28.23 ± 11.14 |
| `python pting/day01.py input-kcen` | 29.9 ± 2.7 | 26.5 | 43.2 | 22.61 ± 8.36 |
| `python pting/day01.py input-lanjian` | 45.9 ± 13.6 | 31.3 | 84.0 | 34.71 ± 16.13 |
| `python pting/day01.py input-mattcl` | 35.9 ± 5.9 | 28.5 | 57.7 | 27.20 ± 10.73 |
| `python pting/day01.py input-pting` | 38.4 ± 9.8 | 26.6 | 76.9 | 29.07 ± 12.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
