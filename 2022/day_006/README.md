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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.4 ± 4.9 | 23.0 | 49.9 | 18.26 ± 15.04 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 27.8 ± 5.1 | 22.3 | 51.8 | 19.23 ± 15.84 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.4 ± 3.6 | 23.7 | 45.0 | 18.24 ± 14.86 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.9 ± 4.0 | 13.2 | 35.5 | 16.49 ± 13.53 |
| `aspidites-solver/aoc -i input-pting -d 6` | 27.1 ± 5.2 | 22.9 | 50.0 | 18.71 ± 15.44 |
| `kcen/2022/06/solve input-aspidites` | 276.4 ± 95.7 | 184.9 | 451.0 | 190.82 ± 166.86 |
| `kcen/2022/06/solve input-kcen` | 212.6 ± 21.8 | 185.3 | 252.3 | 146.78 ± 118.81 |
| `kcen/2022/06/solve input-lanjian` | 213.6 ± 30.1 | 155.0 | 263.6 | 147.52 ± 120.25 |
| `kcen/2022/06/solve input-mattcl` | 192.3 ± 29.5 | 163.1 | 262.4 | 132.77 ± 108.54 |
| `kcen/2022/06/solve input-pting` | 200.0 ± 32.2 | 164.4 | 257.5 | 138.10 ± 113.09 |
| `lanjian/day_06 input-aspidites` | 1.4 ± 1.2 | 0.0 | 12.0 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.5 ± 2.2 | 0.0 | 26.2 | 1.73 ± 2.05 |
| `lanjian/day_06 input-lanjian` | 2.6 ± 1.5 | 0.4 | 13.5 | 1.76 ± 1.76 |
| `lanjian/day_06 input-mattcl` | 2.7 ± 1.4 | 0.6 | 16.1 | 1.83 ± 1.75 |
| `lanjian/day_06 input-pting` | 2.3 ± 1.6 | 0.3 | 16.1 | 1.60 ± 1.70 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.5 ± 1.4 | 0.4 | 10.5 | 1.73 ± 1.69 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.0 ± 3.2 | 0.5 | 68.2 | 2.07 ± 2.76 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.6 ± 1.3 | 0.8 | 9.4 | 1.81 ± 1.72 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.8 ± 1.4 | 0.7 | 17.9 | 1.97 ± 1.86 |
| `mattcl-solver/aoc run 6 input-pting` | 2.5 ± 1.3 | 0.2 | 13.6 | 1.75 ± 1.68 |
| `python pting/day06.py input-aspidites` | 55.7 ± 6.8 | 45.3 | 67.8 | 38.44 ± 31.22 |
| `python pting/day06.py input-kcen` | 58.5 ± 10.3 | 41.9 | 88.5 | 40.41 ± 33.22 |
| `python pting/day06.py input-lanjian` | 63.1 ± 8.9 | 50.7 | 87.8 | 43.56 ± 35.51 |
| `python pting/day06.py input-mattcl` | 60.0 ± 8.4 | 47.5 | 79.5 | 41.46 ± 33.79 |
| `python pting/day06.py input-pting` | 65.0 ± 16.8 | 46.7 | 129.0 | 44.85 ± 37.84 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
