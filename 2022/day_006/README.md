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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 23.1 ± 4.9 | 12.3 | 40.2 | 16.64 ± 17.57 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 23.8 ± 4.3 | 12.6 | 36.7 | 17.19 ± 18.04 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 35.8 ± 16.1 | 23.2 | 81.9 | 25.86 ± 29.16 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 24.3 ± 6.7 | 12.9 | 51.2 | 17.58 ± 18.80 |
| `aspidites-solver/aoc -i input-pting -d 6` | 24.5 ± 2.2 | 13.0 | 35.8 | 17.67 ± 18.34 |
| `kcen/2022/06/solve input-aspidites` | 169.4 ± 17.6 | 147.9 | 213.0 | 122.32 ± 127.10 |
| `kcen/2022/06/solve input-kcen` | 165.4 ± 14.6 | 143.0 | 196.4 | 119.39 ± 123.89 |
| `kcen/2022/06/solve input-lanjian` | 163.3 ± 11.1 | 148.6 | 182.6 | 117.88 ± 122.14 |
| `kcen/2022/06/solve input-mattcl` | 195.9 ± 14.5 | 169.8 | 218.4 | 141.41 ± 146.58 |
| `kcen/2022/06/solve input-pting` | 172.8 ± 14.0 | 155.9 | 203.8 | 124.73 ± 129.34 |
| `lanjian/day_06 input-aspidites` | 1.6 ± 0.9 | 0.1 | 8.5 | 1.12 ± 1.33 |
| `lanjian/day_06 input-kcen` | 1.4 ± 1.4 | 0.2 | 28.8 | 1.00 |
| `lanjian/day_06 input-lanjian` | 1.4 ± 1.1 | 0.2 | 12.7 | 1.02 ± 1.30 |
| `lanjian/day_06 input-mattcl` | 1.9 ± 1.1 | 0.4 | 11.2 | 1.34 ± 1.61 |
| `lanjian/day_06 input-pting` | 1.7 ± 1.1 | 0.3 | 8.0 | 1.26 ± 1.52 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.5 ± 1.3 | 0.8 | 8.4 | 1.82 ± 2.09 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.2 ± 1.0 | 0.5 | 8.6 | 1.57 ± 1.78 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.2 ± 1.1 | 0.5 | 11.6 | 1.58 ± 1.81 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.4 ± 1.2 | 0.8 | 11.7 | 1.70 ± 1.96 |
| `mattcl-solver/aoc run 6 input-pting` | 2.2 ± 1.0 | 0.5 | 8.6 | 1.61 ± 1.83 |
| `python pting/day06.py input-aspidites` | 51.0 ± 5.9 | 40.0 | 70.3 | 36.84 ± 38.32 |
| `python pting/day06.py input-kcen` | 51.0 ± 6.8 | 40.0 | 75.0 | 36.85 ± 38.42 |
| `python pting/day06.py input-lanjian` | 53.7 ± 6.2 | 44.6 | 72.1 | 38.75 ± 40.31 |
| `python pting/day06.py input-mattcl` | 52.8 ± 6.4 | 42.0 | 73.4 | 38.13 ± 39.69 |
| `python pting/day06.py input-pting` | 53.1 ± 7.1 | 43.2 | 79.9 | 38.35 ± 39.98 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
