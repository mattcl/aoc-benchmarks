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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.0 ± 0.6 | 11.3 | 17.5 | 9.44 ± 2.12 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.3 ± 0.6 | 11.4 | 15.7 | 9.61 ± 2.16 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.9 ± 1.3 | 11.6 | 29.2 | 10.16 ± 2.43 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.6 ± 1.1 | 11.5 | 24.8 | 9.86 ± 2.32 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.2 ± 0.8 | 11.4 | 18.7 | 9.54 ± 2.17 |
| `kcen/2022/01/solve input-aspidites` | 97.9 ± 5.8 | 91.1 | 119.9 | 76.82 ± 17.40 |
| `kcen/2022/01/solve input-kcen` | 98.2 ± 9.3 | 85.7 | 126.7 | 77.06 ± 18.36 |
| `kcen/2022/01/solve input-lanjian` | 117.3 ± 16.8 | 96.0 | 164.2 | 92.03 ± 24.05 |
| `kcen/2022/01/solve input-mattcl` | 106.5 ± 8.2 | 91.8 | 125.5 | 83.58 ± 19.36 |
| `kcen/2022/01/solve input-pting` | 109.3 ± 9.1 | 95.6 | 135.3 | 85.77 ± 20.06 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.5 | 0.8 | 12.6 | 1.34 ± 0.52 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.5 | 0.9 | 4.7 | 1.25 ± 0.45 |
| `lanjian/day_01 input-lanjian` | 1.8 ± 0.5 | 1.0 | 5.0 | 1.42 ± 0.50 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.4 | 0.9 | 4.3 | 1.38 ± 0.45 |
| `lanjian/day_01 input-pting` | 1.6 ± 0.6 | 1.0 | 13.8 | 1.28 ± 0.57 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.3 | 0.7 | 3.2 | 1.02 ± 0.35 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.3 | 0.7 | 3.5 | 1.00 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.8 ± 1.2 | 0.7 | 13.5 | 1.37 ± 0.99 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 0.6 | 0.8 | 9.3 | 1.34 ± 0.58 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.7 | 0.6 | 13.1 | 1.09 ± 0.63 |
| `python pting/day01.py input-aspidites` | 31.6 ± 3.1 | 28.1 | 45.2 | 24.81 ± 5.95 |
| `python pting/day01.py input-kcen` | 32.4 ± 3.9 | 27.5 | 51.8 | 25.41 ± 6.34 |
| `python pting/day01.py input-lanjian` | 35.1 ± 4.7 | 29.2 | 57.9 | 27.57 ± 7.05 |
| `python pting/day01.py input-mattcl` | 34.2 ± 2.6 | 29.6 | 50.2 | 26.80 ± 6.20 |
| `python pting/day01.py input-pting` | 34.7 ± 9.2 | 27.4 | 96.4 | 27.24 ± 9.35 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
