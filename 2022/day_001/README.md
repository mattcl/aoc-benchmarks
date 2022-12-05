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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.1 ± 0.6 | 11.5 | 16.3 | 10.49 ± 2.73 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.1 ± 0.7 | 11.4 | 17.1 | 10.47 ± 2.76 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.2 ± 0.5 | 11.6 | 14.9 | 10.57 ± 2.75 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.2 ± 0.6 | 11.6 | 16.6 | 10.56 ± 2.75 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.3 ± 1.2 | 11.4 | 24.5 | 10.59 ± 2.90 |
| `kcen/2022/01/solve input-aspidites` | 103.8 ± 10.0 | 91.4 | 122.4 | 89.66 ± 24.54 |
| `kcen/2022/01/solve input-kcen` | 99.2 ± 7.2 | 89.2 | 119.8 | 85.72 ± 22.82 |
| `kcen/2022/01/solve input-lanjian` | 101.0 ± 6.7 | 91.2 | 121.3 | 87.24 ± 23.09 |
| `kcen/2022/01/solve input-mattcl` | 107.5 ± 15.4 | 89.5 | 147.8 | 92.85 ± 27.25 |
| `kcen/2022/01/solve input-pting` | 106.0 ± 10.7 | 90.4 | 128.4 | 91.55 ± 25.22 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.4 | 1.0 | 5.2 | 1.39 ± 0.48 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.6 | 0.9 | 6.5 | 1.38 ± 0.62 |
| `lanjian/day_01 input-lanjian` | 1.5 ± 0.5 | 0.9 | 7.6 | 1.27 ± 0.55 |
| `lanjian/day_01 input-mattcl` | 2.0 ± 0.8 | 1.0 | 7.2 | 1.69 ± 0.83 |
| `lanjian/day_01 input-pting` | 2.0 ± 0.7 | 1.0 | 8.6 | 1.71 ± 0.75 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.3 | 0.7 | 5.7 | 1.14 ± 0.41 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 0.7 | 0.6 | 11.2 | 1.19 ± 0.71 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.2 ± 0.3 | 0.7 | 4.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.5 ± 0.5 | 0.7 | 5.6 | 1.33 ± 0.55 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.4 | 0.7 | 4.3 | 1.12 ± 0.44 |
| `python pting/day01.py input-aspidites` | 29.9 ± 2.6 | 26.8 | 40.6 | 25.86 ± 6.99 |
| `python pting/day01.py input-kcen` | 31.3 ± 2.9 | 27.1 | 40.5 | 27.00 ± 7.36 |
| `python pting/day01.py input-lanjian` | 31.0 ± 3.4 | 27.7 | 45.3 | 26.80 ± 7.46 |
| `python pting/day01.py input-mattcl` | 34.5 ± 5.9 | 28.6 | 64.9 | 29.83 ± 9.20 |
| `python pting/day01.py input-pting` | 35.9 ± 7.5 | 27.7 | 73.1 | 31.05 ± 10.29 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
