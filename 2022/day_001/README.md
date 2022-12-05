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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.2 ± 2.2 | 11.2 | 27.3 | 11.21 ± 3.83 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.8 ± 2.0 | 11.3 | 27.1 | 10.90 ± 3.67 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.9 ± 2.3 | 11.4 | 26.6 | 11.01 ± 3.81 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.4 ± 0.6 | 11.4 | 15.5 | 10.58 ± 3.22 |
| `aspidites-solver/aoc -i input-pting -d 1` | 13.2 ± 0.6 | 11.7 | 15.0 | 11.21 ± 3.40 |
| `kcen/2022/01/solve input-aspidites` | 117.4 ± 25.5 | 89.1 | 220.2 | 99.94 ± 36.96 |
| `kcen/2022/01/solve input-kcen` | 108.7 ± 11.4 | 89.9 | 152.1 | 92.49 ± 29.38 |
| `kcen/2022/01/solve input-lanjian` | 130.7 ± 15.4 | 115.2 | 169.4 | 111.29 ± 35.84 |
| `kcen/2022/01/solve input-mattcl` | 110.0 ± 22.6 | 89.9 | 210.8 | 93.64 ± 34.01 |
| `kcen/2022/01/solve input-pting` | 112.1 ± 13.7 | 95.2 | 142.6 | 95.43 ± 30.87 |
| `lanjian/day_01 input-aspidites` | 1.9 ± 0.8 | 0.8 | 7.4 | 1.60 ± 0.83 |
| `lanjian/day_01 input-kcen` | 2.2 ± 0.9 | 0.9 | 8.8 | 1.89 ± 0.92 |
| `lanjian/day_01 input-lanjian` | 2.3 ± 1.3 | 0.9 | 12.8 | 1.99 ± 1.23 |
| `lanjian/day_01 input-mattcl` | 1.3 ± 0.2 | 0.9 | 4.0 | 1.12 ± 0.40 |
| `lanjian/day_01 input-pting` | 2.1 ± 0.8 | 0.9 | 6.9 | 1.75 ± 0.89 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.4 ± 0.8 | 0.7 | 13.1 | 1.20 ± 0.77 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.0 ± 0.7 | 0.7 | 5.2 | 1.66 ± 0.77 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.5 ± 0.7 | 0.7 | 10.2 | 1.24 ± 0.72 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.2 ± 0.4 | 0.7 | 3.9 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.9 ± 0.9 | 0.7 | 8.0 | 1.63 ± 0.88 |
| `python pting/day01.py input-aspidites` | 36.9 ± 7.8 | 27.5 | 72.5 | 31.43 ± 11.54 |
| `python pting/day01.py input-kcen` | 36.0 ± 8.2 | 27.7 | 78.6 | 30.66 ± 11.52 |
| `python pting/day01.py input-lanjian` | 36.7 ± 10.7 | 26.6 | 90.3 | 31.25 ± 13.06 |
| `python pting/day01.py input-mattcl` | 36.3 ± 7.8 | 28.2 | 62.5 | 30.88 ± 11.37 |
| `python pting/day01.py input-pting` | 32.3 ± 6.4 | 27.1 | 73.2 | 27.48 ± 9.88 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
