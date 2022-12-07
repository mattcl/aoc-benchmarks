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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.1 ± 1.4 | 12.2 | 23.6 | 6.67 ± 4.90 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.4 ± 3.6 | 11.9 | 30.3 | 7.29 ± 5.57 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 21.3 ± 16.5 | 12.2 | 166.7 | 10.03 ± 10.67 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 15.7 ± 3.5 | 12.5 | 29.0 | 7.43 ± 5.66 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.4 ± 2.9 | 12.6 | 28.1 | 7.25 ± 5.45 |
| `kcen/2022/01/solve input-aspidites` | 160.5 ± 15.4 | 138.8 | 189.8 | 75.75 ± 55.61 |
| `kcen/2022/01/solve input-kcen` | 183.8 ± 23.1 | 147.9 | 217.8 | 86.71 ± 64.05 |
| `kcen/2022/01/solve input-lanjian` | 170.4 ± 19.1 | 136.0 | 210.2 | 80.41 ± 59.21 |
| `kcen/2022/01/solve input-mattcl` | 167.8 ± 20.2 | 139.9 | 204.7 | 79.17 ± 58.40 |
| `kcen/2022/01/solve input-pting` | 178.1 ± 15.0 | 155.2 | 206.8 | 84.04 ± 61.58 |
| `lanjian/day_01 input-aspidites` | 3.0 ± 1.4 | 0.4 | 12.0 | 1.39 ± 1.21 |
| `lanjian/day_01 input-kcen` | 3.0 ± 1.2 | 0.9 | 8.2 | 1.39 ± 1.16 |
| `lanjian/day_01 input-lanjian` | 2.8 ± 1.6 | 0.5 | 14.3 | 1.32 ± 1.22 |
| `lanjian/day_01 input-mattcl` | 3.8 ± 2.3 | 0.6 | 27.3 | 1.77 ± 1.67 |
| `lanjian/day_01 input-pting` | 2.8 ± 1.8 | 0.3 | 19.2 | 1.31 ± 1.28 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.9 ± 1.3 | 0.3 | 13.2 | 1.37 ± 1.16 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.5 ± 2.0 | 0.2 | 15.2 | 1.18 ± 1.28 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.1 ± 1.5 | 0.2 | 17.3 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.9 ± 1.5 | 0.1 | 12.1 | 1.35 ± 1.20 |
| `mattcl-solver/aoc run 1 input-pting` | 2.6 ± 2.2 | 0.1 | 45.4 | 1.23 ± 1.38 |
| `python pting/day01.py input-aspidites` | 56.0 ± 10.1 | 41.4 | 81.4 | 26.41 ± 19.80 |
| `python pting/day01.py input-kcen` | 86.3 ± 53.6 | 44.5 | 334.3 | 40.73 ± 38.96 |
| `python pting/day01.py input-lanjian` | 58.8 ± 9.3 | 44.8 | 79.6 | 27.76 ± 20.67 |
| `python pting/day01.py input-mattcl` | 57.4 ± 9.9 | 41.4 | 81.5 | 27.10 ± 20.27 |
| `python pting/day01.py input-pting` | 62.7 ± 10.0 | 49.0 | 90.7 | 29.61 ± 22.06 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
