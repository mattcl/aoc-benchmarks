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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 17.1 ± 4.7 | 12.8 | 38.6 | 6.82 ± 4.14 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.5 ± 3.0 | 12.9 | 27.6 | 6.17 ± 3.54 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 16.3 ± 3.4 | 12.8 | 35.5 | 6.49 ± 3.76 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 15.4 ± 2.5 | 12.9 | 27.8 | 6.14 ± 3.46 |
| `aspidites-solver/aoc -i input-pting -d 1` | 17.3 ± 4.6 | 13.3 | 34.6 | 6.88 ± 4.15 |
| `kcen/2022/01/solve input-aspidites` | 182.7 ± 22.4 | 149.5 | 224.4 | 72.85 ± 40.35 |
| `kcen/2022/01/solve input-kcen` | 169.9 ± 21.7 | 138.9 | 204.7 | 67.75 ± 37.61 |
| `kcen/2022/01/solve input-lanjian` | 175.4 ± 21.5 | 138.7 | 202.9 | 69.94 ± 38.74 |
| `kcen/2022/01/solve input-mattcl` | 163.6 ± 19.5 | 131.8 | 194.9 | 65.22 ± 36.08 |
| `kcen/2022/01/solve input-pting` | 156.9 ± 20.1 | 126.8 | 208.3 | 62.58 ± 34.74 |
| `lanjian/day_01 input-aspidites` | 6.2 ± 6.2 | 1.2 | 52.5 | 2.46 ± 2.81 |
| `lanjian/day_01 input-kcen` | 3.0 ± 1.3 | 0.7 | 9.7 | 1.19 ± 0.84 |
| `lanjian/day_01 input-lanjian` | 3.5 ± 1.3 | 1.2 | 16.2 | 1.39 ± 0.90 |
| `lanjian/day_01 input-mattcl` | 3.8 ± 1.4 | 0.9 | 10.5 | 1.51 ± 1.00 |
| `lanjian/day_01 input-pting` | 3.8 ± 2.4 | 1.0 | 19.6 | 1.51 ± 1.26 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.2 ± 1.3 | 0.9 | 9.0 | 1.29 ± 0.87 |
| `mattcl-solver/aoc run 1 input-kcen` | 3.4 ± 1.2 | 1.0 | 12.1 | 1.35 ± 0.88 |
| `mattcl-solver/aoc run 1 input-lanjian` | 3.7 ± 1.5 | 0.9 | 21.5 | 1.49 ± 1.01 |
| `mattcl-solver/aoc run 1 input-mattcl` | 3.2 ± 1.3 | 0.8 | 11.4 | 1.30 ± 0.88 |
| `mattcl-solver/aoc run 1 input-pting` | 2.5 ± 1.4 | 0.6 | 14.7 | 1.00 |
| `python pting/day01.py input-aspidites` | 62.7 ± 13.5 | 45.9 | 109.6 | 25.00 ± 14.53 |
| `python pting/day01.py input-kcen` | 56.4 ± 7.9 | 42.3 | 80.7 | 22.49 ± 12.56 |
| `python pting/day01.py input-lanjian` | 58.4 ± 8.0 | 44.3 | 79.9 | 23.29 ± 12.97 |
| `python pting/day01.py input-mattcl` | 53.1 ± 8.4 | 38.3 | 74.3 | 21.18 ± 11.93 |
| `python pting/day01.py input-pting` | 58.2 ± 11.8 | 39.6 | 91.9 | 23.22 ± 13.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
