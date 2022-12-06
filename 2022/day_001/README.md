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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 22.1 ± 16.1 | 12.6 | 100.9 | 7.69 ± 6.38 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.5 ± 1.4 | 12.8 | 24.0 | 5.06 ± 2.04 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 15.8 ± 3.8 | 12.6 | 43.9 | 5.50 ± 2.53 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.8 ± 2.0 | 12.8 | 32.5 | 5.17 ± 2.14 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.1 ± 1.4 | 12.9 | 23.3 | 5.27 ± 2.13 |
| `kcen/2022/01/solve input-aspidites` | 189.6 ± 28.6 | 147.8 | 242.1 | 66.08 ± 27.75 |
| `kcen/2022/01/solve input-kcen` | 178.4 ± 19.4 | 152.3 | 216.7 | 62.17 ± 25.29 |
| `kcen/2022/01/solve input-lanjian` | 157.6 ± 20.6 | 127.5 | 203.3 | 54.94 ± 22.70 |
| `kcen/2022/01/solve input-mattcl` | 182.7 ± 19.0 | 152.7 | 219.7 | 63.66 ± 25.82 |
| `kcen/2022/01/solve input-pting` | 176.0 ± 23.3 | 138.7 | 217.4 | 61.34 ± 25.38 |
| `lanjian/day_01 input-aspidites` | 3.6 ± 1.4 | 1.2 | 13.8 | 1.27 ± 0.69 |
| `lanjian/day_01 input-kcen` | 3.4 ± 1.5 | 1.4 | 18.7 | 1.20 ± 0.70 |
| `lanjian/day_01 input-lanjian` | 3.0 ± 1.4 | 1.2 | 10.1 | 1.05 ± 0.63 |
| `lanjian/day_01 input-mattcl` | 4.0 ± 1.8 | 1.5 | 19.1 | 1.38 ± 0.82 |
| `lanjian/day_01 input-pting` | 2.9 ± 1.1 | 1.1 | 8.4 | 1.00 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.2 ± 1.3 | 0.9 | 9.8 | 1.12 ± 0.64 |
| `mattcl-solver/aoc run 1 input-kcen` | 3.5 ± 1.2 | 1.1 | 10.4 | 1.23 ± 0.64 |
| `mattcl-solver/aoc run 1 input-lanjian` | 3.3 ± 1.3 | 1.0 | 12.8 | 1.14 ± 0.64 |
| `mattcl-solver/aoc run 1 input-mattcl` | 3.6 ± 2.1 | 1.1 | 14.9 | 1.24 ± 0.89 |
| `mattcl-solver/aoc run 1 input-pting` | 3.1 ± 1.4 | 1.0 | 12.7 | 1.07 ± 0.63 |
| `python pting/day01.py input-aspidites` | 56.4 ± 9.3 | 43.5 | 81.1 | 19.65 ± 8.36 |
| `python pting/day01.py input-kcen` | 52.0 ± 8.6 | 42.4 | 81.9 | 18.12 ± 7.71 |
| `python pting/day01.py input-lanjian` | 53.7 ± 9.5 | 41.4 | 79.8 | 18.73 ± 8.05 |
| `python pting/day01.py input-mattcl` | 55.6 ± 8.4 | 42.5 | 76.9 | 19.38 ± 8.14 |
| `python pting/day01.py input-pting` | 55.0 ± 7.7 | 43.3 | 72.7 | 19.18 ± 7.99 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
