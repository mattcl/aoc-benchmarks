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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.6 ± 1.3 | 11.6 | 22.0 | 9.45 ± 3.29 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.2 ± 0.4 | 11.5 | 13.7 | 9.15 ± 3.07 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.6 ± 0.8 | 11.5 | 16.6 | 9.47 ± 3.21 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.6 ± 0.6 | 11.5 | 14.7 | 9.41 ± 3.17 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.8 ± 0.7 | 11.9 | 18.0 | 9.58 ± 3.23 |
| `kcen/2022/01/solve input-aspidites` | 111.1 ± 7.1 | 101.2 | 128.3 | 83.22 ± 28.24 |
| `kcen/2022/01/solve input-kcen` | 107.5 ± 6.0 | 95.0 | 117.0 | 80.51 ± 27.21 |
| `kcen/2022/01/solve input-lanjian` | 110.8 ± 19.9 | 88.5 | 194.1 | 83.03 ± 31.42 |
| `kcen/2022/01/solve input-mattcl` | 105.7 ± 9.7 | 92.9 | 133.6 | 79.16 ± 27.36 |
| `kcen/2022/01/solve input-pting` | 111.3 ± 7.1 | 98.3 | 128.5 | 83.37 ± 28.28 |
| `lanjian/day_01 input-aspidites` | 2.0 ± 0.9 | 1.1 | 14.4 | 1.49 ± 0.84 |
| `lanjian/day_01 input-kcen` | 1.9 ± 0.5 | 1.1 | 4.4 | 1.42 ± 0.58 |
| `lanjian/day_01 input-lanjian` | 1.4 ± 0.4 | 1.0 | 7.6 | 1.04 ± 0.47 |
| `lanjian/day_01 input-mattcl` | 1.9 ± 0.8 | 1.0 | 10.4 | 1.42 ± 0.75 |
| `lanjian/day_01 input-pting` | 2.0 ± 0.5 | 1.1 | 8.8 | 1.49 ± 0.61 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.4 ± 0.4 | 0.8 | 3.4 | 1.08 ± 0.48 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.6 ± 0.4 | 0.8 | 4.0 | 1.23 ± 0.51 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.4 ± 1.7 | 0.7 | 44.5 | 1.08 ± 1.29 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.4 | 0.8 | 4.4 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.5 ± 0.6 | 0.9 | 7.0 | 1.16 ± 0.59 |
| `python pting/day01.py input-aspidites` | 36.0 ± 7.1 | 29.6 | 88.8 | 26.97 ± 10.43 |
| `python pting/day01.py input-kcen` | 33.5 ± 3.2 | 28.1 | 48.6 | 25.12 ± 8.70 |
| `python pting/day01.py input-lanjian` | 30.2 ± 3.1 | 26.2 | 46.6 | 22.66 ± 7.90 |
| `python pting/day01.py input-mattcl` | 35.8 ± 5.0 | 29.2 | 49.4 | 26.83 ± 9.68 |
| `python pting/day01.py input-pting` | 34.0 ± 2.9 | 28.8 | 46.3 | 25.51 ± 8.78 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
