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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 24.7 ± 4.0 | 12.4 | 46.6 | 10.42 ± 7.52 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.3 ± 4.1 | 12.7 | 46.1 | 10.69 ± 7.71 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 27.0 ± 4.2 | 17.1 | 40.8 | 11.36 ± 8.19 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 22.1 ± 6.6 | 12.9 | 46.6 | 9.33 ± 7.13 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.2 ± 4.3 | 23.0 | 53.8 | 11.05 ± 7.97 |
| `kcen/2022/06/solve input-aspidites` | 183.7 ± 26.9 | 142.3 | 220.9 | 77.43 ± 55.59 |
| `kcen/2022/06/solve input-kcen` | 224.7 ± 49.1 | 164.5 | 340.8 | 94.74 ± 69.73 |
| `kcen/2022/06/solve input-lanjian` | 201.7 ± 35.0 | 159.4 | 265.9 | 85.01 ± 61.55 |
| `kcen/2022/06/solve input-mattcl` | 185.2 ± 35.5 | 155.0 | 291.7 | 78.08 ± 56.88 |
| `kcen/2022/06/solve input-pting` | 216.6 ± 29.2 | 170.9 | 273.1 | 91.30 ± 65.34 |
| `lanjian/day_06 input-aspidites` | 2.4 ± 1.7 | 0.5 | 14.7 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.6 ± 1.5 | 0.6 | 14.9 | 1.11 ± 0.99 |
| `lanjian/day_06 input-lanjian` | 5.7 ± 8.2 | 0.9 | 71.8 | 2.41 ± 3.84 |
| `lanjian/day_06 input-mattcl` | 2.5 ± 1.6 | 0.7 | 18.7 | 1.05 ± 0.98 |
| `lanjian/day_06 input-pting` | 2.9 ± 1.2 | 0.7 | 9.0 | 1.24 ± 1.01 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.8 ± 1.4 | 0.5 | 12.4 | 1.19 ± 1.03 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.9 ± 1.4 | 0.8 | 12.7 | 1.21 ± 1.04 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.1 ± 1.8 | 0.8 | 17.3 | 1.32 ± 1.19 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.5 ± 1.3 | 0.6 | 9.8 | 1.07 ± 0.94 |
| `mattcl-solver/aoc run 6 input-pting` | 3.2 ± 1.4 | 0.8 | 16.7 | 1.36 ± 1.13 |
| `python pting/day06.py input-aspidites` | 62.9 ± 16.3 | 47.3 | 125.5 | 26.51 ± 19.86 |
| `python pting/day06.py input-kcen` | 62.2 ± 14.1 | 44.7 | 112.5 | 26.22 ± 19.37 |
| `python pting/day06.py input-lanjian` | 61.2 ± 15.2 | 44.0 | 120.0 | 25.80 ± 19.24 |
| `python pting/day06.py input-mattcl` | 60.2 ± 15.0 | 43.6 | 114.7 | 25.38 ± 18.92 |
| `python pting/day06.py input-pting` | 111.4 ± 95.3 | 48.0 | 452.6 | 46.98 ± 52.01 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
