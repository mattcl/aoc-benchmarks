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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.1 ± 1.7 | 12.0 | 25.4 | 6.35 ± 2.92 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.5 ± 2.4 | 12.4 | 37.0 | 6.52 ± 3.09 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 15.0 ± 3.3 | 12.0 | 27.2 | 6.77 ± 3.35 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.6 ± 2.2 | 12.1 | 29.0 | 6.58 ± 3.08 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.4 ± 3.8 | 12.1 | 51.2 | 6.49 ± 3.36 |
| `kcen/2022/01/solve input-aspidites` | 189.4 ± 17.4 | 156.2 | 215.2 | 85.38 ± 38.71 |
| `kcen/2022/01/solve input-kcen` | 176.0 ± 15.0 | 156.9 | 204.5 | 79.37 ± 35.88 |
| `kcen/2022/01/solve input-lanjian` | 184.7 ± 29.8 | 164.3 | 269.8 | 83.26 ± 39.33 |
| `kcen/2022/01/solve input-mattcl` | 169.2 ± 16.3 | 147.2 | 210.0 | 76.29 ± 34.65 |
| `kcen/2022/01/solve input-pting` | 185.7 ± 28.8 | 151.5 | 254.0 | 83.72 ± 39.38 |
| `lanjian/day_01 input-aspidites` | 3.1 ± 1.6 | 0.9 | 17.3 | 1.39 ± 0.96 |
| `lanjian/day_01 input-kcen` | 3.5 ± 1.4 | 1.3 | 10.0 | 1.60 ± 0.94 |
| `lanjian/day_01 input-lanjian` | 4.2 ± 2.9 | 1.3 | 30.2 | 1.90 ± 1.56 |
| `lanjian/day_01 input-mattcl` | 3.0 ± 1.7 | 0.8 | 15.0 | 1.36 ± 0.98 |
| `lanjian/day_01 input-pting` | 3.5 ± 1.6 | 0.9 | 16.3 | 1.56 ± 1.02 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.9 ± 1.4 | 0.9 | 8.3 | 1.31 ± 0.85 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.2 ± 1.0 | 0.5 | 8.5 | 1.00 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.7 ± 1.4 | 0.6 | 13.6 | 1.23 ± 0.84 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.6 ± 1.5 | 0.6 | 14.9 | 1.16 ± 0.85 |
| `mattcl-solver/aoc run 1 input-pting` | 3.3 ± 1.6 | 1.0 | 19.6 | 1.48 ± 0.99 |
| `python pting/day01.py input-aspidites` | 104.5 ± 32.4 | 54.3 | 188.3 | 47.10 ± 25.50 |
| `python pting/day01.py input-kcen` | 64.6 ± 14.1 | 41.9 | 109.2 | 29.13 ± 14.41 |
| `python pting/day01.py input-lanjian` | 57.8 ± 7.3 | 45.7 | 76.3 | 26.07 ± 12.03 |
| `python pting/day01.py input-mattcl` | 56.9 ± 10.9 | 42.1 | 104.6 | 25.66 ± 12.40 |
| `python pting/day01.py input-pting` | 61.9 ± 13.3 | 44.7 | 120.7 | 27.92 ± 13.78 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
