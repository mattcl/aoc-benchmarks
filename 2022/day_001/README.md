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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.3 ± 0.6 | 11.5 | 14.6 | 9.20 ± 3.73 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.5 ± 0.7 | 11.3 | 16.2 | 9.33 ± 3.79 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.5 ± 0.8 | 11.1 | 14.7 | 9.34 ± 3.80 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.5 ± 1.1 | 10.9 | 22.0 | 9.35 ± 3.86 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.3 ± 0.8 | 11.0 | 15.5 | 9.17 ± 3.74 |
| `kcen/2022/01/solve input-aspidites` | 94.6 ± 9.9 | 77.0 | 123.6 | 70.74 ± 29.42 |
| `kcen/2022/01/solve input-kcen` | 108.6 ± 10.4 | 89.0 | 130.9 | 81.21 ± 33.60 |
| `kcen/2022/01/solve input-lanjian` | 109.7 ± 8.7 | 96.1 | 134.6 | 82.08 ± 33.67 |
| `kcen/2022/01/solve input-mattcl` | 132.7 ± 26.2 | 105.8 | 213.6 | 99.22 ± 44.47 |
| `kcen/2022/01/solve input-pting` | 113.4 ± 18.0 | 96.5 | 154.5 | 84.84 ± 36.69 |
| `lanjian/day_01 input-aspidites` | 2.0 ± 1.2 | 0.6 | 10.0 | 1.52 ± 1.06 |
| `lanjian/day_01 input-kcen` | 1.9 ± 0.6 | 0.6 | 5.2 | 1.40 ± 0.73 |
| `lanjian/day_01 input-lanjian` | 1.8 ± 1.0 | 0.8 | 9.3 | 1.33 ± 0.90 |
| `lanjian/day_01 input-mattcl` | 2.0 ± 0.8 | 0.7 | 11.5 | 1.53 ± 0.87 |
| `lanjian/day_01 input-pting` | 1.7 ± 0.7 | 0.7 | 5.4 | 1.28 ± 0.71 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.5 | 0.6 | 5.1 | 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.0 ± 1.0 | 0.3 | 10.6 | 1.53 ± 0.98 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.8 ± 0.6 | 0.6 | 8.2 | 1.37 ± 0.73 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.8 ± 0.7 | 0.4 | 5.0 | 1.38 ± 0.77 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.7 | 0.5 | 5.5 | 1.03 ± 0.65 |
| `python pting/day01.py input-aspidites` | 45.6 ± 18.1 | 29.9 | 145.6 | 34.09 ± 19.28 |
| `python pting/day01.py input-kcen` | 35.7 ± 8.1 | 27.1 | 66.0 | 26.67 ± 12.31 |
| `python pting/day01.py input-lanjian` | 35.2 ± 6.5 | 26.9 | 67.3 | 26.33 ± 11.68 |
| `python pting/day01.py input-mattcl` | 36.0 ± 9.0 | 26.6 | 81.3 | 26.90 ± 12.75 |
| `python pting/day01.py input-pting` | 33.3 ± 5.1 | 27.1 | 56.9 | 24.94 ± 10.75 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
