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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.7 ± 2.4 | 12.3 | 26.5 | 6.40 ± 3.76 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 16.0 ± 3.9 | 12.8 | 44.1 | 6.98 ± 4.28 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 15.8 ± 3.3 | 12.2 | 28.9 | 6.88 ± 4.13 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 15.1 ± 3.1 | 12.2 | 32.2 | 6.56 ± 3.93 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.0 ± 3.2 | 12.5 | 44.4 | 6.53 ± 3.92 |
| `kcen/2022/01/solve input-aspidites` | 175.3 ± 23.2 | 140.6 | 225.5 | 76.38 ± 44.18 |
| `kcen/2022/01/solve input-kcen` | 280.5 ± 111.5 | 183.9 | 507.0 | 122.19 ± 84.21 |
| `kcen/2022/01/solve input-lanjian` | 179.9 ± 19.5 | 144.5 | 212.3 | 78.39 ± 44.95 |
| `kcen/2022/01/solve input-mattcl` | 164.8 ± 17.1 | 143.5 | 199.0 | 71.81 ± 41.11 |
| `kcen/2022/01/solve input-pting` | 183.5 ± 25.9 | 152.8 | 249.6 | 79.95 ± 46.40 |
| `lanjian/day_01 input-aspidites` | 2.9 ± 1.4 | 0.6 | 10.8 | 1.25 ± 0.93 |
| `lanjian/day_01 input-kcen` | 3.1 ± 1.4 | 0.7 | 18.0 | 1.37 ± 0.98 |
| `lanjian/day_01 input-lanjian` | 2.5 ± 1.1 | 0.8 | 14.0 | 1.10 ± 0.79 |
| `lanjian/day_01 input-mattcl` | 2.8 ± 1.9 | 0.6 | 20.6 | 1.22 ± 1.07 |
| `lanjian/day_01 input-pting` | 3.2 ± 1.4 | 0.9 | 14.4 | 1.39 ± 0.99 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.3 ± 1.3 | 0.5 | 11.6 | 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 3.0 ± 1.2 | 0.8 | 9.8 | 1.33 ± 0.91 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.6 ± 1.4 | 0.3 | 13.0 | 1.13 ± 0.87 |
| `mattcl-solver/aoc run 1 input-mattcl` | 4.3 ± 4.4 | 0.6 | 38.4 | 1.88 ± 2.21 |
| `mattcl-solver/aoc run 1 input-pting` | 3.0 ± 1.1 | 0.5 | 8.7 | 1.32 ± 0.88 |
| `python pting/day01.py input-aspidites` | 56.4 ± 9.6 | 38.6 | 78.8 | 24.58 ± 14.45 |
| `python pting/day01.py input-kcen` | 59.5 ± 7.1 | 49.4 | 78.6 | 25.91 ± 14.91 |
| `python pting/day01.py input-lanjian` | 60.2 ± 12.6 | 40.2 | 97.7 | 26.23 ± 15.75 |
| `python pting/day01.py input-mattcl` | 53.6 ± 11.2 | 38.7 | 90.0 | 23.35 ± 14.03 |
| `python pting/day01.py input-pting` | 59.7 ± 9.6 | 44.3 | 99.0 | 26.00 ± 15.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
