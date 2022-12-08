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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.8 ± 3.3 | 13.4 | 36.7 | 11.52 ± 6.52 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.1 ± 3.3 | 13.3 | 37.2 | 11.22 ± 6.35 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 28.6 ± 5.8 | 23.8 | 58.6 | 12.74 ± 7.48 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.5 ± 6.9 | 13.2 | 63.9 | 10.47 ± 6.54 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.7 ± 2.8 | 23.3 | 43.0 | 11.48 ± 6.44 |
| `kcen/2022/06/solve input-aspidites` | 183.7 ± 14.6 | 158.1 | 214.6 | 81.96 ± 45.59 |
| `kcen/2022/06/solve input-kcen` | 173.3 ± 14.8 | 150.3 | 200.6 | 77.30 ± 43.07 |
| `kcen/2022/06/solve input-lanjian` | 184.2 ± 22.0 | 143.0 | 227.1 | 82.17 ± 46.29 |
| `kcen/2022/06/solve input-mattcl` | 191.3 ± 22.2 | 156.8 | 237.5 | 85.33 ± 48.01 |
| `kcen/2022/06/solve input-pting` | 178.4 ± 13.6 | 159.0 | 201.1 | 79.59 ± 44.24 |
| `lanjian/day_06 input-aspidites` | 2.2 ± 1.2 | 0.6 | 12.4 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.4 ± 1.3 | 0.6 | 24.3 | 1.07 ± 0.84 |
| `lanjian/day_06 input-lanjian` | 2.8 ± 1.5 | 0.7 | 12.5 | 1.25 ± 0.97 |
| `lanjian/day_06 input-mattcl` | 2.4 ± 1.0 | 0.6 | 6.7 | 1.07 ± 0.74 |
| `lanjian/day_06 input-pting` | 2.9 ± 1.6 | 0.9 | 23.9 | 1.30 ± 1.01 |
| `mattcl-solver/aoc run 6 input-aspidites` | 3.4 ± 1.6 | 1.0 | 18.0 | 1.51 ± 1.11 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.6 ± 1.0 | 0.9 | 10.1 | 1.17 ± 0.79 |
| `mattcl-solver/aoc run 6 input-lanjian` | 6.9 ± 11.0 | 1.0 | 144.8 | 3.07 ± 5.19 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.8 ± 1.7 | 0.8 | 16.4 | 1.23 ± 1.00 |
| `mattcl-solver/aoc run 6 input-pting` | 3.0 ± 1.1 | 0.9 | 12.4 | 1.33 ± 0.89 |
| `python pting/day06.py input-aspidites` | 56.0 ± 9.0 | 43.3 | 84.3 | 24.96 ± 14.32 |
| `python pting/day06.py input-kcen` | 55.8 ± 8.9 | 43.9 | 82.5 | 24.90 ± 14.27 |
| `python pting/day06.py input-lanjian` | 54.1 ± 7.2 | 42.4 | 81.0 | 24.13 ± 13.67 |
| `python pting/day06.py input-mattcl` | 58.8 ± 8.3 | 46.2 | 81.3 | 26.24 ± 14.92 |
| `python pting/day06.py input-pting` | 55.4 ± 8.5 | 43.6 | 83.8 | 24.71 ± 14.12 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
