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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.7 ± 3.1 | 11.3 | 34.9 | 12.82 ± 17.21 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 15.3 ± 3.2 | 11.9 | 27.7 | 13.32 ± 17.87 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 13.7 ± 3.3 | 10.8 | 28.7 | 11.89 ± 16.02 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.7 ± 2.2 | 11.3 | 27.6 | 11.92 ± 15.91 |
| `aspidites-solver/aoc -i input-pting -d 1` | 15.0 ± 3.3 | 11.4 | 34.5 | 13.07 ± 17.55 |
| `kcen/2022/01/solve input-aspidites` | 220.0 ± 50.7 | 162.2 | 320.3 | 191.42 ± 257.59 |
| `kcen/2022/01/solve input-kcen` | 172.5 ± 24.1 | 144.2 | 227.2 | 150.08 ± 200.07 |
| `kcen/2022/01/solve input-lanjian` | 170.5 ± 27.6 | 136.9 | 245.6 | 148.37 ± 198.16 |
| `kcen/2022/01/solve input-mattcl` | 173.2 ± 33.4 | 135.7 | 269.2 | 150.67 ± 201.85 |
| `kcen/2022/01/solve input-pting` | 176.6 ± 26.0 | 152.4 | 258.6 | 153.61 ± 204.90 |
| `lanjian/day_01 input-aspidites` | 2.3 ± 1.6 | 0.0 | 12.9 | 2.00 ± 2.98 |
| `lanjian/day_01 input-kcen` | 2.9 ± 1.7 | 0.3 | 16.6 | 2.49 ± 3.63 |
| `lanjian/day_01 input-lanjian` | 3.8 ± 3.4 | 0.0 | 21.4 | 3.34 ± 5.32 |
| `lanjian/day_01 input-mattcl` | 1.5 ± 1.4 | 0.0 | 6.5 | 1.31 ± 2.11 |
| `lanjian/day_01 input-pting` | 1.8 ± 1.5 | 0.0 | 15.4 | 1.60 ± 2.49 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 1.1 | 0.0 | 9.5 | 1.29 ± 1.97 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.6 ± 1.8 | 0.0 | 14.0 | 2.25 ± 3.36 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.9 ± 1.4 | 0.0 | 8.3 | 1.68 ± 2.56 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.1 ± 1.5 | 0.0 | 16.9 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.9 ± 1.5 | 0.0 | 12.0 | 1.63 ± 2.50 |
| `python pting/day01.py input-aspidites` | 57.1 ± 21.2 | 40.5 | 144.5 | 49.72 ± 68.45 |
| `python pting/day01.py input-kcen` | 58.9 ± 15.6 | 43.2 | 121.2 | 51.28 ± 69.33 |
| `python pting/day01.py input-lanjian` | 59.0 ± 23.7 | 41.7 | 184.7 | 51.34 ± 71.10 |
| `python pting/day01.py input-mattcl` | 53.5 ± 16.5 | 38.3 | 151.4 | 46.54 ± 63.35 |
| `python pting/day01.py input-pting` | 63.6 ± 24.7 | 41.2 | 164.8 | 55.37 ± 76.50 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
