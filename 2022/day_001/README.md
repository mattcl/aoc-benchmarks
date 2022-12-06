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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.8 ± 1.6 | 12.6 | 24.4 | 7.97 ± 4.91 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.7 ± 2.7 | 12.3 | 25.6 | 7.93 ± 5.02 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.7 ± 2.0 | 12.5 | 26.1 | 7.93 ± 4.92 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.1 ± 1.2 | 12.3 | 23.3 | 7.60 ± 4.65 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.6 ± 3.8 | 12.2 | 33.7 | 8.41 ± 5.49 |
| `kcen/2022/01/solve input-aspidites` | 176.4 ± 20.7 | 147.6 | 218.9 | 94.99 ± 58.60 |
| `kcen/2022/01/solve input-kcen` | 191.4 ± 12.1 | 174.7 | 209.7 | 103.10 ± 62.78 |
| `kcen/2022/01/solve input-lanjian` | 157.8 ± 23.5 | 135.1 | 205.1 | 84.97 ± 53.00 |
| `kcen/2022/01/solve input-mattcl` | 183.7 ± 21.0 | 144.6 | 216.6 | 98.92 ± 60.96 |
| `kcen/2022/01/solve input-pting` | 254.1 ± 102.8 | 164.9 | 509.8 | 136.84 ± 99.68 |
| `lanjian/day_01 input-aspidites` | 2.5 ± 1.2 | 0.6 | 7.9 | 1.33 ± 1.03 |
| `lanjian/day_01 input-kcen` | 2.8 ± 1.1 | 0.9 | 6.7 | 1.51 ± 1.10 |
| `lanjian/day_01 input-lanjian` | 2.2 ± 0.9 | 0.6 | 6.7 | 1.19 ± 0.87 |
| `lanjian/day_01 input-mattcl` | 3.5 ± 1.9 | 0.7 | 17.8 | 1.87 ± 1.53 |
| `lanjian/day_01 input-pting` | 3.1 ± 1.7 | 1.1 | 13.4 | 1.67 ± 1.35 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.5 ± 1.2 | 0.6 | 9.1 | 1.34 ± 1.03 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.9 ± 1.3 | 0.6 | 13.6 | 1.57 ± 1.17 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.1 ± 1.1 | 0.5 | 8.6 | 1.16 ± 0.91 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.9 ± 1.1 | 0.3 | 10.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 4.0 ± 2.8 | 0.4 | 25.1 | 2.14 ± 1.98 |
| `python pting/day01.py input-aspidites` | 61.4 ± 7.6 | 47.9 | 75.8 | 33.09 ± 20.45 |
| `python pting/day01.py input-kcen` | 53.3 ± 6.5 | 40.4 | 70.5 | 28.68 ± 17.72 |
| `python pting/day01.py input-lanjian` | 78.3 ± 29.3 | 47.0 | 172.6 | 42.18 ± 30.04 |
| `python pting/day01.py input-mattcl` | 60.3 ± 7.5 | 46.3 | 79.5 | 32.45 ± 20.06 |
| `python pting/day01.py input-pting` | 66.8 ± 10.7 | 51.0 | 97.4 | 35.98 ± 22.54 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
