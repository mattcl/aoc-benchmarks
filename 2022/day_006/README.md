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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 24.7 ± 2.6 | 12.8 | 38.1 | 19.44 ± 16.88 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 25.3 ± 3.9 | 13.5 | 44.2 | 19.93 ± 17.46 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 24.0 ± 1.0 | 22.6 | 28.9 | 18.92 ± 16.33 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 18.4 ± 5.4 | 12.4 | 26.4 | 14.47 ± 13.19 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.1 ± 3.0 | 16.9 | 38.4 | 19.78 ± 17.21 |
| `kcen/2022/06/solve input-aspidites` | 275.4 ± 114.4 | 149.9 | 470.2 | 217.06 ± 207.65 |
| `kcen/2022/06/solve input-kcen` | 174.8 ± 21.6 | 142.7 | 223.2 | 137.77 ± 119.95 |
| `kcen/2022/06/solve input-lanjian` | 156.0 ± 14.8 | 136.1 | 191.0 | 123.00 ± 106.65 |
| `kcen/2022/06/solve input-mattcl` | 174.9 ± 23.4 | 139.3 | 222.7 | 137.88 ± 120.24 |
| `kcen/2022/06/solve input-pting` | 174.0 ± 22.8 | 144.6 | 220.2 | 137.17 ± 119.58 |
| `lanjian/day_06 input-aspidites` | 2.0 ± 0.9 | 0.1 | 8.8 | 1.54 ± 1.50 |
| `lanjian/day_06 input-kcen` | 1.3 ± 1.1 | 0.0 | 12.8 | 1.00 |
| `lanjian/day_06 input-lanjian` | 1.6 ± 1.0 | 0.2 | 11.8 | 1.24 ± 1.35 |
| `lanjian/day_06 input-mattcl` | 1.9 ± 0.8 | 0.4 | 9.2 | 1.52 ± 1.46 |
| `lanjian/day_06 input-pting` | 1.5 ± 0.7 | 0.2 | 4.5 | 1.15 ± 1.14 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.0 ± 0.9 | 0.5 | 7.7 | 1.58 ± 1.54 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.3 ± 1.3 | 0.5 | 11.7 | 1.84 ± 1.88 |
| `mattcl-solver/aoc run 6 input-lanjian` | 1.8 ± 0.9 | 0.2 | 5.5 | 1.40 ± 1.40 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.6 ± 2.2 | 0.1 | 25.0 | 2.04 ± 2.46 |
| `mattcl-solver/aoc run 6 input-pting` | 2.6 ± 1.9 | 0.7 | 19.2 | 2.05 ± 2.30 |
| `python pting/day06.py input-aspidites` | 52.2 ± 5.6 | 41.9 | 67.0 | 41.11 ± 35.70 |
| `python pting/day06.py input-kcen` | 54.4 ± 7.3 | 41.1 | 69.4 | 42.90 ± 37.42 |
| `python pting/day06.py input-lanjian` | 56.0 ± 9.2 | 41.4 | 91.6 | 44.17 ± 38.75 |
| `python pting/day06.py input-mattcl` | 54.6 ± 8.3 | 44.0 | 87.0 | 43.05 ± 37.67 |
| `python pting/day06.py input-pting` | 52.4 ± 7.9 | 42.4 | 88.7 | 41.32 ± 36.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
