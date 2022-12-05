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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.4 ± 0.6 | 11.5 | 15.8 | 10.63 ± 3.38 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.2 ± 0.5 | 11.5 | 15.4 | 10.47 ± 3.32 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.4 ± 0.4 | 11.7 | 14.1 | 10.63 ± 3.36 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.3 ± 0.7 | 11.6 | 19.7 | 10.52 ± 3.36 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.2 ± 0.5 | 11.6 | 13.9 | 10.43 ± 3.30 |
| `kcen/2022/01/solve input-aspidites` | 104.2 ± 14.2 | 92.3 | 138.6 | 89.35 ± 30.56 |
| `kcen/2022/01/solve input-kcen` | 103.2 ± 8.8 | 91.3 | 131.3 | 88.54 ± 28.80 |
| `kcen/2022/01/solve input-lanjian` | 110.9 ± 6.0 | 100.8 | 125.4 | 95.09 ± 30.28 |
| `kcen/2022/01/solve input-mattcl` | 111.0 ± 10.6 | 94.6 | 136.3 | 95.19 ± 31.23 |
| `kcen/2022/01/solve input-pting` | 100.5 ± 9.9 | 90.3 | 131.7 | 86.17 ± 28.34 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.7 | 1.0 | 7.9 | 1.47 ± 0.73 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.7 | 0.9 | 8.8 | 1.30 ± 0.73 |
| `lanjian/day_01 input-lanjian` | 1.3 ± 0.3 | 0.9 | 3.4 | 1.14 ± 0.43 |
| `lanjian/day_01 input-mattcl` | 1.9 ± 0.5 | 0.9 | 6.1 | 1.62 ± 0.66 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.4 | 0.9 | 3.7 | 1.19 ± 0.48 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.4 ± 0.7 | 0.8 | 9.1 | 1.24 ± 0.73 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.2 ± 0.4 | 0.8 | 7.2 | 1.00 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.4 ± 0.4 | 0.8 | 4.4 | 1.21 ± 0.51 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.6 ± 0.6 | 0.9 | 10.2 | 1.34 ± 0.67 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.5 | 0.7 | 5.9 | 1.20 ± 0.60 |
| `python pting/day01.py input-aspidites` | 33.7 ± 3.8 | 28.5 | 50.3 | 28.89 ± 9.64 |
| `python pting/day01.py input-kcen` | 34.1 ± 4.9 | 28.5 | 58.1 | 29.24 ± 10.09 |
| `python pting/day01.py input-lanjian` | 34.9 ± 6.8 | 27.5 | 61.8 | 29.93 ± 11.05 |
| `python pting/day01.py input-mattcl` | 34.2 ± 4.9 | 28.6 | 51.9 | 29.33 ± 10.11 |
| `python pting/day01.py input-pting` | 31.9 ± 3.3 | 27.7 | 46.0 | 27.34 ± 9.03 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
