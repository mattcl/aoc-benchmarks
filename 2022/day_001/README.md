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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.4 ± 0.7 | 11.2 | 15.2 | 13.77 ± 8.15 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.0 ± 0.8 | 10.9 | 17.0 | 13.41 ± 7.95 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.5 ± 1.0 | 11.0 | 16.7 | 13.86 ± 8.25 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.3 ± 0.7 | 11.2 | 15.8 | 13.64 ± 8.07 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.0 ± 0.9 | 10.7 | 14.5 | 13.40 ± 7.96 |
| `kcen/2022/01/solve input-aspidites` | 116.6 ± 15.9 | 89.6 | 151.4 | 129.79 ± 78.48 |
| `kcen/2022/01/solve input-kcen` | 102.1 ± 7.9 | 86.6 | 124.9 | 113.62 ± 67.53 |
| `kcen/2022/01/solve input-lanjian` | 111.9 ± 22.5 | 91.0 | 174.8 | 124.49 ± 77.49 |
| `kcen/2022/01/solve input-mattcl` | 105.6 ± 10.2 | 91.6 | 148.6 | 117.50 ± 70.15 |
| `kcen/2022/01/solve input-pting` | 114.8 ± 19.3 | 91.2 | 202.6 | 127.77 ± 78.29 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.7 | 0.6 | 5.0 | 1.59 ± 1.20 |
| `lanjian/day_01 input-kcen` | 1.0 ± 0.3 | 0.5 | 3.4 | 1.08 ± 0.74 |
| `lanjian/day_01 input-lanjian` | 1.5 ± 0.6 | 0.6 | 8.4 | 1.67 ± 1.18 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 1.0 | 0.5 | 8.5 | 1.99 ± 1.61 |
| `lanjian/day_01 input-pting` | 1.3 ± 0.6 | 0.6 | 5.8 | 1.49 ± 1.12 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.0 ± 0.5 | 0.3 | 6.0 | 1.08 ± 0.85 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.2 ± 0.5 | 0.4 | 5.1 | 1.31 ± 0.97 |
| `mattcl-solver/aoc run 1 input-lanjian` | 0.9 ± 0.5 | 0.3 | 4.9 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.7 | 0.4 | 5.1 | 1.49 ± 1.16 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.7 | 0.4 | 5.6 | 1.48 ± 1.14 |
| `python pting/day01.py input-aspidites` | 33.7 ± 4.2 | 26.5 | 55.5 | 37.46 ± 22.56 |
| `python pting/day01.py input-kcen` | 32.4 ± 3.9 | 26.7 | 55.7 | 36.02 ± 21.66 |
| `python pting/day01.py input-lanjian` | 36.2 ± 5.6 | 27.5 | 57.5 | 40.29 ± 24.54 |
| `python pting/day01.py input-mattcl` | 32.1 ± 4.5 | 26.5 | 57.0 | 35.72 ± 21.63 |
| `python pting/day01.py input-pting` | 30.4 ± 2.5 | 26.1 | 36.9 | 33.81 ± 20.11 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
