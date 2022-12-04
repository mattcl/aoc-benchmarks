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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.8 ± 1.8 | 11.4 | 25.6 | 11.19 ± 4.98 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 11.9 ± 0.5 | 11.2 | 14.2 | 10.49 ± 4.45 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.1 ± 0.6 | 11.4 | 15.2 | 10.66 ± 4.53 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.3 ± 1.4 | 11.3 | 23.9 | 10.81 ± 4.72 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.2 ± 0.6 | 11.4 | 14.8 | 10.74 ± 4.56 |
| `kcen/2022/01/solve input-aspidites` | 104.0 ± 7.7 | 91.4 | 121.0 | 91.31 ± 39.11 |
| `kcen/2022/01/solve input-kcen` | 96.8 ± 6.4 | 87.5 | 109.1 | 84.98 ± 36.29 |
| `kcen/2022/01/solve input-lanjian` | 108.3 ± 14.7 | 82.7 | 136.0 | 95.05 ± 42.13 |
| `kcen/2022/01/solve input-mattcl` | 98.9 ± 10.9 | 88.8 | 146.6 | 86.79 ± 37.84 |
| `kcen/2022/01/solve input-pting` | 100.9 ± 9.9 | 86.1 | 133.1 | 88.61 ± 38.38 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 1.2 | 0.9 | 15.9 | 1.50 ± 1.25 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.6 | 0.9 | 5.9 | 1.51 ± 0.85 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.6 | 0.8 | 4.7 | 1.51 ± 0.80 |
| `lanjian/day_01 input-mattcl` | 1.4 ± 0.4 | 0.9 | 4.7 | 1.22 ± 0.63 |
| `lanjian/day_01 input-pting` | 1.5 ± 0.5 | 0.9 | 4.4 | 1.31 ± 0.70 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 0.8 | 0.8 | 12.2 | 1.31 ± 0.88 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 0.5 | 0.6 | 10.1 | 1.19 ± 0.68 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.7 ± 0.6 | 0.8 | 5.4 | 1.51 ± 0.85 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.1 ± 0.5 | 0.7 | 6.6 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.5 ± 1.1 | 0.7 | 12.9 | 1.28 ± 1.11 |
| `python pting/day01.py input-aspidites` | 34.2 ± 4.8 | 26.6 | 55.9 | 30.02 ± 13.35 |
| `python pting/day01.py input-kcen` | 32.7 ± 3.9 | 26.0 | 45.5 | 28.73 ± 12.60 |
| `python pting/day01.py input-lanjian` | 32.4 ± 4.0 | 26.0 | 46.8 | 28.43 ± 12.50 |
| `python pting/day01.py input-mattcl` | 29.7 ± 3.4 | 26.1 | 46.4 | 26.04 ± 11.39 |
| `python pting/day01.py input-pting` | 33.0 ± 3.9 | 26.2 | 46.9 | 28.98 ± 12.70 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
