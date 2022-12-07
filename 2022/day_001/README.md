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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.3 ± 3.6 | 11.8 | 49.0 | 8.80 ± 6.27 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 13.9 ± 2.5 | 11.6 | 38.7 | 8.58 ± 5.92 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 19.7 ± 11.9 | 12.4 | 73.8 | 12.18 ± 10.93 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.6 ± 2.4 | 12.3 | 26.2 | 9.02 ± 6.19 |
| `aspidites-solver/aoc -i input-pting -d 1` | 13.9 ± 1.4 | 11.6 | 24.1 | 8.57 ± 5.76 |
| `kcen/2022/01/solve input-aspidites` | 150.3 ± 21.4 | 124.9 | 209.6 | 92.81 ± 63.14 |
| `kcen/2022/01/solve input-kcen` | 150.9 ± 20.2 | 117.6 | 189.6 | 93.16 ± 63.23 |
| `kcen/2022/01/solve input-lanjian` | 182.7 ± 50.7 | 136.3 | 296.4 | 112.78 ± 81.31 |
| `kcen/2022/01/solve input-mattcl` | 152.0 ± 20.9 | 120.2 | 184.4 | 93.88 ± 63.78 |
| `kcen/2022/01/solve input-pting` | 167.5 ± 22.3 | 120.9 | 216.4 | 103.40 ± 70.16 |
| `lanjian/day_01 input-aspidites` | 3.4 ± 1.9 | 0.7 | 21.4 | 2.10 ± 1.83 |
| `lanjian/day_01 input-kcen` | 2.2 ± 1.6 | 0.5 | 24.1 | 1.37 ± 1.36 |
| `lanjian/day_01 input-lanjian` | 2.7 ± 2.4 | 0.7 | 41.6 | 1.65 ± 1.87 |
| `lanjian/day_01 input-mattcl` | 2.2 ± 0.9 | 0.7 | 6.8 | 1.34 ± 1.05 |
| `lanjian/day_01 input-pting` | 2.2 ± 1.3 | 0.6 | 19.6 | 1.38 ± 1.22 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.9 ± 1.2 | 0.3 | 10.5 | 1.18 ± 1.08 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.8 ± 1.0 | 0.2 | 6.4 | 1.12 ± 0.98 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.6 ± 1.1 | 0.4 | 12.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.8 ± 1.5 | 0.6 | 14.6 | 1.75 ± 1.48 |
| `mattcl-solver/aoc run 1 input-pting` | 2.4 ± 1.4 | 0.3 | 21.1 | 1.50 ± 1.30 |
| `python pting/day01.py input-aspidites` | 45.5 ± 6.7 | 35.1 | 70.7 | 28.11 ± 19.15 |
| `python pting/day01.py input-kcen` | 44.5 ± 8.9 | 33.1 | 66.6 | 27.48 ± 19.10 |
| `python pting/day01.py input-lanjian` | 46.4 ± 6.4 | 35.8 | 62.5 | 28.64 ± 19.45 |
| `python pting/day01.py input-mattcl` | 51.1 ± 6.5 | 38.8 | 70.7 | 31.56 ± 21.38 |
| `python pting/day01.py input-pting` | 49.1 ± 6.9 | 34.2 | 67.0 | 30.33 ± 20.63 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
