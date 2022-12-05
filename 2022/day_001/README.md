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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.4 ± 1.7 | 8.4 | 26.0 | 13.27 ± 5.19 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 11.7 ± 0.3 | 11.3 | 13.9 | 12.55 ± 4.61 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 11.9 ± 0.4 | 11.3 | 13.7 | 12.75 ± 4.69 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 11.9 ± 0.6 | 11.3 | 16.1 | 12.80 ± 4.73 |
| `aspidites-solver/aoc -i input-pting -d 1` | 11.8 ± 1.1 | 11.1 | 23.1 | 12.68 ± 4.79 |
| `kcen/2022/01/solve input-aspidites` | 104.1 ± 11.2 | 87.8 | 139.6 | 111.66 ± 42.62 |
| `kcen/2022/01/solve input-kcen` | 94.9 ± 4.7 | 88.3 | 107.3 | 101.73 ± 37.59 |
| `kcen/2022/01/solve input-lanjian` | 100.0 ± 8.7 | 88.3 | 135.4 | 107.30 ± 40.37 |
| `kcen/2022/01/solve input-mattcl` | 99.1 ± 6.8 | 88.6 | 115.6 | 106.28 ± 39.59 |
| `kcen/2022/01/solve input-pting` | 98.2 ± 11.4 | 87.2 | 137.0 | 105.37 ± 40.48 |
| `lanjian/day_01 input-aspidites` | 1.3 ± 0.5 | 0.7 | 7.2 | 1.39 ± 0.71 |
| `lanjian/day_01 input-kcen` | 1.2 ± 0.3 | 0.8 | 3.4 | 1.27 ± 0.56 |
| `lanjian/day_01 input-lanjian` | 1.4 ± 0.3 | 0.8 | 3.2 | 1.47 ± 0.63 |
| `lanjian/day_01 input-mattcl` | 1.2 ± 0.3 | 0.7 | 2.9 | 1.31 ± 0.58 |
| `lanjian/day_01 input-pting` | 1.2 ± 0.3 | 0.7 | 4.6 | 1.24 ± 0.57 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 1.0 | 0.7 | 9.9 | 1.38 ± 1.14 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.2 ± 0.4 | 0.6 | 4.4 | 1.32 ± 0.65 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.1 ± 0.3 | 0.6 | 3.0 | 1.21 ± 0.53 |
| `mattcl-solver/aoc run 1 input-mattcl` | 0.9 ± 0.3 | 0.6 | 9.2 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.8 | 0.7 | 16.9 | 1.51 ± 1.03 |
| `python pting/day01.py input-aspidites` | 30.2 ± 2.9 | 26.7 | 44.9 | 32.34 ± 12.25 |
| `python pting/day01.py input-kcen` | 31.3 ± 3.8 | 27.3 | 45.4 | 33.52 ± 12.94 |
| `python pting/day01.py input-lanjian` | 32.2 ± 3.6 | 26.7 | 48.7 | 34.52 ± 13.23 |
| `python pting/day01.py input-mattcl` | 31.3 ± 4.7 | 25.9 | 47.6 | 33.54 ± 13.27 |
| `python pting/day01.py input-pting` | 30.4 ± 2.6 | 27.2 | 42.8 | 32.64 ± 12.26 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
