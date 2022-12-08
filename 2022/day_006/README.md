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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.7 ± 1.9 | 23.1 | 36.3 | 13.48 ± 8.88 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 27.3 ± 5.3 | 23.7 | 49.9 | 14.28 ± 9.75 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 27.5 ± 4.9 | 23.6 | 48.3 | 14.39 ± 9.77 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 26.0 ± 5.1 | 13.6 | 47.4 | 13.61 ± 9.30 |
| `aspidites-solver/aoc -i input-pting -d 6` | 29.6 ± 8.2 | 23.9 | 66.7 | 15.51 ± 11.02 |
| `kcen/2022/06/solve input-aspidites` | 195.3 ± 31.3 | 162.3 | 262.1 | 102.31 ± 68.95 |
| `kcen/2022/06/solve input-kcen` | 203.0 ± 22.5 | 173.9 | 253.9 | 106.37 ± 70.61 |
| `kcen/2022/06/solve input-lanjian` | 206.4 ± 28.1 | 163.9 | 274.3 | 108.13 ± 72.29 |
| `kcen/2022/06/solve input-mattcl` | 189.3 ± 31.3 | 156.1 | 271.7 | 99.17 ± 66.95 |
| `kcen/2022/06/solve input-pting` | 193.4 ± 25.5 | 160.3 | 233.0 | 101.31 ± 67.64 |
| `lanjian/day_06 input-aspidites` | 2.6 ± 1.2 | 0.5 | 11.9 | 1.36 ± 1.11 |
| `lanjian/day_06 input-kcen` | 2.5 ± 1.6 | 0.2 | 13.5 | 1.32 ± 1.20 |
| `lanjian/day_06 input-lanjian` | 1.9 ± 1.2 | 0.2 | 18.6 | 1.00 |
| `lanjian/day_06 input-mattcl` | 7.3 ± 6.9 | 1.0 | 53.1 | 3.84 ± 4.41 |
| `lanjian/day_06 input-pting` | 2.5 ± 1.3 | 0.7 | 12.5 | 1.29 ± 1.08 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.8 ± 1.4 | 0.3 | 24.0 | 1.46 ± 1.22 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.2 ± 1.8 | 1.2 | 19.0 | 1.66 ± 1.45 |
| `mattcl-solver/aoc run 6 input-lanjian` | 4.0 ± 2.8 | 1.0 | 43.3 | 2.08 ± 2.01 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.3 ± 2.0 | 0.9 | 21.4 | 1.75 ± 1.54 |
| `mattcl-solver/aoc run 6 input-pting` | 2.8 ± 1.2 | 0.7 | 14.3 | 1.49 ± 1.16 |
| `python pting/day06.py input-aspidites` | 71.4 ± 28.8 | 50.5 | 166.9 | 37.38 ± 28.75 |
| `python pting/day06.py input-kcen` | 59.9 ± 11.1 | 45.6 | 111.9 | 31.39 ± 21.35 |
| `python pting/day06.py input-lanjian` | 63.3 ± 13.0 | 48.3 | 127.7 | 33.18 ± 22.75 |
| `python pting/day06.py input-mattcl` | 59.0 ± 12.9 | 45.8 | 129.5 | 30.90 ± 21.32 |
| `python pting/day06.py input-pting` | 65.7 ± 28.9 | 45.5 | 188.7 | 34.43 ± 27.16 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
