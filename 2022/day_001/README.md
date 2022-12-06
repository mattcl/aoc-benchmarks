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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 18.8 ± 9.2 | 12.9 | 85.2 | 7.20 ± 4.97 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.0 ± 2.3 | 12.7 | 28.2 | 5.72 ± 2.92 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 15.3 ± 3.6 | 12.6 | 37.7 | 5.84 ± 3.16 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.5 ± 1.9 | 12.0 | 26.6 | 5.56 ± 2.80 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.5 ± 3.0 | 12.9 | 36.0 | 5.94 ± 3.11 |
| `kcen/2022/01/solve input-aspidites` | 183.2 ± 28.5 | 143.5 | 266.6 | 70.08 ± 35.79 |
| `kcen/2022/01/solve input-kcen` | 156.9 ± 21.3 | 128.1 | 208.8 | 60.04 ± 30.32 |
| `kcen/2022/01/solve input-lanjian` | 167.2 ± 17.3 | 142.6 | 217.1 | 63.98 ± 31.81 |
| `kcen/2022/01/solve input-mattcl` | 176.5 ± 35.0 | 132.8 | 262.7 | 67.52 ± 35.45 |
| `kcen/2022/01/solve input-pting` | 184.2 ± 22.5 | 150.1 | 220.0 | 70.48 ± 35.34 |
| `lanjian/day_01 input-aspidites` | 6.2 ± 8.7 | 1.1 | 106.1 | 2.38 ± 3.52 |
| `lanjian/day_01 input-kcen` | 3.1 ± 1.5 | 1.1 | 22.1 | 1.18 ± 0.81 |
| `lanjian/day_01 input-lanjian` | 3.1 ± 1.3 | 0.9 | 9.8 | 1.20 ± 0.76 |
| `lanjian/day_01 input-mattcl` | 3.3 ± 1.4 | 1.1 | 12.6 | 1.26 ± 0.81 |
| `lanjian/day_01 input-pting` | 3.1 ± 1.3 | 1.2 | 9.8 | 1.20 ± 0.76 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.8 ± 3.6 | 0.8 | 89.5 | 1.08 ± 1.47 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.6 ± 2.2 | 0.8 | 35.9 | 1.01 ± 0.98 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.6 ± 1.3 | 0.8 | 15.6 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.7 ± 3.6 | 0.8 | 82.4 | 1.03 ± 1.48 |
| `mattcl-solver/aoc run 1 input-pting` | 4.0 ± 3.0 | 1.1 | 40.4 | 1.51 ± 1.35 |
| `python pting/day01.py input-aspidites` | 59.7 ± 10.7 | 42.8 | 86.2 | 22.82 ± 11.83 |
| `python pting/day01.py input-kcen` | 53.3 ± 9.6 | 42.8 | 83.1 | 20.40 ± 10.58 |
| `python pting/day01.py input-lanjian` | 56.0 ± 10.1 | 41.6 | 86.1 | 21.41 ± 11.11 |
| `python pting/day01.py input-mattcl` | 54.7 ± 10.7 | 42.6 | 85.9 | 20.93 ± 10.97 |
| `python pting/day01.py input-pting` | 60.0 ± 10.7 | 46.6 | 108.6 | 22.97 ± 11.90 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
