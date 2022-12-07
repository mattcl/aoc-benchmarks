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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.6 ± 3.2 | 24.1 | 40.4 | 12.23 ± 9.80 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 24.8 ± 4.2 | 13.2 | 45.1 | 11.42 ± 9.25 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.7 ± 3.1 | 23.0 | 38.6 | 12.28 ± 9.84 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 27.8 ± 5.9 | 13.7 | 48.3 | 12.80 ± 10.50 |
| `aspidites-solver/aoc -i input-pting -d 6` | 29.0 ± 4.8 | 24.3 | 46.9 | 13.33 ± 10.79 |
| `kcen/2022/06/solve input-aspidites` | 203.5 ± 19.1 | 171.9 | 236.1 | 93.65 ± 74.71 |
| `kcen/2022/06/solve input-kcen` | 183.0 ± 18.2 | 156.5 | 212.7 | 84.22 ± 67.24 |
| `kcen/2022/06/solve input-lanjian` | 219.2 ± 15.4 | 195.7 | 244.4 | 100.85 ± 80.21 |
| `kcen/2022/06/solve input-mattcl` | 204.7 ± 25.7 | 171.5 | 263.6 | 94.20 ± 75.56 |
| `kcen/2022/06/solve input-pting` | 196.7 ± 19.6 | 174.7 | 234.6 | 90.49 ± 72.26 |
| `lanjian/day_06 input-aspidites` | 3.3 ± 3.3 | 0.6 | 47.8 | 1.52 ± 1.96 |
| `lanjian/day_06 input-kcen` | 2.2 ± 1.7 | 0.6 | 23.5 | 1.00 |
| `lanjian/day_06 input-lanjian` | 3.2 ± 2.0 | 0.7 | 20.1 | 1.46 ± 1.48 |
| `lanjian/day_06 input-mattcl` | 3.0 ± 1.2 | 0.9 | 10.8 | 1.39 ± 1.24 |
| `lanjian/day_06 input-pting` | 3.1 ± 1.9 | 0.9 | 18.5 | 1.42 ± 1.42 |
| `mattcl-solver/aoc run 6 input-aspidites` | 3.9 ± 3.8 | 1.1 | 61.4 | 1.79 ± 2.24 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.4 ± 1.7 | 1.0 | 20.4 | 1.56 ± 1.45 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.5 ± 1.2 | 0.8 | 17.6 | 1.16 ± 1.08 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.7 ± 1.5 | 1.0 | 9.9 | 1.69 ± 1.51 |
| `mattcl-solver/aoc run 6 input-pting` | 3.4 ± 1.9 | 1.3 | 34.8 | 1.57 ± 1.51 |
| `python pting/day06.py input-aspidites` | 69.6 ± 17.2 | 49.4 | 146.2 | 32.02 ± 26.58 |
| `python pting/day06.py input-kcen` | 56.4 ± 8.8 | 42.6 | 86.7 | 25.97 ± 20.97 |
| `python pting/day06.py input-lanjian` | 67.9 ± 10.6 | 56.4 | 110.8 | 31.24 ± 25.22 |
| `python pting/day06.py input-mattcl` | 67.2 ± 26.4 | 42.4 | 167.8 | 30.90 ± 27.32 |
| `python pting/day06.py input-pting` | 64.8 ± 10.5 | 49.0 | 92.7 | 29.79 ± 24.10 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
