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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 38.4 ± 31.7 | 23.8 | 179.3 | 16.19 ± 17.68 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 28.7 ± 5.5 | 23.6 | 50.5 | 12.07 ± 8.96 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 28.1 ± 5.6 | 23.8 | 48.0 | 11.82 ± 8.80 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 25.3 ± 3.7 | 13.2 | 34.9 | 10.65 ± 7.80 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.9 ± 3.9 | 23.0 | 45.8 | 11.35 ± 8.30 |
| `kcen/2022/06/solve input-aspidites` | 185.6 ± 24.2 | 155.4 | 223.5 | 78.14 ± 56.98 |
| `kcen/2022/06/solve input-kcen` | 200.0 ± 27.8 | 158.1 | 243.0 | 84.23 ± 61.55 |
| `kcen/2022/06/solve input-lanjian` | 218.5 ± 27.2 | 170.6 | 250.7 | 91.99 ± 66.97 |
| `kcen/2022/06/solve input-mattcl` | 197.6 ± 27.5 | 166.0 | 238.4 | 83.22 ± 60.81 |
| `kcen/2022/06/solve input-pting` | 199.3 ± 22.2 | 168.7 | 228.7 | 83.93 ± 60.93 |
| `lanjian/day_06 input-aspidites` | 2.4 ± 1.7 | 0.0 | 26.1 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.7 ± 2.2 | 0.0 | 34.1 | 1.14 ± 1.22 |
| `lanjian/day_06 input-lanjian` | 2.6 ± 1.2 | 0.5 | 14.0 | 1.08 ± 0.93 |
| `lanjian/day_06 input-mattcl` | 2.6 ± 1.6 | 0.3 | 21.1 | 1.11 ± 1.04 |
| `lanjian/day_06 input-pting` | 3.5 ± 2.7 | 0.4 | 23.2 | 1.47 ± 1.54 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.8 ± 1.4 | 0.4 | 12.4 | 1.16 ± 1.03 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.4 ± 1.9 | 0.9 | 19.6 | 1.45 ± 1.30 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.4 ± 1.5 | 0.2 | 14.9 | 1.01 ± 0.96 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.9 ± 1.8 | 0.8 | 14.8 | 1.23 ± 1.15 |
| `mattcl-solver/aoc run 6 input-pting` | 10.1 ± 10.4 | 1.2 | 53.5 | 4.23 ± 5.34 |
| `python pting/day06.py input-aspidites` | 64.8 ± 10.5 | 49.7 | 96.3 | 27.29 ± 20.07 |
| `python pting/day06.py input-kcen` | 63.1 ± 9.9 | 48.9 | 85.4 | 26.58 ± 19.52 |
| `python pting/day06.py input-lanjian` | 69.4 ± 10.5 | 52.9 | 94.7 | 29.21 ± 21.41 |
| `python pting/day06.py input-mattcl` | 60.9 ± 8.8 | 45.4 | 79.8 | 25.64 ± 18.76 |
| `python pting/day06.py input-pting` | 77.3 ± 13.5 | 55.3 | 123.9 | 32.53 ± 24.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
