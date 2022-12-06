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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.9 ± 1.4 | 12.9 | 26.5 | 6.18 ± 4.04 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.5 ± 2.0 | 13.2 | 26.4 | 6.43 ± 4.23 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 15.7 ± 4.2 | 12.7 | 41.7 | 6.50 ± 4.55 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.4 ± 1.4 | 12.7 | 26.5 | 5.97 ± 3.90 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.8 ± 2.9 | 12.7 | 31.5 | 6.55 ± 4.40 |
| `kcen/2022/01/solve input-aspidites` | 191.7 ± 26.6 | 149.8 | 239.3 | 79.63 ± 52.61 |
| `kcen/2022/01/solve input-kcen` | 170.3 ± 21.0 | 143.6 | 211.5 | 70.72 ± 46.51 |
| `kcen/2022/01/solve input-lanjian` | 151.5 ± 18.4 | 127.9 | 188.5 | 62.91 ± 41.35 |
| `kcen/2022/01/solve input-mattcl` | 148.3 ± 15.3 | 133.6 | 181.2 | 61.59 ± 40.29 |
| `kcen/2022/01/solve input-pting` | 171.0 ± 20.7 | 146.1 | 220.9 | 71.03 ± 46.68 |
| `lanjian/day_01 input-aspidites` | 3.1 ± 1.3 | 1.1 | 15.6 | 1.27 ± 0.98 |
| `lanjian/day_01 input-kcen` | 5.9 ± 5.5 | 1.5 | 67.6 | 2.45 ± 2.78 |
| `lanjian/day_01 input-lanjian` | 2.7 ± 1.6 | 0.9 | 25.5 | 1.13 ± 0.98 |
| `lanjian/day_01 input-mattcl` | 3.1 ± 1.2 | 1.2 | 9.4 | 1.28 ± 0.98 |
| `lanjian/day_01 input-pting` | 2.9 ± 1.2 | 1.2 | 10.7 | 1.22 ± 0.93 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.5 ± 1.2 | 0.7 | 17.0 | 1.05 ± 0.85 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.8 ± 1.3 | 0.8 | 12.0 | 1.15 ± 0.92 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.4 ± 1.6 | 0.6 | 17.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 4.5 ± 5.2 | 0.7 | 52.8 | 1.85 ± 2.47 |
| `mattcl-solver/aoc run 1 input-pting` | 3.1 ± 1.0 | 0.9 | 10.2 | 1.28 ± 0.92 |
| `python pting/day01.py input-aspidites` | 58.6 ± 10.6 | 42.3 | 83.7 | 24.35 ± 16.33 |
| `python pting/day01.py input-kcen` | 53.8 ± 9.9 | 39.8 | 81.2 | 22.35 ± 15.01 |
| `python pting/day01.py input-lanjian` | 51.8 ± 9.4 | 37.0 | 74.3 | 21.49 ± 14.42 |
| `python pting/day01.py input-mattcl` | 49.9 ± 8.8 | 39.0 | 78.2 | 20.71 ± 13.87 |
| `python pting/day01.py input-pting` | 52.4 ± 9.2 | 38.8 | 72.2 | 21.75 ± 14.56 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
