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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 16.3 ± 4.0 | 12.2 | 37.1 | 5.50 ± 3.54 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.3 ± 3.4 | 11.9 | 32.7 | 5.16 ± 3.29 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 20.2 ± 31.7 | 12.1 | 364.8 | 6.81 ± 11.42 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.5 ± 1.4 | 11.7 | 18.8 | 4.56 ± 2.76 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.6 ± 2.8 | 12.8 | 32.1 | 5.27 ± 3.29 |
| `kcen/2022/01/solve input-aspidites` | 135.8 ± 20.7 | 110.1 | 214.6 | 45.79 ± 28.20 |
| `kcen/2022/01/solve input-kcen` | 179.7 ± 35.1 | 141.9 | 258.5 | 60.58 ± 38.03 |
| `kcen/2022/01/solve input-lanjian` | 166.8 ± 45.1 | 124.3 | 303.7 | 56.20 ± 36.83 |
| `kcen/2022/01/solve input-mattcl` | 132.1 ± 26.4 | 109.2 | 227.0 | 44.51 ± 28.00 |
| `kcen/2022/01/solve input-pting` | 170.0 ± 33.4 | 133.6 | 259.7 | 57.30 ± 36.00 |
| `lanjian/day_01 input-aspidites` | 3.4 ± 2.3 | 1.0 | 17.5 | 1.15 ± 1.02 |
| `lanjian/day_01 input-kcen` | 3.0 ± 1.9 | 0.8 | 14.1 | 1.01 ± 0.87 |
| `lanjian/day_01 input-lanjian` | 3.9 ± 3.8 | 0.7 | 60.4 | 1.30 ± 1.49 |
| `lanjian/day_01 input-mattcl` | 3.3 ± 1.9 | 0.9 | 12.9 | 1.10 ± 0.91 |
| `lanjian/day_01 input-pting` | 3.7 ± 1.7 | 1.1 | 13.4 | 1.25 ± 0.94 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.4 ± 1.7 | 0.9 | 12.0 | 1.15 ± 0.89 |
| `mattcl-solver/aoc run 1 input-kcen` | 4.5 ± 4.2 | 0.5 | 37.9 | 1.53 ± 1.70 |
| `mattcl-solver/aoc run 1 input-lanjian` | 3.0 ± 1.8 | 0.6 | 12.3 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 4.1 ± 3.8 | 0.7 | 43.1 | 1.38 ± 1.54 |
| `mattcl-solver/aoc run 1 input-pting` | 3.9 ± 2.2 | 0.8 | 12.7 | 1.32 ± 1.08 |
| `python pting/day01.py input-aspidites` | 46.6 ± 19.9 | 32.3 | 121.8 | 15.69 ± 11.52 |
| `python pting/day01.py input-kcen` | 68.8 ± 32.8 | 42.9 | 197.7 | 23.19 ± 17.70 |
| `python pting/day01.py input-lanjian` | 52.3 ± 27.0 | 34.4 | 168.8 | 17.63 ± 13.90 |
| `python pting/day01.py input-mattcl` | 47.0 ± 16.1 | 32.3 | 136.4 | 15.85 ± 10.91 |
| `python pting/day01.py input-pting` | 58.8 ± 28.2 | 36.6 | 176.0 | 19.81 ± 15.16 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
