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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.7 ± 0.6 | 11.8 | 16.0 | 9.16 ± 4.06 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.7 ± 1.2 | 11.4 | 23.3 | 9.17 ± 4.13 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.5 ± 0.6 | 11.6 | 15.1 | 9.03 ± 4.00 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.5 ± 0.5 | 11.6 | 14.6 | 9.02 ± 3.99 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.7 ± 1.1 | 11.6 | 24.9 | 9.17 ± 4.12 |
| `kcen/2022/01/solve input-aspidites` | 108.1 ± 6.8 | 94.3 | 128.0 | 78.09 ± 34.76 |
| `kcen/2022/01/solve input-kcen` | 110.2 ± 8.0 | 98.0 | 126.6 | 79.64 ± 35.57 |
| `kcen/2022/01/solve input-lanjian` | 105.7 ± 6.6 | 92.4 | 117.1 | 76.40 ± 34.00 |
| `kcen/2022/01/solve input-mattcl` | 105.4 ± 10.5 | 96.0 | 137.6 | 76.20 ± 34.43 |
| `kcen/2022/01/solve input-pting` | 123.5 ± 25.9 | 105.2 | 241.4 | 89.24 ± 43.57 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 0.5 | 0.9 | 6.1 | 1.29 ± 0.67 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.7 | 0.8 | 13.5 | 1.12 ± 0.71 |
| `lanjian/day_01 input-lanjian` | 1.5 ± 0.4 | 0.8 | 7.0 | 1.11 ± 0.58 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.5 | 0.9 | 4.5 | 1.30 ± 0.68 |
| `lanjian/day_01 input-pting` | 1.9 ± 0.5 | 1.0 | 4.5 | 1.38 ± 0.70 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 0.4 | 0.7 | 3.8 | 1.08 ± 0.57 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 0.6 | 0.6 | 5.2 | 1.00 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.5 ± 0.5 | 0.7 | 4.5 | 1.05 ± 0.60 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.5 ± 0.5 | 0.7 | 5.1 | 1.06 ± 0.59 |
| `mattcl-solver/aoc run 1 input-pting` | 1.9 ± 0.6 | 0.6 | 4.7 | 1.35 ± 0.74 |
| `python pting/day01.py input-aspidites` | 34.2 ± 3.5 | 28.7 | 44.6 | 24.73 ± 11.18 |
| `python pting/day01.py input-kcen` | 33.9 ± 3.5 | 28.4 | 44.0 | 24.51 ± 11.09 |
| `python pting/day01.py input-lanjian` | 33.2 ± 5.6 | 27.0 | 53.8 | 24.00 ± 11.31 |
| `python pting/day01.py input-mattcl` | 34.9 ± 4.8 | 28.8 | 56.6 | 25.20 ± 11.63 |
| `python pting/day01.py input-pting` | 35.5 ± 3.3 | 28.7 | 43.9 | 25.65 ± 11.56 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
