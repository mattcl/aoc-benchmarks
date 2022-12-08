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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.6 ± 2.5 | 13.3 | 38.3 | 15.11 ± 9.67 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 22.8 ± 5.3 | 12.6 | 36.2 | 13.45 ± 9.06 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.9 ± 2.8 | 23.3 | 39.7 | 15.32 ± 9.83 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.4 ± 5.3 | 12.7 | 35.7 | 13.84 ± 9.30 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.5 ± 3.5 | 12.6 | 51.2 | 15.06 ± 9.75 |
| `kcen/2022/06/solve input-aspidites` | 174.4 ± 31.6 | 144.7 | 246.7 | 103.03 ± 67.79 |
| `kcen/2022/06/solve input-kcen` | 175.5 ± 16.4 | 155.8 | 211.7 | 103.66 ± 66.28 |
| `kcen/2022/06/solve input-lanjian` | 171.0 ± 20.4 | 145.0 | 218.2 | 100.98 ± 64.99 |
| `kcen/2022/06/solve input-mattcl` | 192.3 ± 27.5 | 162.2 | 250.1 | 113.60 ± 73.66 |
| `kcen/2022/06/solve input-pting` | 206.4 ± 19.3 | 177.5 | 241.0 | 121.95 ± 77.97 |
| `lanjian/day_06 input-aspidites` | 1.8 ± 1.2 | 0.2 | 8.0 | 1.05 ± 0.95 |
| `lanjian/day_06 input-kcen` | 2.9 ± 1.9 | 0.6 | 16.0 | 1.74 ± 1.58 |
| `lanjian/day_06 input-lanjian` | 2.4 ± 1.2 | 0.8 | 10.9 | 1.41 ± 1.14 |
| `lanjian/day_06 input-mattcl` | 1.7 ± 1.1 | 0.2 | 6.9 | 1.00 |
| `lanjian/day_06 input-pting` | 4.1 ± 4.3 | 0.5 | 48.4 | 2.44 ± 2.96 |
| `mattcl-solver/aoc run 6 input-aspidites` | 3.6 ± 1.5 | 1.4 | 20.0 | 2.14 ± 1.63 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.4 ± 1.2 | 1.4 | 10.1 | 2.01 ± 1.44 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.1 ± 1.6 | 1.2 | 20.6 | 1.82 ± 1.50 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.1 ± 1.1 | 1.2 | 11.4 | 1.81 ± 1.32 |
| `mattcl-solver/aoc run 6 input-pting` | 3.0 ± 1.0 | 1.0 | 9.2 | 1.75 ± 1.25 |
| `python pting/day06.py input-aspidites` | 55.6 ± 8.7 | 43.2 | 79.6 | 32.87 ± 21.41 |
| `python pting/day06.py input-kcen` | 57.8 ± 10.3 | 44.0 | 93.8 | 34.16 ± 22.45 |
| `python pting/day06.py input-lanjian` | 54.3 ± 7.2 | 45.0 | 74.4 | 32.10 ± 20.74 |
| `python pting/day06.py input-mattcl` | 48.0 ± 8.0 | 38.6 | 73.9 | 28.35 ± 18.54 |
| `python pting/day06.py input-pting` | 57.9 ± 12.7 | 41.9 | 126.5 | 34.21 ± 22.89 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
