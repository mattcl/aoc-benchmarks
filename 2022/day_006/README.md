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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 32.9 ± 18.9 | 19.2 | 145.9 | 17.07 ± 13.45 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 26.7 ± 4.1 | 13.3 | 47.9 | 13.85 ± 7.76 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 28.1 ± 6.7 | 23.3 | 58.2 | 14.58 ± 8.59 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 17.7 ± 5.3 | 12.8 | 27.6 | 9.21 ± 5.67 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.2 ± 3.2 | 22.6 | 45.1 | 13.60 ± 7.51 |
| `kcen/2022/06/solve input-aspidites` | 203.9 ± 56.7 | 161.2 | 342.8 | 105.93 ± 64.23 |
| `kcen/2022/06/solve input-kcen` | 175.2 ± 14.7 | 154.7 | 203.5 | 91.03 ± 49.62 |
| `kcen/2022/06/solve input-lanjian` | 193.1 ± 25.0 | 164.0 | 242.8 | 100.35 ± 55.59 |
| `kcen/2022/06/solve input-mattcl` | 193.3 ± 31.6 | 143.6 | 246.5 | 100.46 ± 56.54 |
| `kcen/2022/06/solve input-pting` | 199.5 ± 24.1 | 162.6 | 242.0 | 103.68 ± 57.23 |
| `lanjian/day_06 input-aspidites` | 1.9 ± 1.0 | 0.5 | 10.3 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.2 ± 1.2 | 0.5 | 14.7 | 1.16 ± 0.87 |
| `lanjian/day_06 input-lanjian` | 2.6 ± 1.4 | 0.7 | 23.7 | 1.33 ± 1.04 |
| `lanjian/day_06 input-mattcl` | 2.6 ± 1.6 | 0.4 | 17.1 | 1.37 ± 1.12 |
| `lanjian/day_06 input-pting` | 3.1 ± 1.8 | 0.8 | 20.5 | 1.61 ± 1.26 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.5 ± 1.1 | 0.5 | 7.4 | 1.29 ± 0.90 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.0 ± 1.5 | 0.6 | 13.2 | 1.54 ± 1.14 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.7 ± 1.2 | 0.5 | 13.4 | 1.41 ± 0.99 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.2 ± 1.9 | 0.7 | 12.7 | 1.65 ± 1.32 |
| `mattcl-solver/aoc run 6 input-pting` | 3.1 ± 1.2 | 0.9 | 15.3 | 1.59 ± 1.06 |
| `python pting/day06.py input-aspidites` | 57.7 ± 9.4 | 45.5 | 92.7 | 29.99 ± 16.87 |
| `python pting/day06.py input-kcen` | 58.1 ± 8.8 | 47.6 | 75.6 | 30.18 ± 16.89 |
| `python pting/day06.py input-lanjian` | 64.1 ± 9.9 | 51.0 | 93.9 | 33.30 ± 18.65 |
| `python pting/day06.py input-mattcl` | 56.8 ± 8.9 | 41.4 | 78.4 | 29.50 ± 16.54 |
| `python pting/day06.py input-pting` | 62.6 ± 8.6 | 49.7 | 85.5 | 32.53 ± 18.09 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
