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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.7 ± 1.8 | 11.3 | 23.7 | 10.37 ± 4.78 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.5 ± 1.0 | 11.6 | 22.9 | 10.26 ± 4.58 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.2 ± 1.1 | 11.5 | 23.8 | 9.97 ± 4.48 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.4 ± 0.7 | 11.5 | 17.4 | 10.11 ± 4.47 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.1 ± 0.4 | 11.5 | 14.3 | 9.94 ± 4.38 |
| `kcen/2022/01/solve input-aspidites` | 109.1 ± 5.3 | 97.4 | 121.0 | 89.26 ± 39.42 |
| `kcen/2022/01/solve input-kcen` | 110.9 ± 7.6 | 98.2 | 134.7 | 90.74 ± 40.32 |
| `kcen/2022/01/solve input-lanjian` | 111.8 ± 12.5 | 96.3 | 138.6 | 91.40 ± 41.40 |
| `kcen/2022/01/solve input-mattcl` | 112.4 ± 12.4 | 93.2 | 141.1 | 91.96 ± 41.62 |
| `kcen/2022/01/solve input-pting` | 105.2 ± 5.6 | 95.7 | 115.5 | 86.06 ± 38.05 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 0.8 | 0.8 | 8.1 | 1.45 ± 0.89 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.4 | 0.8 | 4.9 | 1.22 ± 0.63 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.6 | 0.8 | 5.7 | 1.39 ± 0.81 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.5 | 0.8 | 4.6 | 1.45 ± 0.76 |
| `lanjian/day_01 input-pting` | 1.5 ± 0.4 | 0.9 | 4.3 | 1.21 ± 0.62 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.6 ± 0.9 | 0.7 | 20.9 | 1.29 ± 0.91 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.5 | 0.6 | 11.3 | 1.09 ± 0.65 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.6 | 0.6 | 9.2 | 1.07 ± 0.70 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.6 ± 0.7 | 0.7 | 10.0 | 1.33 ± 0.79 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 0.5 | 0.5 | 9.5 | 1.00 |
| `python pting/day01.py input-aspidites` | 36.5 ± 6.5 | 28.5 | 60.8 | 29.82 ± 14.14 |
| `python pting/day01.py input-kcen` | 34.8 ± 4.4 | 29.4 | 56.5 | 28.47 ± 13.00 |
| `python pting/day01.py input-lanjian` | 35.5 ± 4.1 | 29.3 | 46.3 | 29.04 ± 13.18 |
| `python pting/day01.py input-mattcl` | 32.5 ± 4.3 | 27.2 | 50.2 | 26.57 ± 12.19 |
| `python pting/day01.py input-pting` | 34.2 ± 3.9 | 28.4 | 45.2 | 27.99 ± 12.70 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
