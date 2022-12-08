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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.0 ± 3.4 | 12.9 | 46.7 | 19.21 ± 14.25 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 24.6 ± 2.6 | 12.8 | 35.1 | 18.97 ± 13.97 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.0 ± 2.3 | 22.9 | 37.7 | 19.24 ± 14.13 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 21.3 ± 6.0 | 12.5 | 38.6 | 16.37 ± 12.80 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.3 ± 3.6 | 12.6 | 45.5 | 19.47 ± 14.46 |
| `kcen/2022/06/solve input-aspidites` | 225.8 ± 91.1 | 158.7 | 402.5 | 173.81 ± 144.79 |
| `kcen/2022/06/solve input-kcen` | 161.7 ± 13.4 | 150.4 | 192.9 | 124.46 ± 91.29 |
| `kcen/2022/06/solve input-lanjian` | 162.7 ± 12.0 | 144.7 | 191.1 | 125.24 ± 91.74 |
| `kcen/2022/06/solve input-mattcl` | 174.8 ± 15.6 | 150.6 | 206.4 | 134.52 ± 98.77 |
| `kcen/2022/06/solve input-pting` | 181.7 ± 20.7 | 146.8 | 236.9 | 139.80 ± 103.12 |
| `lanjian/day_06 input-aspidites` | 1.6 ± 1.7 | 0.0 | 16.9 | 1.24 ± 1.57 |
| `lanjian/day_06 input-kcen` | 1.3 ± 0.9 | 0.0 | 12.8 | 1.00 |
| `lanjian/day_06 input-lanjian` | 1.4 ± 1.0 | 0.0 | 10.9 | 1.09 ± 1.10 |
| `lanjian/day_06 input-mattcl` | 1.8 ± 1.5 | 0.1 | 16.3 | 1.42 ± 1.53 |
| `lanjian/day_06 input-pting` | 1.7 ± 1.4 | 0.2 | 14.1 | 1.33 ± 1.44 |
| `mattcl-solver/aoc run 6 input-aspidites` | 1.8 ± 1.2 | 0.3 | 12.4 | 1.42 ± 1.39 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.6 ± 1.0 | 0.2 | 11.0 | 1.23 ± 1.20 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.3 ± 1.7 | 0.3 | 17.1 | 1.80 ± 1.83 |
| `mattcl-solver/aoc run 6 input-mattcl` | 1.8 ± 1.0 | 0.3 | 14.6 | 1.39 ± 1.28 |
| `mattcl-solver/aoc run 6 input-pting` | 1.7 ± 1.1 | 0.2 | 8.2 | 1.29 ± 1.24 |
| `python pting/day06.py input-aspidites` | 63.2 ± 24.0 | 45.8 | 154.6 | 48.66 ± 39.98 |
| `python pting/day06.py input-kcen` | 52.2 ± 8.3 | 40.9 | 76.9 | 40.20 ± 29.99 |
| `python pting/day06.py input-lanjian` | 52.3 ± 6.3 | 44.1 | 76.2 | 40.25 ± 29.73 |
| `python pting/day06.py input-mattcl` | 54.8 ± 10.1 | 42.0 | 86.5 | 42.15 ± 31.69 |
| `python pting/day06.py input-pting` | 54.1 ± 6.1 | 41.1 | 83.5 | 41.64 ± 30.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
