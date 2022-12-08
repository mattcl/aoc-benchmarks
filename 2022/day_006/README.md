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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.1 ± 3.8 | 12.6 | 45.7 | 16.13 ± 14.14 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 27.4 ± 5.2 | 14.0 | 52.4 | 17.66 ± 15.62 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.3 ± 3.5 | 23.4 | 43.0 | 16.95 ± 14.80 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 27.1 ± 15.4 | 12.7 | 125.5 | 17.41 ± 18.01 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.5 ± 2.6 | 23.1 | 45.9 | 16.38 ± 14.24 |
| `kcen/2022/06/solve input-aspidites` | 211.9 ± 19.4 | 173.4 | 236.9 | 136.36 ± 118.41 |
| `kcen/2022/06/solve input-kcen` | 186.0 ± 18.1 | 156.8 | 213.6 | 119.65 ± 103.98 |
| `kcen/2022/06/solve input-lanjian` | 172.4 ± 31.0 | 138.4 | 249.1 | 110.94 ± 97.85 |
| `kcen/2022/06/solve input-mattcl` | 181.4 ± 21.0 | 155.6 | 237.1 | 116.74 ± 101.71 |
| `kcen/2022/06/solve input-pting` | 184.5 ± 24.6 | 148.9 | 221.9 | 118.72 ± 103.74 |
| `lanjian/day_06 input-aspidites` | 1.7 ± 1.1 | 0.0 | 7.3 | 1.08 ± 1.17 |
| `lanjian/day_06 input-kcen` | 2.1 ± 1.2 | 0.3 | 12.8 | 1.37 ± 1.41 |
| `lanjian/day_06 input-lanjian` | 1.6 ± 1.3 | 0.0 | 17.7 | 1.00 |
| `lanjian/day_06 input-mattcl` | 2.1 ± 1.2 | 0.1 | 11.3 | 1.32 ± 1.38 |
| `lanjian/day_06 input-pting` | 2.1 ± 1.4 | 0.2 | 12.6 | 1.37 ± 1.49 |
| `mattcl-solver/aoc run 6 input-aspidites` | 6.1 ± 11.2 | 0.8 | 100.6 | 3.95 ± 7.97 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.7 ± 1.0 | 0.5 | 9.5 | 1.72 ± 1.62 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.8 ± 1.7 | 0.6 | 15.9 | 1.79 ± 1.89 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.6 ± 1.1 | 0.9 | 8.2 | 1.64 ± 1.59 |
| `mattcl-solver/aoc run 6 input-pting` | 3.0 ± 1.6 | 0.9 | 18.8 | 1.91 ± 1.94 |
| `python pting/day06.py input-aspidites` | 61.3 ± 6.7 | 48.2 | 74.7 | 39.46 ± 34.34 |
| `python pting/day06.py input-kcen` | 57.6 ± 7.4 | 44.3 | 76.4 | 37.04 ± 32.34 |
| `python pting/day06.py input-lanjian` | 59.7 ± 10.0 | 46.9 | 92.1 | 38.43 ± 33.81 |
| `python pting/day06.py input-mattcl` | 59.5 ± 7.6 | 43.3 | 82.7 | 38.31 ± 33.44 |
| `python pting/day06.py input-pting` | 58.6 ± 7.4 | 46.4 | 74.6 | 37.73 ± 32.93 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
