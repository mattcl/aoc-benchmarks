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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.1 ± 0.4 | 11.5 | 14.1 | 9.82 ± 3.67 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.0 ± 0.4 | 11.4 | 14.2 | 9.75 ± 3.64 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.5 ± 1.8 | 11.5 | 27.0 | 10.20 ± 4.07 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.5 ± 1.0 | 11.4 | 19.2 | 10.20 ± 3.88 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.1 ± 0.4 | 11.6 | 13.8 | 9.85 ± 3.68 |
| `kcen/2022/01/solve input-aspidites` | 114.3 ± 16.8 | 93.8 | 152.8 | 93.08 ± 37.22 |
| `kcen/2022/01/solve input-kcen` | 94.8 ± 5.3 | 89.3 | 109.6 | 77.19 ± 29.02 |
| `kcen/2022/01/solve input-lanjian` | 94.6 ± 4.0 | 88.2 | 105.7 | 77.05 ± 28.84 |
| `kcen/2022/01/solve input-mattcl` | 112.3 ± 12.3 | 94.7 | 140.0 | 91.46 ± 35.44 |
| `kcen/2022/01/solve input-pting` | 107.5 ± 9.4 | 94.3 | 133.6 | 87.53 ± 33.43 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.5 | 1.0 | 6.4 | 1.27 ± 0.65 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.6 | 0.9 | 11.4 | 1.23 ± 0.65 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.4 | 1.0 | 4.4 | 1.39 ± 0.62 |
| `lanjian/day_01 input-mattcl` | 1.5 ± 0.4 | 0.9 | 3.7 | 1.19 ± 0.53 |
| `lanjian/day_01 input-pting` | 1.5 ± 0.5 | 0.9 | 9.0 | 1.25 ± 0.63 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 0.5 | 0.9 | 5.6 | 1.23 ± 0.60 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 0.4 | 0.8 | 5.4 | 1.15 ± 0.56 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.2 ± 0.5 | 0.7 | 8.3 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.2 | 0.8 | 3.2 | 1.03 ± 0.43 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.6 | 0.8 | 11.9 | 1.08 ± 0.64 |
| `python pting/day01.py input-aspidites` | 34.7 ± 5.5 | 28.4 | 58.8 | 28.26 ± 11.42 |
| `python pting/day01.py input-kcen` | 30.9 ± 3.6 | 27.3 | 55.2 | 25.14 ± 9.80 |
| `python pting/day01.py input-lanjian` | 32.6 ± 4.6 | 27.7 | 57.6 | 26.57 ± 10.57 |
| `python pting/day01.py input-mattcl` | 31.6 ± 3.6 | 27.9 | 47.4 | 25.77 ± 10.01 |
| `python pting/day01.py input-pting` | 32.1 ± 3.2 | 28.2 | 43.2 | 26.16 ± 10.07 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
