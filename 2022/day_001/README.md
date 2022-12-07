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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.5 ± 3.9 | 11.5 | 40.6 | 6.21 ± 4.40 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.9 ± 3.5 | 12.0 | 34.8 | 6.41 ± 4.46 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 15.1 ± 3.2 | 11.9 | 31.0 | 6.46 ± 4.45 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.6 ± 3.0 | 11.8 | 26.4 | 6.27 ± 4.31 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.3 ± 3.0 | 11.5 | 36.4 | 6.14 ± 4.23 |
| `kcen/2022/01/solve input-aspidites` | 161.2 ± 58.7 | 122.9 | 349.2 | 69.10 ± 51.83 |
| `kcen/2022/01/solve input-kcen` | 172.0 ± 44.7 | 137.1 | 299.3 | 73.72 ± 51.99 |
| `kcen/2022/01/solve input-lanjian` | 157.1 ± 13.7 | 137.4 | 185.5 | 67.33 ± 44.53 |
| `kcen/2022/01/solve input-mattcl` | 153.9 ± 12.9 | 122.2 | 172.5 | 65.97 ± 43.60 |
| `kcen/2022/01/solve input-pting` | 151.8 ± 16.2 | 131.5 | 198.7 | 65.09 ± 43.23 |
| `lanjian/day_01 input-aspidites` | 3.1 ± 1.9 | 0.5 | 17.4 | 1.31 ± 1.18 |
| `lanjian/day_01 input-kcen` | 3.2 ± 1.7 | 0.6 | 12.8 | 1.39 ± 1.18 |
| `lanjian/day_01 input-lanjian` | 3.3 ± 1.9 | 0.8 | 16.2 | 1.40 ± 1.23 |
| `lanjian/day_01 input-mattcl` | 4.3 ± 2.3 | 1.1 | 18.5 | 1.82 ± 1.56 |
| `lanjian/day_01 input-pting` | 2.4 ± 1.7 | 0.6 | 13.0 | 1.05 ± 1.00 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.6 ± 1.9 | 0.2 | 16.7 | 1.13 ± 1.09 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.6 ± 2.1 | 0.5 | 19.6 | 1.11 ± 1.14 |
| `mattcl-solver/aoc run 1 input-lanjian` | 3.1 ± 1.7 | 0.4 | 10.7 | 1.32 ± 1.13 |
| `mattcl-solver/aoc run 1 input-mattcl` | 3.8 ± 2.4 | 0.8 | 18.4 | 1.64 ± 1.48 |
| `mattcl-solver/aoc run 1 input-pting` | 2.3 ± 1.5 | 0.1 | 14.0 | 1.00 |
| `python pting/day01.py input-aspidites` | 49.5 ± 17.5 | 35.5 | 125.7 | 21.20 ± 15.80 |
| `python pting/day01.py input-kcen` | 74.1 ± 52.2 | 36.3 | 237.0 | 31.78 ± 30.57 |
| `python pting/day01.py input-lanjian` | 54.3 ± 23.1 | 38.1 | 169.0 | 23.27 ± 18.19 |
| `python pting/day01.py input-mattcl` | 85.3 ± 69.6 | 41.6 | 341.8 | 36.55 ± 38.26 |
| `python pting/day01.py input-pting` | 52.6 ± 24.9 | 33.5 | 148.2 | 22.55 ± 18.23 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
