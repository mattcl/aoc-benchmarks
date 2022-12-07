# Day 6 benchmarks

[link to problem](http://adventofcode.com/2022/day/6)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 6)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.3 ± 6.3 | 12.8 | 53.4 | 10.91 ± 6.60 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 27.1 ± 6.7 | 13.0 | 52.4 | 11.27 ± 6.84 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 30.9 ± 7.8 | 23.7 | 51.9 | 12.82 ± 7.82 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 27.8 ± 9.1 | 13.4 | 71.8 | 11.55 ± 7.45 |
| `aspidites-solver/aoc -i input-pting -d 6` | 29.4 ± 7.0 | 23.3 | 50.7 | 12.19 ± 7.36 |
| `kcen/2022/06/solve input-aspidites` | 208.0 ± 57.0 | 150.8 | 314.9 | 86.35 ± 53.48 |
| `kcen/2022/06/solve input-kcen` | 169.5 ± 34.7 | 140.5 | 287.6 | 70.38 ± 41.66 |
| `kcen/2022/06/solve input-lanjian` | 186.2 ± 34.1 | 150.6 | 301.7 | 77.28 ± 45.19 |
| `kcen/2022/06/solve input-mattcl` | 193.8 ± 53.7 | 140.3 | 345.7 | 80.45 ± 49.94 |
| `kcen/2022/06/solve input-pting` | 189.5 ± 60.7 | 143.5 | 390.1 | 78.65 ± 50.43 |
| `lanjian/day_06 input-aspidites` | 3.1 ± 1.5 | 0.7 | 13.0 | 1.29 ± 0.94 |
| `lanjian/day_06 input-kcen` | 3.2 ± 2.1 | 0.8 | 21.1 | 1.35 ± 1.16 |
| `lanjian/day_06 input-lanjian` | 3.4 ± 2.0 | 0.5 | 15.7 | 1.40 ± 1.14 |
| `lanjian/day_06 input-mattcl` | 2.4 ± 1.3 | 0.7 | 9.1 | 1.00 |
| `lanjian/day_06 input-pting` | 2.5 ± 1.8 | 0.6 | 11.7 | 1.05 ± 0.93 |
| `mattcl-solver/aoc run 6 input-aspidites` | 4.1 ± 2.0 | 0.9 | 20.1 | 1.71 ± 1.27 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.8 ± 1.8 | 0.9 | 17.1 | 1.57 ± 1.15 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.8 ± 1.9 | 0.8 | 29.6 | 1.14 ± 1.02 |
| `mattcl-solver/aoc run 6 input-mattcl` | 4.2 ± 2.0 | 0.6 | 21.5 | 1.76 ± 1.29 |
| `mattcl-solver/aoc run 6 input-pting` | 3.2 ± 2.2 | 0.7 | 49.7 | 1.35 ± 1.19 |
| `python pting/day06.py input-aspidites` | 57.5 ± 29.0 | 38.7 | 193.8 | 23.85 ± 17.91 |
| `python pting/day06.py input-kcen` | 76.0 ± 38.2 | 40.3 | 179.7 | 31.56 ± 23.63 |
| `python pting/day06.py input-lanjian` | 61.7 ± 30.8 | 39.5 | 207.1 | 25.59 ± 19.12 |
| `python pting/day06.py input-mattcl` | 68.9 ± 35.1 | 43.8 | 164.9 | 28.61 ± 21.55 |
| `python pting/day06.py input-pting` | 63.8 ± 25.9 | 45.3 | 151.1 | 26.47 ± 18.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
