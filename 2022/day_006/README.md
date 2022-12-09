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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 73.4 ± 39.3 | 24.2 | 177.7 | 41.10 ± 28.73 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 27.5 ± 8.5 | 12.4 | 68.7 | 15.43 ± 8.40 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.8 ± 3.7 | 20.0 | 46.7 | 14.43 ± 6.79 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 24.8 ± 4.8 | 12.5 | 39.6 | 13.91 ± 6.80 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.2 ± 4.7 | 16.5 | 48.9 | 14.66 ± 7.09 |
| `kcen/2022/06/solve input-aspidites` | 188.7 ± 51.8 | 152.0 | 349.7 | 105.75 ± 55.64 |
| `kcen/2022/06/solve input-kcen` | 209.3 ± 38.9 | 159.4 | 302.9 | 117.24 ± 56.94 |
| `kcen/2022/06/solve input-lanjian` | 176.6 ± 16.2 | 157.2 | 226.0 | 98.93 ± 45.32 |
| `kcen/2022/06/solve input-mattcl` | 173.5 ± 25.3 | 140.1 | 223.9 | 97.19 ± 45.86 |
| `kcen/2022/06/solve input-pting` | 185.5 ± 33.2 | 147.0 | 306.4 | 103.92 ± 50.22 |
| `lanjian/day_06 input-aspidites` | 2.4 ± 1.3 | 0.3 | 11.1 | 1.37 ± 0.95 |
| `lanjian/day_06 input-kcen` | 2.3 ± 1.7 | 0.3 | 14.7 | 1.31 ± 1.12 |
| `lanjian/day_06 input-lanjian` | 2.1 ± 0.9 | 0.4 | 8.2 | 1.16 ± 0.73 |
| `lanjian/day_06 input-mattcl` | 2.3 ± 1.6 | 0.2 | 17.3 | 1.29 ± 1.05 |
| `lanjian/day_06 input-pting` | 1.8 ± 0.8 | 0.4 | 6.5 | 1.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.8 ± 1.4 | 0.8 | 12.2 | 1.55 ± 1.03 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.5 ± 1.0 | 0.8 | 7.1 | 1.42 ± 0.85 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.8 ± 1.3 | 1.0 | 22.9 | 1.55 ± 1.00 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.2 ± 0.9 | 0.6 | 10.2 | 1.24 ± 0.77 |
| `mattcl-solver/aoc run 6 input-pting` | 2.4 ± 1.0 | 0.5 | 8.9 | 1.36 ± 0.82 |
| `python pting/day06.py input-aspidites` | 57.4 ± 9.2 | 46.6 | 81.5 | 32.18 ± 15.33 |
| `python pting/day06.py input-kcen` | 57.4 ± 8.7 | 41.2 | 79.2 | 32.15 ± 15.23 |
| `python pting/day06.py input-lanjian` | 54.8 ± 11.0 | 41.4 | 101.5 | 30.69 ± 15.10 |
| `python pting/day06.py input-mattcl` | 59.5 ± 7.9 | 46.1 | 86.2 | 33.32 ± 15.59 |
| `python pting/day06.py input-pting` | 57.2 ± 13.0 | 44.0 | 111.0 | 32.07 ± 16.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
