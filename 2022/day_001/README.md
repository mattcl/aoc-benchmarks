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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 15.2 ± 3.3 | 11.8 | 27.7 | 6.95 ± 5.59 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 26.6 ± 27.8 | 12.0 | 190.6 | 12.16 ± 15.81 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.0 ± 3.0 | 11.4 | 28.0 | 6.38 ± 5.13 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.0 ± 2.7 | 11.3 | 37.7 | 6.41 ± 5.12 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.8 ± 2.4 | 11.6 | 28.7 | 6.76 ± 5.36 |
| `kcen/2022/01/solve input-aspidites` | 183.2 ± 57.0 | 142.4 | 318.8 | 83.74 ± 69.98 |
| `kcen/2022/01/solve input-kcen` | 165.1 ± 41.7 | 122.9 | 312.9 | 75.43 ± 61.53 |
| `kcen/2022/01/solve input-lanjian` | 181.2 ± 33.9 | 139.2 | 238.9 | 82.82 ± 66.07 |
| `kcen/2022/01/solve input-mattcl` | 265.1 ± 130.9 | 145.5 | 536.5 | 121.14 ± 111.38 |
| `kcen/2022/01/solve input-pting` | 207.1 ± 71.9 | 145.6 | 364.7 | 94.66 ± 80.42 |
| `lanjian/day_01 input-aspidites` | 3.5 ± 2.4 | 0.6 | 37.5 | 1.59 ± 1.66 |
| `lanjian/day_01 input-kcen` | 3.2 ± 1.9 | 0.5 | 10.4 | 1.44 ± 1.42 |
| `lanjian/day_01 input-lanjian` | 3.9 ± 2.1 | 0.4 | 16.0 | 1.77 ± 1.69 |
| `lanjian/day_01 input-mattcl` | 2.9 ± 1.8 | 0.5 | 11.8 | 1.34 ± 1.31 |
| `lanjian/day_01 input-pting` | 3.1 ± 1.6 | 0.3 | 13.3 | 1.43 ± 1.34 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.6 ± 1.8 | 0.0 | 9.5 | 1.17 ± 1.22 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.6 ± 1.7 | 0.2 | 10.0 | 1.17 ± 1.20 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.7 ± 1.8 | 0.0 | 9.1 | 1.24 ± 1.27 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.9 ± 1.8 | 0.1 | 15.0 | 1.32 ± 1.32 |
| `mattcl-solver/aoc run 1 input-pting` | 2.2 ± 1.7 | 0.0 | 17.4 | 1.00 |
| `python pting/day01.py input-aspidites` | 50.1 ± 17.0 | 35.3 | 115.3 | 22.92 ± 19.40 |
| `python pting/day01.py input-kcen` | 55.1 ± 24.8 | 37.2 | 133.8 | 25.19 ± 22.58 |
| `python pting/day01.py input-lanjian` | 57.7 ± 27.1 | 37.6 | 155.2 | 26.37 ± 23.90 |
| `python pting/day01.py input-mattcl` | 70.9 ± 47.7 | 34.0 | 258.3 | 32.41 ± 33.27 |
| `python pting/day01.py input-pting` | 59.5 ± 28.9 | 38.7 | 154.6 | 27.21 ± 24.89 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
