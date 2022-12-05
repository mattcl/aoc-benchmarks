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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.1 ± 1.0 | 7.0 | 18.5 | 13.51 ± 2.89 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 11.5 ± 0.4 | 11.0 | 13.2 | 12.87 ± 2.57 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 11.7 ± 0.4 | 11.2 | 13.8 | 13.07 ± 2.62 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.4 ± 0.9 | 11.4 | 23.4 | 13.88 ± 2.94 |
| `aspidites-solver/aoc -i input-pting -d 1` | 11.8 ± 0.5 | 11.1 | 13.6 | 13.23 ± 2.66 |
| `kcen/2022/01/solve input-aspidites` | 94.7 ± 5.9 | 86.6 | 112.1 | 105.92 ± 21.92 |
| `kcen/2022/01/solve input-kcen` | 94.5 ± 5.5 | 84.5 | 108.7 | 105.76 ± 21.74 |
| `kcen/2022/01/solve input-lanjian` | 96.4 ± 8.9 | 87.4 | 126.7 | 107.85 ± 23.50 |
| `kcen/2022/01/solve input-mattcl` | 106.0 ± 8.4 | 93.3 | 130.8 | 118.54 ± 25.19 |
| `kcen/2022/01/solve input-pting` | 97.0 ± 6.4 | 84.7 | 119.3 | 108.54 ± 22.58 |
| `lanjian/day_01 input-aspidites` | 1.9 ± 1.0 | 0.8 | 12.2 | 2.11 ± 1.24 |
| `lanjian/day_01 input-kcen` | 1.4 ± 0.4 | 0.9 | 6.9 | 1.62 ± 0.57 |
| `lanjian/day_01 input-lanjian` | 1.2 ± 0.4 | 0.7 | 6.1 | 1.39 ± 0.54 |
| `lanjian/day_01 input-mattcl` | 1.3 ± 0.4 | 0.8 | 6.2 | 1.43 ± 0.52 |
| `lanjian/day_01 input-pting` | 1.3 ± 0.3 | 0.8 | 2.8 | 1.40 ± 0.42 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.4 ± 0.4 | 0.6 | 5.7 | 1.52 ± 0.57 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.1 ± 0.3 | 0.7 | 3.6 | 1.24 ± 0.40 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.1 ± 0.4 | 0.7 | 9.4 | 1.22 ± 0.55 |
| `mattcl-solver/aoc run 1 input-mattcl` | 0.9 ± 0.2 | 0.5 | 2.5 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.0 ± 0.4 | 0.6 | 7.7 | 1.14 ± 0.50 |
| `python pting/day01.py input-aspidites` | 36.1 ± 11.3 | 27.4 | 94.2 | 40.40 ± 14.92 |
| `python pting/day01.py input-kcen` | 31.4 ± 3.7 | 26.3 | 42.3 | 35.12 ± 8.06 |
| `python pting/day01.py input-lanjian` | 29.8 ± 2.1 | 26.8 | 37.0 | 33.33 ± 6.98 |
| `python pting/day01.py input-mattcl` | 31.4 ± 3.7 | 25.6 | 43.5 | 35.16 ± 8.07 |
| `python pting/day01.py input-pting` | 29.8 ± 2.6 | 26.2 | 36.0 | 33.32 ± 7.17 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
