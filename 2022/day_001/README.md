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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.2 ± 0.5 | 11.6 | 14.1 | 11.01 ± 2.87 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.5 ± 0.5 | 11.7 | 14.2 | 11.25 ± 2.93 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 13.3 ± 0.6 | 12.3 | 15.6 | 12.00 ± 3.13 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.1 ± 0.5 | 11.6 | 14.2 | 10.91 ± 2.84 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.8 ± 1.8 | 11.5 | 24.6 | 11.54 ± 3.39 |
| `kcen/2022/01/solve input-aspidites` | 101.9 ± 5.6 | 93.4 | 116.5 | 91.73 ± 24.14 |
| `kcen/2022/01/solve input-kcen` | 106.9 ± 7.7 | 94.9 | 123.0 | 96.18 ± 25.71 |
| `kcen/2022/01/solve input-lanjian` | 112.5 ± 11.4 | 96.4 | 139.8 | 101.19 ± 27.98 |
| `kcen/2022/01/solve input-mattcl` | 111.0 ± 28.3 | 87.3 | 216.0 | 99.89 ± 36.18 |
| `kcen/2022/01/solve input-pting` | 103.5 ± 7.0 | 89.6 | 118.9 | 93.15 ± 24.78 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.3 | 1.0 | 3.5 | 1.27 ± 0.42 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.4 | 0.9 | 8.4 | 1.47 ± 0.55 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.7 | 0.9 | 14.3 | 1.56 ± 0.74 |
| `lanjian/day_01 input-mattcl` | 1.7 ± 0.5 | 1.0 | 6.4 | 1.56 ± 0.59 |
| `lanjian/day_01 input-pting` | 1.5 ± 0.8 | 0.9 | 9.3 | 1.36 ± 0.77 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.2 ± 0.4 | 0.7 | 3.7 | 1.10 ± 0.43 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.4 | 0.8 | 3.5 | 1.16 ± 0.45 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.1 ± 0.3 | 0.7 | 3.5 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 0.5 | 0.8 | 4.0 | 1.56 ± 0.58 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 0.6 | 0.8 | 8.7 | 1.09 ± 0.58 |
| `python pting/day01.py input-aspidites` | 33.4 ± 4.1 | 28.4 | 46.2 | 30.06 ± 8.56 |
| `python pting/day01.py input-kcen` | 32.8 ± 4.0 | 28.2 | 44.7 | 29.53 ± 8.40 |
| `python pting/day01.py input-lanjian` | 32.3 ± 2.8 | 28.3 | 41.7 | 29.03 ± 7.89 |
| `python pting/day01.py input-mattcl` | 35.5 ± 3.8 | 28.4 | 46.4 | 31.91 ± 8.89 |
| `python pting/day01.py input-pting` | 37.1 ± 7.4 | 29.8 | 85.0 | 33.39 ± 10.89 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
