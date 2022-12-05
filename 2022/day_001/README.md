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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.8 ± 0.6 | 11.7 | 14.9 | 9.85 ± 3.46 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.5 ± 0.7 | 11.6 | 19.0 | 9.65 ± 3.41 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.4 ± 0.9 | 11.6 | 19.2 | 9.57 ± 3.40 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.3 ± 0.4 | 11.6 | 14.5 | 9.45 ± 3.31 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.8 ± 0.6 | 11.7 | 16.3 | 9.88 ± 3.47 |
| `kcen/2022/01/solve input-aspidites` | 112.5 ± 11.9 | 97.2 | 156.1 | 86.60 ± 31.56 |
| `kcen/2022/01/solve input-kcen` | 114.2 ± 21.3 | 90.7 | 164.8 | 87.92 ± 34.75 |
| `kcen/2022/01/solve input-lanjian` | 109.5 ± 10.1 | 91.9 | 131.7 | 84.26 ± 30.39 |
| `kcen/2022/01/solve input-mattcl` | 107.3 ± 8.9 | 91.6 | 124.6 | 82.61 ± 29.59 |
| `kcen/2022/01/solve input-pting` | 112.1 ± 11.4 | 96.7 | 144.0 | 86.29 ± 31.34 |
| `lanjian/day_01 input-aspidites` | 1.5 ± 0.4 | 0.8 | 5.3 | 1.17 ± 0.49 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.4 | 1.0 | 3.9 | 1.30 ± 0.56 |
| `lanjian/day_01 input-lanjian` | 1.5 ± 0.6 | 0.8 | 6.7 | 1.15 ± 0.63 |
| `lanjian/day_01 input-mattcl` | 1.7 ± 0.8 | 0.8 | 15.1 | 1.34 ± 0.77 |
| `lanjian/day_01 input-pting` | 1.8 ± 0.4 | 1.0 | 3.9 | 1.37 ± 0.56 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.4 ± 0.4 | 0.7 | 4.4 | 1.06 ± 0.46 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.7 ± 0.5 | 0.8 | 3.6 | 1.32 ± 0.58 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.5 | 0.7 | 5.3 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.5 ± 0.6 | 0.7 | 7.6 | 1.12 ± 0.61 |
| `mattcl-solver/aoc run 1 input-pting` | 1.7 ± 0.4 | 0.7 | 4.2 | 1.28 ± 0.56 |
| `python pting/day01.py input-aspidites` | 32.4 ± 4.5 | 28.1 | 66.8 | 24.91 ± 9.36 |
| `python pting/day01.py input-kcen` | 33.2 ± 3.3 | 29.1 | 46.9 | 25.55 ± 9.27 |
| `python pting/day01.py input-lanjian` | 36.4 ± 5.8 | 28.9 | 51.7 | 28.01 ± 10.74 |
| `python pting/day01.py input-mattcl` | 32.4 ± 3.7 | 27.8 | 45.4 | 24.92 ± 9.14 |
| `python pting/day01.py input-pting` | 33.9 ± 3.6 | 29.3 | 49.7 | 26.07 ± 9.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
