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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 23.7 ± 2.1 | 12.0 | 28.4 | 46.84 ± 78.22 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 24.1 ± 2.2 | 13.2 | 31.6 | 47.71 ± 79.67 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 24.3 ± 2.9 | 21.7 | 36.6 | 48.07 ± 80.37 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.4 ± 3.7 | 12.0 | 34.6 | 46.26 ± 77.48 |
| `aspidites-solver/aoc -i input-pting -d 6` | 24.3 ± 2.1 | 21.9 | 38.1 | 48.03 ± 80.20 |
| `kcen/2022/06/solve input-aspidites` | 174.5 ± 14.6 | 155.1 | 206.0 | 344.79 ± 575.67 |
| `kcen/2022/06/solve input-kcen` | 167.3 ± 20.9 | 146.1 | 233.8 | 330.71 ± 553.01 |
| `kcen/2022/06/solve input-lanjian` | 174.1 ± 16.5 | 145.6 | 204.6 | 344.17 ± 574.83 |
| `kcen/2022/06/solve input-mattcl` | 191.7 ± 20.3 | 158.1 | 234.1 | 378.85 ± 633.00 |
| `kcen/2022/06/solve input-pting` | 255.7 ± 105.8 | 157.1 | 496.6 | 505.30 ± 868.17 |
| `lanjian/day_06 input-aspidites` | 1.1 ± 1.1 | 0.0 | 15.4 | 2.17 ± 4.18 |
| `lanjian/day_06 input-kcen` | 1.0 ± 1.2 | 0.0 | 14.7 | 2.05 ± 4.22 |
| `lanjian/day_06 input-lanjian` | 2.2 ± 3.6 | 0.0 | 28.8 | 4.34 ± 10.10 |
| `lanjian/day_06 input-mattcl` | 1.2 ± 1.3 | 0.0 | 15.3 | 2.43 ± 4.82 |
| `lanjian/day_06 input-pting` | 0.5 ± 0.8 | 0.0 | 10.2 | 1.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 1.6 ± 1.0 | 0.0 | 7.5 | 3.10 ± 5.55 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.2 ± 1.0 | 0.0 | 11.5 | 2.44 ± 4.53 |
| `mattcl-solver/aoc run 6 input-lanjian` | 5.0 ± 6.6 | 0.0 | 49.0 | 9.97 ± 21.07 |
| `mattcl-solver/aoc run 6 input-mattcl` | 1.5 ± 1.3 | 0.0 | 10.9 | 3.00 ± 5.64 |
| `mattcl-solver/aoc run 6 input-pting` | 0.8 ± 0.9 | 0.0 | 8.0 | 1.50 ± 3.12 |
| `python pting/day06.py input-aspidites` | 53.6 ± 8.0 | 40.5 | 84.6 | 105.90 ± 177.29 |
| `python pting/day06.py input-kcen` | 52.9 ± 8.5 | 37.9 | 83.6 | 104.51 ± 175.07 |
| `python pting/day06.py input-lanjian` | 51.1 ± 8.0 | 40.1 | 80.3 | 101.05 ± 169.24 |
| `python pting/day06.py input-mattcl` | 56.3 ± 6.4 | 46.1 | 72.5 | 111.19 ± 185.84 |
| `python pting/day06.py input-pting` | 50.3 ± 6.0 | 41.3 | 68.6 | 99.39 ± 166.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
