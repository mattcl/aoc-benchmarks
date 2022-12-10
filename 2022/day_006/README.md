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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 18.4 ± 6.0 | 12.3 | 37.3 | 14.67 ± 8.24 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 17.1 ± 5.6 | 12.1 | 33.9 | 13.64 ± 7.65 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 20.1 ± 5.2 | 12.3 | 28.4 | 16.02 ± 8.43 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 13.8 ± 2.5 | 12.2 | 25.9 | 10.99 ± 5.42 |
| `aspidites-solver/aoc -i input-pting -d 6` | 22.2 ± 4.5 | 12.7 | 26.8 | 17.70 ± 8.85 |
| `kcen/2022/06/solve input-aspidites` | 130.3 ± 11.9 | 112.1 | 163.6 | 103.85 ± 48.43 |
| `kcen/2022/06/solve input-kcen` | 129.2 ± 12.5 | 113.1 | 151.7 | 102.92 ± 48.11 |
| `kcen/2022/06/solve input-lanjian` | 129.2 ± 10.7 | 111.4 | 153.4 | 102.93 ± 47.84 |
| `kcen/2022/06/solve input-mattcl` | 117.3 ± 6.1 | 103.7 | 130.1 | 93.44 ± 43.00 |
| `kcen/2022/06/solve input-pting` | 123.4 ± 10.2 | 110.2 | 154.6 | 98.29 ± 45.69 |
| `lanjian/day_06 input-aspidites` | 1.4 ± 0.6 | 0.4 | 7.0 | 1.13 ± 0.73 |
| `lanjian/day_06 input-kcen` | 1.5 ± 0.8 | 0.2 | 13.9 | 1.19 ± 0.87 |
| `lanjian/day_06 input-lanjian` | 1.5 ± 1.7 | 0.3 | 49.3 | 1.18 ± 1.45 |
| `lanjian/day_06 input-mattcl` | 1.3 ± 0.5 | 0.4 | 6.5 | 1.04 ± 0.63 |
| `lanjian/day_06 input-pting` | 1.4 ± 0.7 | 0.4 | 10.4 | 1.13 ± 0.74 |
| `mattcl-solver/aoc run 6 input-aspidites` | 1.7 ± 0.7 | 0.5 | 7.3 | 1.34 ± 0.81 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.7 ± 0.7 | 0.5 | 7.4 | 1.33 ± 0.83 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.3 ± 1.2 | 0.5 | 16.2 | 1.83 ± 1.27 |
| `mattcl-solver/aoc run 6 input-mattcl` | 1.3 ± 0.6 | 0.4 | 7.7 | 1.00 |
| `mattcl-solver/aoc run 6 input-pting` | 1.5 ± 0.6 | 0.6 | 7.3 | 1.23 ± 0.76 |
| `python pting/day06.py input-aspidites` | 39.0 ± 3.6 | 33.6 | 52.0 | 31.07 ± 14.50 |
| `python pting/day06.py input-kcen` | 41.1 ± 3.5 | 35.3 | 51.3 | 32.74 ± 15.22 |
| `python pting/day06.py input-lanjian` | 43.1 ± 4.7 | 35.3 | 58.9 | 34.31 ± 16.13 |
| `python pting/day06.py input-mattcl` | 39.4 ± 4.0 | 32.5 | 53.6 | 31.38 ± 14.70 |
| `python pting/day06.py input-pting` | 40.8 ± 3.5 | 33.4 | 49.2 | 32.47 ± 15.11 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
