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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.0 ± 2.3 | 23.3 | 38.8 | 10.81 ± 5.02 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 26.1 ± 2.2 | 15.7 | 39.3 | 10.83 ± 5.02 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 27.5 ± 7.1 | 23.8 | 69.6 | 11.40 ± 5.97 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 24.5 ± 4.5 | 13.5 | 38.6 | 10.17 ± 5.00 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.5 ± 2.8 | 23.7 | 37.9 | 11.02 ± 5.16 |
| `kcen/2022/06/solve input-aspidites` | 179.8 ± 31.0 | 149.3 | 241.9 | 74.68 ± 36.39 |
| `kcen/2022/06/solve input-kcen` | 180.3 ± 19.4 | 156.9 | 219.1 | 74.89 ± 35.08 |
| `kcen/2022/06/solve input-lanjian` | 186.8 ± 27.9 | 156.8 | 250.1 | 77.56 ± 37.21 |
| `kcen/2022/06/solve input-mattcl` | 185.7 ± 19.0 | 165.4 | 219.1 | 77.13 ± 36.04 |
| `kcen/2022/06/solve input-pting` | 257.2 ± 148.8 | 162.5 | 560.3 | 106.80 ± 78.67 |
| `lanjian/day_06 input-aspidites` | 2.8 ± 1.9 | 0.6 | 15.9 | 1.16 ± 0.94 |
| `lanjian/day_06 input-kcen` | 2.4 ± 1.1 | 0.6 | 7.2 | 1.00 |
| `lanjian/day_06 input-lanjian` | 2.7 ± 1.4 | 0.5 | 13.9 | 1.12 ± 0.76 |
| `lanjian/day_06 input-mattcl` | 2.5 ± 1.2 | 0.4 | 11.4 | 1.02 ± 0.68 |
| `lanjian/day_06 input-pting` | 2.4 ± 1.1 | 0.5 | 7.3 | 1.01 ± 0.65 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.6 ± 1.3 | 0.8 | 10.7 | 1.07 ± 0.71 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.9 ± 1.2 | 0.9 | 9.5 | 1.21 ± 0.76 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.8 ± 1.4 | 0.6 | 10.8 | 1.15 ± 0.77 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.6 ± 1.2 | 0.6 | 7.3 | 1.08 ± 0.70 |
| `mattcl-solver/aoc run 6 input-pting` | 3.3 ± 2.0 | 0.8 | 29.7 | 1.38 ± 1.05 |
| `python pting/day06.py input-aspidites` | 62.3 ± 11.6 | 42.7 | 95.3 | 25.85 ± 12.73 |
| `python pting/day06.py input-kcen` | 63.7 ± 12.9 | 45.4 | 89.9 | 26.47 ± 13.20 |
| `python pting/day06.py input-lanjian` | 53.0 ± 7.2 | 43.4 | 74.0 | 22.02 ± 10.47 |
| `python pting/day06.py input-mattcl` | 59.7 ± 13.5 | 43.4 | 94.2 | 24.79 ± 12.62 |
| `python pting/day06.py input-pting` | 54.2 ± 6.8 | 43.8 | 80.8 | 22.49 ± 10.64 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
