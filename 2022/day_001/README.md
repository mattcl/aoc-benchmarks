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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 11.7 ± 0.4 | 11.3 | 13.7 | 10.32 ± 2.67 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.0 ± 0.5 | 11.4 | 14.0 | 10.56 ± 2.74 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.2 ± 1.8 | 11.2 | 26.2 | 10.80 ± 3.21 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.3 ± 0.7 | 11.4 | 16.5 | 10.84 ± 2.85 |
| `aspidites-solver/aoc -i input-pting -d 1` | 11.9 ± 0.3 | 11.4 | 13.7 | 10.48 ± 2.70 |
| `kcen/2022/01/solve input-aspidites` | 88.4 ± 6.3 | 82.6 | 109.2 | 77.94 ± 20.71 |
| `kcen/2022/01/solve input-kcen` | 95.9 ± 7.8 | 86.9 | 122.0 | 84.59 ± 22.73 |
| `kcen/2022/01/solve input-lanjian` | 113.1 ± 21.0 | 89.0 | 161.2 | 99.79 ± 31.54 |
| `kcen/2022/01/solve input-mattcl` | 101.0 ± 12.2 | 85.6 | 134.1 | 89.10 ± 25.22 |
| `kcen/2022/01/solve input-pting` | 98.4 ± 10.9 | 84.7 | 133.6 | 86.79 ± 24.20 |
| `lanjian/day_01 input-aspidites` | 1.3 ± 0.3 | 0.9 | 3.1 | 1.12 ± 0.37 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.8 | 1.0 | 13.8 | 1.41 ± 0.78 |
| `lanjian/day_01 input-lanjian` | 1.3 ± 0.3 | 0.9 | 5.7 | 1.12 ± 0.40 |
| `lanjian/day_01 input-mattcl` | 1.7 ± 0.8 | 0.9 | 11.6 | 1.47 ± 0.79 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.5 | 0.9 | 8.7 | 1.19 ± 0.54 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.2 ± 0.5 | 0.7 | 9.1 | 1.04 ± 0.50 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.2 ± 0.3 | 0.7 | 2.9 | 1.04 ± 0.35 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.1 ± 0.3 | 0.8 | 5.1 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.5 ± 0.6 | 0.8 | 6.5 | 1.34 ± 0.62 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.5 | 0.8 | 6.1 | 1.18 ± 0.51 |
| `python pting/day01.py input-aspidites` | 29.7 ± 4.3 | 25.6 | 49.2 | 26.19 ± 7.70 |
| `python pting/day01.py input-kcen` | 31.5 ± 5.3 | 26.3 | 56.1 | 27.81 ± 8.51 |
| `python pting/day01.py input-lanjian` | 28.9 ± 2.0 | 25.6 | 40.5 | 25.47 ± 6.75 |
| `python pting/day01.py input-mattcl` | 29.0 ± 2.4 | 25.8 | 38.1 | 25.61 ± 6.89 |
| `python pting/day01.py input-pting` | 28.6 ± 2.5 | 26.1 | 42.4 | 25.25 ± 6.82 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
