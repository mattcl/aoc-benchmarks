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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 47.4 ± 28.0 | 17.8 | 140.2 | 17.52 ± 12.92 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.6 ± 3.6 | 12.1 | 46.9 | 5.76 ± 2.87 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.6 ± 2.3 | 12.4 | 26.7 | 5.38 ± 2.52 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.6 ± 2.5 | 12.4 | 32.1 | 5.41 ± 2.55 |
| `aspidites-solver/aoc -i input-pting -d 1` | 17.0 ± 6.2 | 12.0 | 47.1 | 6.27 ± 3.59 |
| `kcen/2022/01/solve input-aspidites` | 214.5 ± 82.7 | 147.7 | 389.3 | 79.31 ± 46.45 |
| `kcen/2022/01/solve input-kcen` | 180.2 ± 23.5 | 159.3 | 249.0 | 66.64 ± 30.63 |
| `kcen/2022/01/solve input-lanjian` | 166.2 ± 19.1 | 141.7 | 211.2 | 61.45 ± 27.99 |
| `kcen/2022/01/solve input-mattcl` | 167.7 ± 17.5 | 141.9 | 202.3 | 62.00 ± 28.08 |
| `kcen/2022/01/solve input-pting` | 181.8 ± 10.9 | 169.7 | 203.7 | 67.22 ± 29.90 |
| `lanjian/day_01 input-aspidites` | 3.3 ± 1.5 | 1.1 | 13.1 | 1.23 ± 0.78 |
| `lanjian/day_01 input-kcen` | 3.8 ± 1.6 | 1.3 | 20.2 | 1.40 ± 0.86 |
| `lanjian/day_01 input-lanjian` | 2.7 ± 2.0 | 0.7 | 21.0 | 1.01 ± 0.85 |
| `lanjian/day_01 input-mattcl` | 2.7 ± 1.2 | 0.7 | 12.0 | 1.00 |
| `lanjian/day_01 input-pting` | 3.4 ± 1.3 | 1.1 | 11.1 | 1.26 ± 0.74 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.2 ± 1.5 | 1.0 | 20.3 | 1.17 ± 0.75 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.9 ± 1.4 | 0.7 | 13.9 | 1.09 ± 0.69 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.8 ± 2.0 | 0.4 | 40.3 | 1.05 ± 0.88 |
| `mattcl-solver/aoc run 1 input-mattcl` | 3.1 ± 1.4 | 0.7 | 12.4 | 1.16 ± 0.73 |
| `mattcl-solver/aoc run 1 input-pting` | 3.0 ± 1.7 | 0.8 | 14.6 | 1.10 ± 0.78 |
| `python pting/day01.py input-aspidites` | 54.7 ± 7.9 | 44.7 | 75.8 | 20.25 ± 9.39 |
| `python pting/day01.py input-kcen` | 59.8 ± 10.7 | 42.9 | 89.8 | 22.11 ± 10.52 |
| `python pting/day01.py input-lanjian` | 50.6 ± 5.9 | 41.6 | 71.9 | 18.73 ± 8.54 |
| `python pting/day01.py input-mattcl` | 52.5 ± 6.7 | 39.9 | 70.1 | 19.41 ± 8.91 |
| `python pting/day01.py input-pting` | 53.1 ± 5.8 | 44.0 | 82.3 | 19.64 ± 8.92 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
