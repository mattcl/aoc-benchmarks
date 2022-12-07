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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 28.8 ± 9.2 | 12.0 | 59.6 | 20.54 ± 23.97 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.8 ± 6.5 | 12.0 | 47.0 | 18.41 ± 21.18 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 28.2 ± 7.2 | 22.1 | 48.7 | 20.13 ± 23.17 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 21.8 ± 8.5 | 12.0 | 40.7 | 15.54 ± 18.49 |
| `aspidites-solver/aoc -i input-pting -d 6` | 27.9 ± 7.0 | 22.1 | 57.9 | 19.93 ± 22.92 |
| `kcen/2022/06/solve input-aspidites` | 180.9 ± 37.5 | 141.9 | 279.0 | 129.10 ± 147.40 |
| `kcen/2022/06/solve input-kcen` | 171.3 ± 24.7 | 147.2 | 251.1 | 122.25 ± 138.38 |
| `kcen/2022/06/solve input-lanjian` | 174.6 ± 37.0 | 147.6 | 264.6 | 124.63 ± 142.39 |
| `kcen/2022/06/solve input-mattcl` | 180.9 ± 34.5 | 147.5 | 299.5 | 129.10 ± 147.03 |
| `kcen/2022/06/solve input-pting` | 165.3 ± 29.2 | 139.1 | 250.5 | 118.00 ± 134.11 |
| `lanjian/day_06 input-aspidites` | 1.8 ± 1.7 | 0.0 | 14.4 | 1.27 ± 1.87 |
| `lanjian/day_06 input-kcen` | 3.9 ± 6.1 | 0.0 | 68.8 | 2.82 ± 5.40 |
| `lanjian/day_06 input-lanjian` | 1.4 ± 1.6 | 0.0 | 16.2 | 1.00 |
| `lanjian/day_06 input-mattcl` | 5.3 ± 7.7 | 0.0 | 77.8 | 3.76 ± 6.95 |
| `lanjian/day_06 input-pting` | 2.0 ± 1.5 | 0.0 | 7.1 | 1.45 ± 1.93 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.2 ± 2.0 | 0.0 | 21.3 | 1.59 ± 2.31 |
| `mattcl-solver/aoc run 6 input-kcen` | 4.2 ± 4.9 | 0.3 | 52.1 | 2.97 ± 4.80 |
| `mattcl-solver/aoc run 6 input-lanjian` | 1.9 ± 1.7 | 0.0 | 11.3 | 1.33 ± 1.90 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.1 ± 2.2 | 0.0 | 13.6 | 1.53 ± 2.35 |
| `mattcl-solver/aoc run 6 input-pting` | 2.0 ± 1.6 | 0.0 | 12.3 | 1.40 ± 1.93 |
| `python pting/day06.py input-aspidites` | 53.1 ± 20.4 | 36.8 | 154.6 | 37.86 ± 44.92 |
| `python pting/day06.py input-kcen` | 67.4 ± 28.3 | 38.8 | 165.7 | 48.09 ± 57.65 |
| `python pting/day06.py input-lanjian` | 61.2 ± 27.0 | 40.8 | 157.0 | 43.66 ± 52.68 |
| `python pting/day06.py input-mattcl` | 52.1 ± 18.5 | 37.5 | 142.4 | 37.18 ± 43.79 |
| `python pting/day06.py input-pting` | 59.3 ± 24.2 | 38.8 | 171.5 | 42.29 ± 50.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
