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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.9 ± 3.6 | 11.4 | 42.8 | 7.47 ± 6.93 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.4 ± 5.1 | 11.9 | 48.9 | 8.26 ± 7.85 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.0 ± 4.0 | 11.5 | 44.4 | 7.54 ± 7.07 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.8 ± 2.8 | 11.8 | 39.5 | 7.43 ± 6.80 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.0 ± 4.0 | 11.7 | 33.8 | 8.04 ± 7.48 |
| `kcen/2022/01/solve input-aspidites` | 190.5 ± 16.0 | 160.8 | 230.2 | 102.34 ± 91.66 |
| `kcen/2022/01/solve input-kcen` | 203.8 ± 30.8 | 172.3 | 290.8 | 109.51 ± 99.03 |
| `kcen/2022/01/solve input-lanjian` | 184.7 ± 20.0 | 160.2 | 236.6 | 99.24 ± 89.14 |
| `kcen/2022/01/solve input-mattcl` | 188.2 ± 26.2 | 157.2 | 269.7 | 101.11 ± 91.25 |
| `kcen/2022/01/solve input-pting` | 192.6 ± 29.1 | 151.1 | 256.3 | 103.49 ± 93.59 |
| `lanjian/day_01 input-aspidites` | 2.1 ± 1.0 | 0.4 | 13.4 | 1.10 ± 1.13 |
| `lanjian/day_01 input-kcen` | 2.5 ± 1.8 | 0.3 | 17.3 | 1.32 ± 1.54 |
| `lanjian/day_01 input-lanjian` | 3.3 ± 2.2 | 1.0 | 19.1 | 1.77 ± 1.96 |
| `lanjian/day_01 input-mattcl` | 2.1 ± 1.3 | 0.1 | 10.2 | 1.12 ± 1.22 |
| `lanjian/day_01 input-pting` | 2.4 ± 1.6 | 0.4 | 21.6 | 1.28 ± 1.44 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.9 ± 1.7 | 0.1 | 25.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 3.2 ± 3.3 | 0.4 | 43.6 | 1.74 ± 2.34 |
| `mattcl-solver/aoc run 1 input-lanjian` | 4.5 ± 3.7 | 0.7 | 25.5 | 2.40 ± 2.90 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.3 ± 1.4 | 0.2 | 19.2 | 1.22 ± 1.33 |
| `mattcl-solver/aoc run 1 input-pting` | 6.8 ± 6.7 | 0.2 | 36.2 | 3.65 ± 4.87 |
| `python pting/day01.py input-aspidites` | 54.2 ± 12.9 | 42.2 | 119.3 | 29.13 ± 26.88 |
| `python pting/day01.py input-kcen` | 62.6 ± 11.3 | 47.5 | 115.3 | 33.64 ± 30.60 |
| `python pting/day01.py input-lanjian` | 64.3 ± 8.7 | 52.8 | 92.9 | 34.53 ± 31.14 |
| `python pting/day01.py input-mattcl` | 61.0 ± 16.3 | 44.7 | 143.5 | 32.76 ± 30.49 |
| `python pting/day01.py input-pting` | 64.7 ± 15.0 | 46.6 | 127.6 | 34.75 ± 32.01 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
