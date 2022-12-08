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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 24.7 ± 3.0 | 13.2 | 48.0 | 15.04 ± 10.40 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 24.1 ± 5.1 | 12.9 | 46.2 | 14.71 ± 10.48 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.3 ± 2.3 | 23.3 | 41.2 | 15.42 ± 10.58 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 35.5 ± 26.4 | 12.6 | 147.4 | 21.62 ± 21.80 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.2 ± 1.6 | 23.2 | 35.4 | 15.35 ± 10.49 |
| `kcen/2022/06/solve input-aspidites` | 177.5 ± 24.9 | 147.0 | 230.9 | 108.17 ± 75.17 |
| `kcen/2022/06/solve input-kcen` | 168.0 ± 22.3 | 142.7 | 213.2 | 102.35 ± 70.97 |
| `kcen/2022/06/solve input-lanjian` | 176.4 ± 12.0 | 158.0 | 200.4 | 107.49 ± 73.53 |
| `kcen/2022/06/solve input-mattcl` | 162.2 ± 19.7 | 137.0 | 213.7 | 98.84 ± 68.34 |
| `kcen/2022/06/solve input-pting` | 162.7 ± 13.1 | 142.3 | 191.8 | 99.16 ± 67.96 |
| `lanjian/day_06 input-aspidites` | 2.1 ± 1.4 | 0.4 | 15.2 | 1.29 ± 1.24 |
| `lanjian/day_06 input-kcen` | 2.5 ± 1.9 | 0.3 | 23.8 | 1.53 ± 1.57 |
| `lanjian/day_06 input-lanjian` | 2.1 ± 1.5 | 0.3 | 16.3 | 1.28 ± 1.27 |
| `lanjian/day_06 input-mattcl` | 1.8 ± 1.0 | 0.3 | 12.9 | 1.07 ± 0.96 |
| `lanjian/day_06 input-pting` | 1.6 ± 1.1 | 0.2 | 13.0 | 1.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.6 ± 1.2 | 0.8 | 9.5 | 1.60 ± 1.30 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.9 ± 1.6 | 0.5 | 22.3 | 1.74 ± 1.54 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.4 ± 1.2 | 0.5 | 13.4 | 1.48 ± 1.24 |
| `mattcl-solver/aoc run 6 input-mattcl` | 1.9 ± 0.8 | 0.5 | 5.7 | 1.19 ± 0.95 |
| `mattcl-solver/aoc run 6 input-pting` | 2.4 ± 1.2 | 0.5 | 12.4 | 1.47 ± 1.22 |
| `python pting/day06.py input-aspidites` | 53.0 ± 9.2 | 41.4 | 97.1 | 32.32 ± 22.69 |
| `python pting/day06.py input-kcen` | 51.3 ± 6.6 | 39.2 | 73.2 | 31.25 ± 21.65 |
| `python pting/day06.py input-lanjian` | 59.2 ± 8.9 | 46.6 | 82.5 | 36.08 ± 25.15 |
| `python pting/day06.py input-mattcl` | 53.5 ± 11.1 | 42.6 | 85.0 | 32.59 ± 23.18 |
| `python pting/day06.py input-pting` | 52.3 ± 6.6 | 44.1 | 73.4 | 31.84 ± 22.04 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
