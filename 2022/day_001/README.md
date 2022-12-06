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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.7 ± 3.0 | 12.5 | 38.0 | 6.23 ± 3.03 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.8 ± 2.9 | 12.4 | 36.7 | 6.25 ± 3.03 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.4 ± 3.2 | 12.3 | 32.5 | 6.11 ± 3.03 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.8 ± 2.3 | 12.3 | 29.4 | 6.27 ± 2.95 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.5 ± 2.3 | 12.4 | 28.0 | 6.15 ± 2.89 |
| `kcen/2022/01/solve input-aspidites` | 179.6 ± 17.1 | 161.2 | 213.7 | 75.96 ± 34.40 |
| `kcen/2022/01/solve input-kcen` | 185.3 ± 17.5 | 155.7 | 212.3 | 78.36 ± 35.48 |
| `kcen/2022/01/solve input-lanjian` | 257.9 ± 65.2 | 180.4 | 359.8 | 109.10 ± 55.64 |
| `kcen/2022/01/solve input-mattcl` | 179.5 ± 27.9 | 149.9 | 241.1 | 75.91 ± 35.62 |
| `kcen/2022/01/solve input-pting` | 191.1 ± 16.6 | 167.9 | 219.6 | 80.81 ± 36.47 |
| `lanjian/day_01 input-aspidites` | 2.4 ± 1.0 | 0.9 | 10.4 | 1.00 |
| `lanjian/day_01 input-kcen` | 2.9 ± 1.4 | 0.8 | 11.9 | 1.24 ± 0.81 |
| `lanjian/day_01 input-lanjian` | 3.1 ± 1.5 | 0.8 | 23.6 | 1.33 ± 0.85 |
| `lanjian/day_01 input-mattcl` | 3.2 ± 1.2 | 1.2 | 16.6 | 1.36 ± 0.80 |
| `lanjian/day_01 input-pting` | 2.9 ± 1.2 | 0.8 | 11.3 | 1.24 ± 0.74 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.2 ± 1.6 | 0.8 | 16.5 | 1.37 ± 0.90 |
| `mattcl-solver/aoc run 1 input-kcen` | 5.0 ± 4.8 | 0.8 | 36.8 | 2.10 ± 2.21 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.9 ± 1.1 | 0.7 | 9.8 | 1.24 ± 0.73 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.9 ± 1.2 | 0.8 | 10.7 | 1.25 ± 0.75 |
| `mattcl-solver/aoc run 1 input-pting` | 2.9 ± 1.3 | 0.8 | 11.1 | 1.25 ± 0.77 |
| `python pting/day01.py input-aspidites` | 60.0 ± 11.4 | 40.9 | 97.6 | 25.37 ± 12.23 |
| `python pting/day01.py input-kcen` | 67.4 ± 10.0 | 47.1 | 88.0 | 28.51 ± 13.31 |
| `python pting/day01.py input-lanjian` | 70.6 ± 26.7 | 44.2 | 216.2 | 29.86 ± 17.39 |
| `python pting/day01.py input-mattcl` | 56.8 ± 9.5 | 41.2 | 87.1 | 24.04 ± 11.39 |
| `python pting/day01.py input-pting` | 58.9 ± 7.1 | 46.0 | 81.2 | 24.91 ± 11.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
