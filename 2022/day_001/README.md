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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.0 ± 0.5 | 11.4 | 15.0 | 11.53 ± 3.63 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.1 ± 0.5 | 11.4 | 14.5 | 11.64 ± 3.66 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.2 ± 0.9 | 11.4 | 19.3 | 11.70 ± 3.75 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.2 ± 1.0 | 11.4 | 23.0 | 11.75 ± 3.78 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.3 ± 0.7 | 11.5 | 15.2 | 11.80 ± 3.73 |
| `kcen/2022/01/solve input-aspidites` | 100.7 ± 5.8 | 89.6 | 112.4 | 96.86 ± 30.66 |
| `kcen/2022/01/solve input-kcen` | 106.2 ± 15.3 | 91.6 | 155.7 | 102.10 ± 35.01 |
| `kcen/2022/01/solve input-lanjian` | 102.2 ± 8.0 | 90.7 | 127.6 | 98.29 ± 31.56 |
| `kcen/2022/01/solve input-mattcl` | 98.1 ± 5.4 | 90.2 | 111.0 | 94.31 ± 29.82 |
| `kcen/2022/01/solve input-pting` | 103.5 ± 8.8 | 92.6 | 133.9 | 99.53 ± 32.11 |
| `lanjian/day_01 input-aspidites` | 1.5 ± 0.5 | 0.8 | 9.4 | 1.48 ± 0.66 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.5 | 1.0 | 6.9 | 1.61 ± 0.73 |
| `lanjian/day_01 input-lanjian` | 1.4 ± 0.6 | 0.8 | 11.5 | 1.34 ± 0.72 |
| `lanjian/day_01 input-mattcl` | 1.7 ± 0.5 | 0.9 | 6.0 | 1.65 ± 0.72 |
| `lanjian/day_01 input-pting` | 1.3 ± 0.4 | 0.9 | 5.6 | 1.28 ± 0.54 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.4 ± 0.4 | 0.7 | 4.2 | 1.37 ± 0.58 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 0.6 | 0.7 | 8.2 | 1.30 ± 0.67 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.2 ± 0.5 | 0.7 | 9.7 | 1.14 ± 0.63 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.2 ± 0.5 | 0.8 | 5.6 | 1.15 ± 0.59 |
| `mattcl-solver/aoc run 1 input-pting` | 1.0 ± 0.3 | 0.7 | 6.5 | 1.00 |
| `python pting/day01.py input-aspidites` | 31.3 ± 2.6 | 27.3 | 42.4 | 30.10 ± 9.71 |
| `python pting/day01.py input-kcen` | 32.8 ± 4.3 | 27.9 | 49.4 | 31.54 ± 10.65 |
| `python pting/day01.py input-lanjian` | 33.3 ± 4.4 | 27.9 | 51.3 | 31.97 ± 10.81 |
| `python pting/day01.py input-mattcl` | 32.6 ± 3.2 | 28.0 | 42.4 | 31.31 ± 10.22 |
| `python pting/day01.py input-pting` | 31.3 ± 2.6 | 27.0 | 38.9 | 30.05 ± 9.68 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
