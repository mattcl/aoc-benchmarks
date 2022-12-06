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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 15.0 ± 3.9 | 12.1 | 37.3 | 7.59 ± 6.03 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.1 ± 3.0 | 11.7 | 35.4 | 7.11 ± 5.53 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 13.7 ± 2.1 | 11.6 | 35.4 | 6.94 ± 5.31 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 16.1 ± 4.9 | 12.0 | 35.0 | 8.13 ± 6.57 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.5 ± 2.7 | 12.2 | 28.7 | 7.32 ± 5.65 |
| `kcen/2022/01/solve input-aspidites` | 279.8 ± 116.7 | 176.3 | 535.0 | 141.51 ± 121.35 |
| `kcen/2022/01/solve input-kcen` | 199.4 ± 17.3 | 176.3 | 240.7 | 100.81 ± 76.04 |
| `kcen/2022/01/solve input-lanjian` | 174.2 ± 11.7 | 155.2 | 196.0 | 88.09 ± 66.26 |
| `kcen/2022/01/solve input-mattcl` | 189.2 ± 21.6 | 155.2 | 220.7 | 95.65 ± 72.49 |
| `kcen/2022/01/solve input-pting` | 208.0 ± 26.5 | 156.7 | 246.4 | 105.20 ± 79.95 |
| `lanjian/day_01 input-aspidites` | 2.8 ± 1.9 | 0.5 | 16.4 | 1.42 ± 1.42 |
| `lanjian/day_01 input-kcen` | 2.9 ± 1.5 | 0.3 | 9.2 | 1.48 ± 1.34 |
| `lanjian/day_01 input-lanjian` | 2.9 ± 1.6 | 0.6 | 13.2 | 1.48 ± 1.39 |
| `lanjian/day_01 input-mattcl` | 2.0 ± 1.5 | 0.1 | 15.0 | 1.00 |
| `lanjian/day_01 input-pting` | 2.2 ± 1.1 | 0.3 | 10.2 | 1.14 ± 1.03 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.7 ± 3.0 | 0.4 | 23.7 | 1.87 ± 2.06 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.8 ± 1.9 | 0.5 | 14.6 | 1.42 ± 1.42 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.2 ± 1.1 | 0.2 | 6.1 | 1.13 ± 1.02 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.0 ± 2.1 | 0.0 | 28.6 | 1.02 ± 1.32 |
| `mattcl-solver/aoc run 1 input-pting` | 2.4 ± 1.2 | 0.3 | 11.7 | 1.20 ± 1.09 |
| `python pting/day01.py input-aspidites` | 61.8 ± 8.1 | 47.6 | 81.5 | 31.27 ± 23.78 |
| `python pting/day01.py input-kcen` | 75.7 ± 22.3 | 57.1 | 172.5 | 38.28 ± 30.82 |
| `python pting/day01.py input-lanjian` | 63.7 ± 10.0 | 50.7 | 91.9 | 32.23 ± 24.68 |
| `python pting/day01.py input-mattcl` | 68.6 ± 21.9 | 48.9 | 166.8 | 34.71 ± 28.27 |
| `python pting/day01.py input-pting` | 63.8 ± 10.2 | 47.7 | 96.3 | 32.27 ± 24.72 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
