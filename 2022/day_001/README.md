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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 11.9 ± 0.5 | 11.4 | 15.6 | 10.35 ± 2.83 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.1 ± 0.5 | 11.4 | 14.4 | 10.48 ± 2.87 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.2 ± 1.3 | 11.4 | 24.3 | 10.59 ± 3.08 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.3 ± 0.4 | 11.6 | 14.1 | 10.63 ± 2.90 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.1 ± 0.5 | 11.4 | 14.8 | 10.51 ± 2.88 |
| `kcen/2022/01/solve input-aspidites` | 101.3 ± 7.2 | 91.6 | 130.0 | 87.83 ± 24.58 |
| `kcen/2022/01/solve input-kcen` | 102.0 ± 6.5 | 90.0 | 117.0 | 88.37 ± 24.59 |
| `kcen/2022/01/solve input-lanjian` | 109.0 ± 8.7 | 92.3 | 136.8 | 94.48 ± 26.67 |
| `kcen/2022/01/solve input-mattcl` | 109.7 ± 15.0 | 94.4 | 152.4 | 95.04 ± 28.83 |
| `kcen/2022/01/solve input-pting` | 105.8 ± 8.4 | 94.8 | 137.9 | 91.66 ± 25.87 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.8 | 0.8 | 10.9 | 1.38 ± 0.78 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.5 | 0.8 | 6.2 | 1.35 ± 0.54 |
| `lanjian/day_01 input-lanjian` | 1.9 ± 0.5 | 0.9 | 5.4 | 1.63 ± 0.64 |
| `lanjian/day_01 input-mattcl` | 1.6 ± 0.5 | 0.8 | 9.3 | 1.40 ± 0.59 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.4 | 0.9 | 4.2 | 1.18 ± 0.46 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.2 ± 0.5 | 0.7 | 6.1 | 1.08 ± 0.53 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.2 ± 0.3 | 0.7 | 3.2 | 1.06 ± 0.41 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.6 ± 0.4 | 0.6 | 3.6 | 1.34 ± 0.50 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.2 ± 0.3 | 0.7 | 2.8 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 0.6 | 0.7 | 9.0 | 1.07 ± 0.56 |
| `python pting/day01.py input-aspidites` | 33.4 ± 4.4 | 27.2 | 51.1 | 28.98 ± 8.71 |
| `python pting/day01.py input-kcen` | 33.8 ± 4.5 | 27.8 | 47.0 | 29.30 ± 8.83 |
| `python pting/day01.py input-lanjian` | 35.1 ± 5.3 | 29.2 | 59.6 | 30.45 ± 9.43 |
| `python pting/day01.py input-mattcl` | 39.8 ± 10.2 | 28.2 | 84.3 | 34.50 ± 12.89 |
| `python pting/day01.py input-pting` | 31.4 ± 2.6 | 27.3 | 41.8 | 27.19 ± 7.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
