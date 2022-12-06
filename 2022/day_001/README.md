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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.3 ± 2.5 | 11.8 | 28.9 | 7.67 ± 5.27 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.1 ± 2.7 | 11.7 | 32.9 | 7.59 ± 5.25 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.1 ± 2.5 | 11.8 | 27.9 | 7.59 ± 5.22 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.8 ± 1.8 | 11.8 | 29.1 | 7.42 ± 5.02 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.6 ± 2.4 | 12.2 | 26.4 | 7.83 ± 5.36 |
| `kcen/2022/01/solve input-aspidites` | 160.1 ± 19.2 | 131.7 | 199.5 | 85.97 ± 58.09 |
| `kcen/2022/01/solve input-kcen` | 170.9 ± 13.4 | 152.6 | 196.1 | 91.81 ± 61.47 |
| `kcen/2022/01/solve input-lanjian` | 188.9 ± 18.1 | 160.0 | 233.4 | 101.48 ± 68.17 |
| `kcen/2022/01/solve input-mattcl` | 240.5 ± 95.6 | 156.7 | 448.6 | 129.20 ± 100.07 |
| `kcen/2022/01/solve input-pting` | 190.9 ± 28.1 | 164.8 | 267.8 | 102.55 ± 69.84 |
| `lanjian/day_01 input-aspidites` | 2.6 ± 1.0 | 0.7 | 10.5 | 1.38 ± 1.07 |
| `lanjian/day_01 input-kcen` | 3.0 ± 1.4 | 0.7 | 11.6 | 1.60 ± 1.32 |
| `lanjian/day_01 input-lanjian` | 2.7 ± 1.8 | 0.5 | 19.2 | 1.45 ± 1.38 |
| `lanjian/day_01 input-mattcl` | 1.9 ± 1.1 | 0.3 | 8.3 | 1.01 ± 0.88 |
| `lanjian/day_01 input-pting` | 2.2 ± 1.0 | 0.4 | 7.3 | 1.17 ± 0.95 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.0 ± 1.2 | 0.0 | 8.7 | 1.09 ± 0.96 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.6 ± 1.4 | 0.3 | 12.4 | 1.41 ± 1.19 |
| `mattcl-solver/aoc run 1 input-lanjian` | 3.2 ± 1.5 | 0.7 | 13.8 | 1.70 ± 1.38 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.9 ± 1.2 | 0.1 | 13.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 2.7 ± 1.2 | 0.5 | 7.4 | 1.43 ± 1.16 |
| `python pting/day01.py input-aspidites` | 53.2 ± 6.8 | 44.3 | 73.4 | 28.56 ± 19.34 |
| `python pting/day01.py input-kcen` | 60.5 ± 8.6 | 46.5 | 83.1 | 32.49 ± 22.09 |
| `python pting/day01.py input-lanjian` | 63.4 ± 10.4 | 46.8 | 95.4 | 34.04 ± 23.32 |
| `python pting/day01.py input-mattcl` | 58.0 ± 7.6 | 45.6 | 80.0 | 31.17 ± 21.12 |
| `python pting/day01.py input-pting` | 49.3 ± 6.8 | 38.6 | 73.9 | 26.49 ± 17.99 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
