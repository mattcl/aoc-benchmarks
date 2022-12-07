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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.9 ± 2.2 | 12.0 | 26.6 | 7.18 ± 5.22 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.6 ± 2.4 | 12.2 | 29.4 | 7.03 ± 5.14 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.3 ± 2.1 | 11.8 | 26.3 | 6.90 ± 5.01 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 15.2 ± 3.5 | 12.3 | 37.4 | 7.33 ± 5.49 |
| `aspidites-solver/aoc -i input-pting -d 1` | 16.9 ± 4.8 | 12.3 | 37.1 | 8.16 ± 6.26 |
| `kcen/2022/01/solve input-aspidites` | 173.0 ± 18.2 | 148.1 | 214.5 | 83.43 ± 60.03 |
| `kcen/2022/01/solve input-kcen` | 180.5 ± 26.6 | 137.5 | 228.8 | 87.04 ± 63.27 |
| `kcen/2022/01/solve input-lanjian` | 172.2 ± 20.4 | 135.5 | 205.2 | 83.06 ± 59.93 |
| `kcen/2022/01/solve input-mattcl` | 320.1 ± 192.7 | 154.9 | 722.5 | 154.37 ± 143.91 |
| `kcen/2022/01/solve input-pting` | 161.6 ± 21.1 | 134.0 | 213.6 | 77.92 ± 56.39 |
| `lanjian/day_01 input-aspidites` | 2.9 ± 1.1 | 0.8 | 9.3 | 1.40 ± 1.14 |
| `lanjian/day_01 input-kcen` | 3.4 ± 1.5 | 0.6 | 12.8 | 1.63 ± 1.36 |
| `lanjian/day_01 input-lanjian` | 2.9 ± 1.1 | 0.6 | 12.0 | 1.39 ± 1.13 |
| `lanjian/day_01 input-mattcl` | 2.6 ± 1.6 | 0.1 | 23.9 | 1.24 ± 1.17 |
| `lanjian/day_01 input-pting` | 2.1 ± 1.5 | 0.0 | 21.1 | 1.00 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.7 ± 1.6 | 0.2 | 23.9 | 1.31 ± 1.21 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.9 ± 1.4 | 0.6 | 15.9 | 1.38 ± 1.19 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.5 ± 1.3 | 0.1 | 9.6 | 1.19 ± 1.04 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.6 ± 1.7 | 0.4 | 18.5 | 1.25 ± 1.20 |
| `mattcl-solver/aoc run 1 input-pting` | 2.4 ± 1.5 | 0.1 | 16.4 | 1.16 ± 1.10 |
| `python pting/day01.py input-aspidites` | 52.8 ± 9.8 | 41.5 | 80.6 | 25.48 ± 18.74 |
| `python pting/day01.py input-kcen` | 54.3 ± 7.4 | 40.7 | 74.6 | 26.18 ± 18.97 |
| `python pting/day01.py input-lanjian` | 54.7 ± 6.8 | 43.5 | 75.1 | 26.39 ± 19.07 |
| `python pting/day01.py input-mattcl` | 52.5 ± 5.8 | 43.5 | 68.9 | 25.33 ± 18.25 |
| `python pting/day01.py input-pting` | 49.1 ± 7.0 | 40.8 | 73.2 | 23.66 ± 17.18 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
