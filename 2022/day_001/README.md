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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.6 ± 1.6 | 12.7 | 27.4 | 6.06 ± 3.96 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.1 ± 3.1 | 12.8 | 32.7 | 6.27 ± 4.23 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 17.2 ± 4.7 | 13.1 | 35.7 | 7.14 ± 4.98 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.5 ± 1.9 | 12.4 | 26.0 | 6.00 ± 3.94 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.4 ± 1.7 | 12.4 | 24.9 | 5.98 ± 3.91 |
| `kcen/2022/01/solve input-aspidites` | 158.7 ± 19.6 | 137.9 | 206.2 | 65.74 ± 43.08 |
| `kcen/2022/01/solve input-kcen` | 237.1 ± 135.2 | 145.8 | 582.9 | 98.22 ± 84.47 |
| `kcen/2022/01/solve input-lanjian` | 190.5 ± 21.0 | 162.6 | 238.9 | 78.93 ± 51.54 |
| `kcen/2022/01/solve input-mattcl` | 177.4 ± 18.5 | 152.3 | 213.0 | 73.50 ± 47.92 |
| `kcen/2022/01/solve input-pting` | 166.3 ± 18.5 | 143.0 | 201.8 | 68.91 ± 45.01 |
| `lanjian/day_01 input-aspidites` | 3.2 ± 1.2 | 1.3 | 8.3 | 1.33 ± 0.98 |
| `lanjian/day_01 input-kcen` | 2.9 ± 0.9 | 1.3 | 10.5 | 1.21 ± 0.87 |
| `lanjian/day_01 input-lanjian` | 5.8 ± 7.7 | 1.5 | 158.8 | 2.42 ± 3.55 |
| `lanjian/day_01 input-mattcl` | 3.2 ± 1.3 | 1.3 | 18.2 | 1.34 ± 1.02 |
| `lanjian/day_01 input-pting` | 3.2 ± 1.1 | 1.2 | 10.9 | 1.33 ± 0.97 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.1 ± 1.6 | 0.9 | 19.1 | 1.30 ± 1.07 |
| `mattcl-solver/aoc run 1 input-kcen` | 3.2 ± 1.5 | 0.9 | 13.7 | 1.32 ± 1.07 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.4 ± 1.6 | 0.8 | 24.4 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 3.0 ± 1.3 | 1.1 | 18.3 | 1.23 ± 0.97 |
| `mattcl-solver/aoc run 1 input-pting` | 3.1 ± 1.1 | 1.1 | 9.2 | 1.28 ± 0.94 |
| `python pting/day01.py input-aspidites` | 51.2 ± 8.0 | 38.4 | 77.6 | 21.21 ± 14.04 |
| `python pting/day01.py input-kcen` | 49.9 ± 6.7 | 36.5 | 65.9 | 20.66 ± 13.59 |
| `python pting/day01.py input-lanjian` | 56.0 ± 6.5 | 43.0 | 71.4 | 23.22 ± 15.18 |
| `python pting/day01.py input-mattcl` | 54.4 ± 8.5 | 42.7 | 77.7 | 22.55 ± 14.94 |
| `python pting/day01.py input-pting` | 52.3 ± 7.6 | 42.2 | 87.6 | 21.69 ± 14.31 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
