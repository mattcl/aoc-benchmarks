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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.2 ± 1.4 | 11.0 | 28.2 | 9.42 ± 4.47 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.1 ± 0.7 | 11.2 | 16.0 | 9.37 ± 4.36 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 13.1 ± 1.5 | 11.6 | 25.0 | 10.10 ± 4.81 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.8 ± 0.9 | 11.3 | 15.6 | 9.87 ± 4.61 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.5 ± 1.0 | 11.0 | 18.4 | 9.65 ± 4.52 |
| `kcen/2022/01/solve input-aspidites` | 110.5 ± 9.3 | 93.5 | 138.5 | 85.21 ± 39.97 |
| `kcen/2022/01/solve input-kcen` | 105.6 ± 12.3 | 84.2 | 133.2 | 81.47 ± 38.77 |
| `kcen/2022/01/solve input-lanjian` | 103.3 ± 15.6 | 85.3 | 153.1 | 79.64 ± 38.67 |
| `kcen/2022/01/solve input-mattcl` | 109.6 ± 8.7 | 94.9 | 140.9 | 84.53 ± 39.59 |
| `kcen/2022/01/solve input-pting` | 108.7 ± 10.8 | 91.7 | 132.4 | 83.88 ± 39.59 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.8 | 0.8 | 11.9 | 1.22 ± 0.82 |
| `lanjian/day_01 input-kcen` | 1.9 ± 0.8 | 0.5 | 7.0 | 1.45 ± 0.93 |
| `lanjian/day_01 input-lanjian` | 2.1 ± 0.8 | 0.8 | 7.5 | 1.58 ± 0.97 |
| `lanjian/day_01 input-mattcl` | 1.9 ± 0.7 | 0.7 | 4.9 | 1.48 ± 0.86 |
| `lanjian/day_01 input-pting` | 1.6 ± 0.9 | 0.7 | 11.5 | 1.23 ± 0.89 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.8 ± 0.8 | 0.5 | 10.4 | 1.37 ± 0.91 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.5 ± 0.9 | 0.5 | 9.5 | 1.16 ± 0.89 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.6 | 0.6 | 5.2 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 0.6 | 0.7 | 4.4 | 1.28 ± 0.74 |
| `mattcl-solver/aoc run 1 input-pting` | 1.8 ± 0.9 | 0.8 | 7.3 | 1.43 ± 0.97 |
| `python pting/day01.py input-aspidites` | 38.2 ± 10.3 | 30.6 | 77.3 | 29.48 ± 15.75 |
| `python pting/day01.py input-kcen` | 36.6 ± 8.3 | 27.9 | 76.3 | 28.26 ± 14.53 |
| `python pting/day01.py input-lanjian` | 34.4 ± 4.7 | 28.1 | 65.0 | 26.52 ± 12.77 |
| `python pting/day01.py input-mattcl` | 33.4 ± 6.6 | 25.9 | 59.6 | 25.77 ± 12.93 |
| `python pting/day01.py input-pting` | 35.3 ± 5.8 | 29.3 | 73.7 | 27.22 ± 13.34 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
