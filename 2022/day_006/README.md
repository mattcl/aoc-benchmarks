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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 22.6 ± 5.1 | 12.6 | 35.8 | 12.82 ± 7.43 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 23.9 ± 4.8 | 12.9 | 36.7 | 13.56 ± 7.72 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.1 ± 2.9 | 12.9 | 36.5 | 14.25 ± 7.77 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.2 ± 5.8 | 13.2 | 39.5 | 13.17 ± 7.75 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.2 ± 2.8 | 12.7 | 38.2 | 14.29 ± 7.78 |
| `kcen/2022/06/solve input-aspidites` | 176.8 ± 33.4 | 139.6 | 254.6 | 100.37 ± 56.73 |
| `kcen/2022/06/solve input-kcen` | 170.3 ± 22.6 | 146.4 | 205.9 | 96.67 ± 53.08 |
| `kcen/2022/06/solve input-lanjian` | 169.1 ± 13.3 | 150.4 | 201.6 | 95.98 ± 51.70 |
| `kcen/2022/06/solve input-mattcl` | 172.6 ± 23.9 | 143.0 | 224.8 | 97.98 ± 53.94 |
| `kcen/2022/06/solve input-pting` | 191.1 ± 22.9 | 148.5 | 223.7 | 108.48 ± 59.24 |
| `lanjian/day_06 input-aspidites` | 2.2 ± 1.0 | 0.5 | 8.9 | 1.25 ± 0.86 |
| `lanjian/day_06 input-kcen` | 1.9 ± 0.7 | 0.6 | 5.7 | 1.08 ± 0.71 |
| `lanjian/day_06 input-lanjian` | 2.7 ± 1.0 | 1.1 | 9.5 | 1.53 ± 0.99 |
| `lanjian/day_06 input-mattcl` | 2.7 ± 1.6 | 0.6 | 17.9 | 1.52 ± 1.23 |
| `lanjian/day_06 input-pting` | 1.8 ± 0.9 | 0.4 | 9.6 | 1.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.4 ± 1.0 | 0.6 | 9.9 | 1.35 ± 0.92 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.2 ± 0.8 | 0.7 | 6.6 | 1.24 ± 0.80 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.2 ± 1.4 | 1.2 | 13.4 | 1.84 ± 1.25 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.5 ± 0.9 | 0.7 | 8.9 | 1.44 ± 0.93 |
| `mattcl-solver/aoc run 6 input-pting` | 2.6 ± 1.3 | 0.7 | 10.9 | 1.49 ± 1.07 |
| `python pting/day06.py input-aspidites` | 67.4 ± 46.7 | 38.1 | 294.8 | 38.23 ± 33.42 |
| `python pting/day06.py input-kcen` | 52.4 ± 9.9 | 39.1 | 91.9 | 29.74 ± 16.82 |
| `python pting/day06.py input-lanjian` | 58.6 ± 10.3 | 43.6 | 89.5 | 33.23 ± 18.64 |
| `python pting/day06.py input-mattcl` | 58.8 ± 11.2 | 43.5 | 100.4 | 33.36 ± 18.87 |
| `python pting/day06.py input-pting` | 51.3 ± 7.9 | 39.6 | 74.8 | 29.14 ± 16.16 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
