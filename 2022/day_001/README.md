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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.9 ± 1.3 | 12.1 | 24.7 | 6.66 ± 2.77 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.7 ± 2.0 | 12.1 | 24.4 | 7.07 ± 3.00 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.4 ± 1.6 | 12.4 | 24.9 | 6.93 ± 2.90 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 15.3 ± 3.8 | 12.2 | 43.2 | 7.32 ± 3.47 |
| `aspidites-solver/aoc -i input-pting -d 1` | 16.2 ± 4.4 | 11.3 | 37.1 | 7.79 ± 3.80 |
| `kcen/2022/01/solve input-aspidites` | 163.2 ± 19.3 | 134.1 | 217.9 | 78.24 ± 32.92 |
| `kcen/2022/01/solve input-kcen` | 201.9 ± 19.0 | 169.8 | 235.0 | 96.79 ± 40.13 |
| `kcen/2022/01/solve input-lanjian` | 173.9 ± 12.6 | 155.4 | 202.8 | 83.40 ± 34.22 |
| `kcen/2022/01/solve input-mattcl` | 161.0 ± 19.1 | 125.4 | 199.3 | 77.21 ± 32.50 |
| `kcen/2022/01/solve input-pting` | 200.4 ± 24.0 | 152.6 | 251.3 | 96.10 ± 40.48 |
| `lanjian/day_01 input-aspidites` | 2.5 ± 1.0 | 0.7 | 7.7 | 1.22 ± 0.70 |
| `lanjian/day_01 input-kcen` | 3.0 ± 1.1 | 1.0 | 13.7 | 1.44 ± 0.80 |
| `lanjian/day_01 input-lanjian` | 2.1 ± 0.8 | 0.8 | 8.2 | 1.00 |
| `lanjian/day_01 input-mattcl` | 2.8 ± 1.4 | 0.7 | 15.4 | 1.36 ± 0.86 |
| `lanjian/day_01 input-pting` | 2.7 ± 1.0 | 0.7 | 10.5 | 1.28 ± 0.69 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.0 ± 2.1 | 0.6 | 18.2 | 1.45 ± 1.17 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.3 ± 1.0 | 0.3 | 8.3 | 1.12 ± 0.67 |
| `mattcl-solver/aoc run 1 input-lanjian` | 3.2 ± 2.9 | 0.5 | 25.4 | 1.51 ± 1.54 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.5 ± 1.2 | 0.5 | 15.1 | 1.20 ± 0.76 |
| `mattcl-solver/aoc run 1 input-pting` | 2.2 ± 1.0 | 0.4 | 10.6 | 1.06 ± 0.64 |
| `python pting/day01.py input-aspidites` | 75.7 ± 39.3 | 42.0 | 205.3 | 36.29 ± 23.87 |
| `python pting/day01.py input-kcen` | 59.8 ± 9.8 | 43.9 | 76.3 | 28.66 ± 12.50 |
| `python pting/day01.py input-lanjian` | 53.3 ± 8.1 | 38.6 | 83.6 | 25.53 ± 11.02 |
| `python pting/day01.py input-mattcl` | 50.8 ± 6.8 | 41.5 | 67.8 | 24.34 ± 10.36 |
| `python pting/day01.py input-pting` | 59.5 ± 10.6 | 42.1 | 87.7 | 28.55 ± 12.60 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
