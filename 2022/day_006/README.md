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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.5 ± 5.7 | 12.3 | 64.0 | 15.68 ± 10.56 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 22.5 ± 4.9 | 12.4 | 35.2 | 13.80 ± 9.29 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 24.8 ± 2.6 | 22.6 | 37.1 | 15.26 ± 9.83 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 21.5 ± 5.4 | 12.6 | 34.4 | 13.20 ± 9.03 |
| `aspidites-solver/aoc -i input-pting -d 6` | 23.8 ± 4.6 | 12.2 | 37.1 | 14.62 ± 9.71 |
| `kcen/2022/06/solve input-aspidites` | 187.8 ± 17.0 | 164.5 | 217.0 | 115.37 ± 74.11 |
| `kcen/2022/06/solve input-kcen` | 156.7 ± 8.9 | 141.9 | 179.3 | 96.24 ± 61.44 |
| `kcen/2022/06/solve input-lanjian` | 195.6 ± 19.2 | 161.2 | 234.8 | 120.18 ± 77.33 |
| `kcen/2022/06/solve input-mattcl` | 194.6 ± 21.4 | 158.5 | 239.2 | 119.58 ± 77.17 |
| `kcen/2022/06/solve input-pting` | 176.8 ± 25.1 | 151.2 | 244.8 | 108.60 ± 70.76 |
| `lanjian/day_06 input-aspidites` | 2.4 ± 1.3 | 0.3 | 19.9 | 1.45 ± 1.21 |
| `lanjian/day_06 input-kcen` | 1.8 ± 1.0 | 0.0 | 11.9 | 1.13 ± 0.95 |
| `lanjian/day_06 input-lanjian` | 2.0 ± 1.0 | 0.5 | 12.4 | 1.25 ± 0.99 |
| `lanjian/day_06 input-mattcl` | 2.0 ± 1.1 | 0.2 | 11.8 | 1.21 ± 1.02 |
| `lanjian/day_06 input-pting` | 1.6 ± 1.0 | 0.1 | 11.2 | 1.00 ± 0.88 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.7 ± 1.3 | 0.5 | 16.6 | 1.64 ± 1.32 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.6 ± 1.0 | 0.0 | 8.6 | 1.00 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.5 ± 1.4 | 0.6 | 17.8 | 1.55 ± 1.30 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.2 ± 1.0 | 0.4 | 15.0 | 1.36 ± 1.05 |
| `mattcl-solver/aoc run 6 input-pting` | 1.8 ± 0.8 | 0.4 | 9.9 | 1.10 ± 0.85 |
| `python pting/day06.py input-aspidites` | 56.7 ± 8.0 | 44.7 | 75.9 | 34.81 ± 22.68 |
| `python pting/day06.py input-kcen` | 51.2 ± 8.2 | 39.9 | 73.5 | 31.47 ± 20.64 |
| `python pting/day06.py input-lanjian` | 56.5 ± 8.0 | 44.2 | 77.6 | 34.70 ± 22.61 |
| `python pting/day06.py input-mattcl` | 53.8 ± 8.3 | 42.4 | 88.2 | 33.06 ± 21.63 |
| `python pting/day06.py input-pting` | 52.9 ± 7.4 | 40.9 | 80.5 | 32.52 ± 21.18 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
