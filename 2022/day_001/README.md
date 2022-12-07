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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.8 ± 1.8 | 12.7 | 24.6 | 5.21 ± 2.20 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.8 ± 2.2 | 12.5 | 26.4 | 5.18 ± 2.23 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 15.0 ± 2.0 | 12.3 | 28.0 | 5.28 ± 2.25 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 15.6 ± 3.0 | 12.8 | 32.3 | 5.48 ± 2.45 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.8 ± 3.8 | 12.6 | 35.8 | 5.56 ± 2.61 |
| `kcen/2022/01/solve input-aspidites` | 184.5 ± 23.7 | 146.6 | 217.6 | 64.70 ± 27.41 |
| `kcen/2022/01/solve input-kcen` | 167.8 ± 13.5 | 144.6 | 190.2 | 58.87 ± 24.23 |
| `kcen/2022/01/solve input-lanjian` | 166.2 ± 21.3 | 137.9 | 226.9 | 58.29 ± 24.68 |
| `kcen/2022/01/solve input-mattcl` | 179.5 ± 22.6 | 154.6 | 248.0 | 62.95 ± 26.61 |
| `kcen/2022/01/solve input-pting` | 177.1 ± 24.0 | 143.1 | 221.4 | 62.11 ± 26.45 |
| `lanjian/day_01 input-aspidites` | 3.2 ± 1.6 | 0.9 | 15.7 | 1.13 ± 0.72 |
| `lanjian/day_01 input-kcen` | 3.4 ± 2.0 | 0.8 | 28.2 | 1.20 ± 0.84 |
| `lanjian/day_01 input-lanjian` | 3.7 ± 2.1 | 1.1 | 24.2 | 1.31 ± 0.91 |
| `lanjian/day_01 input-mattcl` | 3.3 ± 1.4 | 0.8 | 14.3 | 1.16 ± 0.67 |
| `lanjian/day_01 input-pting` | 3.0 ± 1.4 | 0.8 | 13.8 | 1.07 ± 0.66 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.3 ± 1.6 | 0.7 | 11.8 | 1.16 ± 0.74 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.9 ± 1.4 | 0.4 | 10.0 | 1.02 ± 0.65 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.9 ± 1.3 | 0.5 | 12.8 | 1.02 ± 0.62 |
| `mattcl-solver/aoc run 1 input-mattcl` | 5.5 ± 5.0 | 0.9 | 40.9 | 1.94 ± 1.92 |
| `mattcl-solver/aoc run 1 input-pting` | 2.9 ± 1.2 | 0.4 | 8.1 | 1.00 |
| `python pting/day01.py input-aspidites` | 57.1 ± 10.1 | 45.3 | 109.5 | 20.02 ± 8.82 |
| `python pting/day01.py input-kcen` | 54.0 ± 12.0 | 42.4 | 113.3 | 18.93 ± 8.72 |
| `python pting/day01.py input-lanjian` | 57.0 ± 9.9 | 41.2 | 92.0 | 19.98 ± 8.78 |
| `python pting/day01.py input-mattcl` | 58.1 ± 12.1 | 41.3 | 94.1 | 20.37 ± 9.25 |
| `python pting/day01.py input-pting` | 56.8 ± 7.9 | 44.6 | 72.6 | 19.92 ± 8.50 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
