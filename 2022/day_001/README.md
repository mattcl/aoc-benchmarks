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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 11.9 ± 0.4 | 11.3 | 14.2 | 11.38 ± 2.91 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.9 ± 1.3 | 11.7 | 22.2 | 12.36 ± 3.36 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.7 ± 1.5 | 11.6 | 23.8 | 12.16 ± 3.39 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.2 ± 0.5 | 11.5 | 13.9 | 11.66 ± 2.98 |
| `aspidites-solver/aoc -i input-pting -d 1` | 11.9 ± 0.4 | 11.2 | 13.7 | 11.38 ± 2.90 |
| `kcen/2022/01/solve input-aspidites` | 99.3 ± 9.7 | 88.5 | 125.1 | 95.04 ± 25.78 |
| `kcen/2022/01/solve input-kcen` | 103.8 ± 7.8 | 91.7 | 116.1 | 99.37 ± 26.22 |
| `kcen/2022/01/solve input-lanjian` | 102.2 ± 7.4 | 90.8 | 122.0 | 97.78 ± 25.72 |
| `kcen/2022/01/solve input-mattcl` | 105.2 ± 8.3 | 93.1 | 121.9 | 100.68 ± 26.67 |
| `kcen/2022/01/solve input-pting` | 92.0 ± 6.4 | 83.9 | 104.5 | 88.07 ± 23.10 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.7 | 0.9 | 11.4 | 1.61 ± 0.81 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.4 | 0.9 | 4.7 | 1.44 ± 0.52 |
| `lanjian/day_01 input-lanjian` | 1.3 ± 0.4 | 1.0 | 7.3 | 1.26 ± 0.48 |
| `lanjian/day_01 input-mattcl` | 2.2 ± 1.2 | 1.0 | 15.1 | 2.09 ± 1.24 |
| `lanjian/day_01 input-pting` | 1.6 ± 0.4 | 1.1 | 8.0 | 1.55 ± 0.55 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.3 | 0.8 | 3.3 | 1.20 ± 0.42 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.3 | 0.8 | 4.3 | 1.28 ± 0.43 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.0 ± 0.3 | 0.7 | 4.1 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.3 | 0.8 | 3.3 | 1.25 ± 0.44 |
| `mattcl-solver/aoc run 1 input-pting` | 1.5 ± 0.8 | 0.9 | 16.1 | 1.39 ± 0.87 |
| `python pting/day01.py input-aspidites` | 33.7 ± 4.3 | 28.4 | 47.7 | 32.29 ± 9.17 |
| `python pting/day01.py input-kcen` | 31.9 ± 3.0 | 27.7 | 42.7 | 30.50 ± 8.22 |
| `python pting/day01.py input-lanjian` | 32.0 ± 3.7 | 27.1 | 56.8 | 30.67 ± 8.52 |
| `python pting/day01.py input-mattcl` | 35.8 ± 5.1 | 29.8 | 53.1 | 34.25 ± 9.95 |
| `python pting/day01.py input-pting` | 32.6 ± 3.2 | 28.5 | 44.8 | 31.21 ± 8.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
