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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.3 ± 1.4 | 11.5 | 27.9 | 10.36 ± 6.21 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.7 ± 0.7 | 11.7 | 15.9 | 9.90 ± 5.86 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 16.0 ± 3.1 | 12.9 | 28.9 | 12.45 ± 7.74 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 21.3 ± 14.8 | 13.0 | 105.8 | 16.56 ± 15.12 |
| `aspidites-solver/aoc -i input-pting -d 1` | 13.7 ± 1.0 | 12.0 | 18.5 | 10.65 ± 6.33 |
| `kcen/2022/01/solve input-aspidites` | 136.9 ± 14.6 | 119.6 | 180.1 | 106.54 ± 63.86 |
| `kcen/2022/01/solve input-kcen` | 144.4 ± 17.1 | 123.9 | 179.0 | 112.40 ± 67.62 |
| `kcen/2022/01/solve input-lanjian` | 187.3 ± 32.2 | 152.9 | 281.1 | 145.80 ± 89.57 |
| `kcen/2022/01/solve input-mattcl` | 192.8 ± 32.7 | 138.2 | 257.5 | 150.08 ± 92.11 |
| `kcen/2022/01/solve input-pting` | 143.7 ± 9.6 | 127.5 | 161.2 | 111.88 ± 66.41 |
| `lanjian/day_01 input-aspidites` | 2.5 ± 1.7 | 0.4 | 32.4 | 1.93 ± 1.74 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.8 | 0.4 | 5.5 | 1.18 ± 0.94 |
| `lanjian/day_01 input-lanjian` | 3.7 ± 1.4 | 0.8 | 14.3 | 2.89 ± 2.04 |
| `lanjian/day_01 input-mattcl` | 3.1 ± 2.1 | 0.6 | 20.7 | 2.38 ± 2.13 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.7 | 0.4 | 5.2 | 1.07 ± 0.86 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.9 ± 3.6 | 0.5 | 33.4 | 3.00 ± 3.29 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 1.0 | 0.2 | 10.6 | 1.12 ± 1.00 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.4 ± 1.3 | 0.5 | 13.5 | 1.84 ± 1.49 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.5 ± 1.8 | 0.4 | 13.0 | 1.96 ± 1.80 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.8 | 0.1 | 5.2 | 1.00 |
| `python pting/day01.py input-aspidites` | 47.1 ± 6.9 | 38.0 | 71.6 | 36.65 ± 22.28 |
| `python pting/day01.py input-kcen` | 44.6 ± 4.7 | 33.5 | 64.6 | 34.72 ± 20.81 |
| `python pting/day01.py input-lanjian` | 64.8 ± 12.5 | 48.1 | 98.7 | 50.47 ± 31.32 |
| `python pting/day01.py input-mattcl` | 51.9 ± 7.7 | 41.3 | 78.0 | 40.40 ± 24.57 |
| `python pting/day01.py input-pting` | 44.4 ± 5.9 | 36.3 | 67.1 | 34.57 ± 20.90 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
