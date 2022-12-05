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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.3 ± 0.5 | 11.4 | 14.2 | 10.52 ± 7.25 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.6 ± 0.8 | 11.6 | 20.1 | 10.80 ± 7.47 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.3 ± 1.1 | 11.4 | 22.4 | 10.57 ± 7.34 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.4 ± 0.5 | 11.6 | 13.9 | 10.61 ± 7.31 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.2 ± 0.7 | 11.3 | 17.3 | 10.42 ± 7.20 |
| `kcen/2022/01/solve input-aspidites` | 105.8 ± 7.8 | 93.3 | 122.8 | 90.71 ± 62.80 |
| `kcen/2022/01/solve input-kcen` | 116.3 ± 10.4 | 96.2 | 135.1 | 99.71 ± 69.21 |
| `kcen/2022/01/solve input-lanjian` | 105.8 ± 6.0 | 95.0 | 119.3 | 90.65 ± 62.61 |
| `kcen/2022/01/solve input-mattcl` | 101.8 ± 8.5 | 92.2 | 129.5 | 87.22 ± 60.48 |
| `kcen/2022/01/solve input-pting` | 101.8 ± 9.7 | 89.9 | 127.1 | 87.27 ± 60.65 |
| `lanjian/day_01 input-aspidites` | 1.5 ± 0.4 | 0.9 | 3.9 | 1.28 ± 0.94 |
| `lanjian/day_01 input-kcen` | 2.0 ± 0.8 | 1.0 | 8.4 | 1.69 ± 1.35 |
| `lanjian/day_01 input-lanjian` | 2.0 ± 0.9 | 0.9 | 9.0 | 1.73 ± 1.42 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.4 | 1.0 | 4.5 | 1.56 ± 1.14 |
| `lanjian/day_01 input-pting` | 1.5 ± 0.4 | 0.9 | 4.4 | 1.29 ± 0.95 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.3 | 0.8 | 3.1 | 1.13 ± 0.83 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.5 ± 0.7 | 0.7 | 8.6 | 1.31 ± 1.07 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.4 ± 0.6 | 0.8 | 7.6 | 1.16 ± 0.95 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.4 | 0.7 | 5.7 | 1.12 ± 0.84 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 0.8 | 0.7 | 16.1 | 1.00 |
| `python pting/day01.py input-aspidites` | 33.2 ± 3.9 | 28.3 | 53.3 | 28.46 ± 19.87 |
| `python pting/day01.py input-kcen` | 37.1 ± 4.4 | 29.9 | 52.5 | 31.79 ± 22.20 |
| `python pting/day01.py input-lanjian` | 37.4 ± 5.7 | 29.8 | 63.9 | 32.03 ± 22.58 |
| `python pting/day01.py input-mattcl` | 35.1 ± 4.1 | 29.6 | 47.3 | 30.10 ± 21.01 |
| `python pting/day01.py input-pting` | 32.5 ± 3.0 | 28.0 | 45.0 | 27.87 ± 19.36 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
