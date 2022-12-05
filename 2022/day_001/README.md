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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.8 ± 1.3 | 11.7 | 25.4 | 11.28 ± 2.99 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.5 ± 1.0 | 11.5 | 23.0 | 11.00 ± 2.81 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.8 ± 1.2 | 11.7 | 22.8 | 11.29 ± 2.95 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.1 ± 0.7 | 11.4 | 16.8 | 10.66 ± 2.66 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.4 ± 1.1 | 11.7 | 22.8 | 10.98 ± 2.85 |
| `kcen/2022/01/solve input-aspidites` | 105.7 ± 6.1 | 96.1 | 119.1 | 93.27 ± 23.34 |
| `kcen/2022/01/solve input-kcen` | 112.3 ± 9.1 | 97.6 | 139.0 | 99.08 ± 25.42 |
| `kcen/2022/01/solve input-lanjian` | 111.2 ± 5.6 | 101.6 | 125.2 | 98.06 ± 24.38 |
| `kcen/2022/01/solve input-mattcl` | 108.3 ± 15.1 | 87.5 | 156.3 | 95.56 ± 26.83 |
| `kcen/2022/01/solve input-pting` | 111.4 ± 11.9 | 95.7 | 146.4 | 98.25 ± 26.11 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 0.6 | 0.9 | 7.7 | 1.59 ± 0.64 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.4 | 0.9 | 4.0 | 1.42 ± 0.48 |
| `lanjian/day_01 input-lanjian` | 1.6 ± 0.6 | 1.0 | 8.9 | 1.41 ± 0.64 |
| `lanjian/day_01 input-mattcl` | 1.4 ± 0.5 | 0.9 | 7.7 | 1.21 ± 0.50 |
| `lanjian/day_01 input-pting` | 1.8 ± 0.7 | 0.9 | 7.0 | 1.55 ± 0.69 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.6 ± 1.0 | 0.8 | 17.1 | 1.38 ± 0.95 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.4 | 0.8 | 4.0 | 1.18 ± 0.45 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.1 ± 0.3 | 0.8 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.5 | 0.8 | 8.5 | 1.11 ± 0.51 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.7 | 0.7 | 9.6 | 1.24 ± 0.69 |
| `python pting/day01.py input-aspidites` | 34.2 ± 3.6 | 28.1 | 46.9 | 30.16 ± 7.99 |
| `python pting/day01.py input-kcen` | 34.7 ± 5.3 | 28.6 | 58.5 | 30.60 ± 8.81 |
| `python pting/day01.py input-lanjian` | 31.3 ± 3.9 | 27.5 | 47.2 | 27.56 ± 7.55 |
| `python pting/day01.py input-mattcl` | 34.3 ± 2.8 | 28.9 | 42.6 | 30.29 ± 7.77 |
| `python pting/day01.py input-pting` | 34.7 ± 4.2 | 29.0 | 49.5 | 30.61 ± 8.31 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
