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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 11.0 ± 0.2 | 10.9 | 12.8 | 21.46 ± 2.68 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 11.0 ± 0.1 | 10.9 | 11.4 | 21.39 ± 2.65 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 11.0 ± 0.1 | 10.9 | 11.3 | 21.38 ± 2.65 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 11.0 ± 0.1 | 10.9 | 12.8 | 21.35 ± 2.65 |
| `aspidites-solver/aoc -i input-pting -d 6` | 11.0 ± 0.1 | 10.9 | 12.2 | 21.37 ± 2.65 |
| `kcen/2022/06/solve input-aspidites` | 68.9 ± 2.7 | 66.4 | 85.4 | 133.78 ± 17.36 |
| `kcen/2022/06/solve input-kcen` | 71.1 ± 3.0 | 66.6 | 77.4 | 138.05 ± 18.05 |
| `kcen/2022/06/solve input-lanjian` | 68.0 ± 0.9 | 66.8 | 71.0 | 132.16 ± 16.41 |
| `kcen/2022/06/solve input-mattcl` | 68.3 ± 0.9 | 66.9 | 71.0 | 132.76 ± 16.49 |
| `kcen/2022/06/solve input-pting` | 67.9 ± 0.8 | 66.9 | 70.4 | 131.94 ± 16.38 |
| `lanjian/day_06 input-aspidites` | 0.5 ± 0.1 | 0.4 | 2.5 | 1.02 ± 0.20 |
| `lanjian/day_06 input-kcen` | 0.5 ± 0.1 | 0.4 | 2.3 | 1.00 |
| `lanjian/day_06 input-lanjian` | 0.5 ± 0.1 | 0.5 | 2.5 | 1.02 ± 0.21 |
| `lanjian/day_06 input-mattcl` | 0.5 ± 0.1 | 0.4 | 2.2 | 1.01 ± 0.19 |
| `lanjian/day_06 input-pting` | 0.6 ± 0.1 | 0.5 | 3.3 | 1.09 ± 0.21 |
| `mattcl-solver/aoc run 6 input-aspidites` | 0.6 ± 0.1 | 0.5 | 2.6 | 1.18 ± 0.21 |
| `mattcl-solver/aoc run 6 input-kcen` | 0.6 ± 0.1 | 0.5 | 2.4 | 1.17 ± 0.19 |
| `mattcl-solver/aoc run 6 input-lanjian` | 0.6 ± 0.1 | 0.5 | 2.8 | 1.18 ± 0.20 |
| `mattcl-solver/aoc run 6 input-mattcl` | 0.6 ± 0.1 | 0.5 | 3.0 | 1.20 ± 0.25 |
| `mattcl-solver/aoc run 6 input-pting` | 0.6 ± 0.1 | 0.5 | 2.1 | 1.17 ± 0.19 |
| `python pting/day06.py input-aspidites` | 20.6 ± 0.4 | 20.0 | 23.1 | 40.08 ± 5.02 |
| `python pting/day06.py input-kcen` | 20.6 ± 0.4 | 20.0 | 22.7 | 39.98 ± 5.00 |
| `python pting/day06.py input-lanjian` | 21.2 ± 0.4 | 20.5 | 23.2 | 41.24 ± 5.16 |
| `python pting/day06.py input-mattcl` | 20.3 ± 0.6 | 19.5 | 23.1 | 39.38 ± 4.99 |
| `python pting/day06.py input-pting` | 21.4 ± 0.7 | 20.5 | 26.0 | 41.53 ± 5.29 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
