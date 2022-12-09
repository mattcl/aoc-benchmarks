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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 23.7 ± 7.1 | 12.7 | 49.3 | 13.32 ± 7.70 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 21.1 ± 6.6 | 12.8 | 52.1 | 11.88 ± 6.93 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.3 ± 4.5 | 23.2 | 48.3 | 14.78 ± 7.73 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 18.5 ± 5.6 | 12.5 | 38.2 | 10.39 ± 6.00 |
| `aspidites-solver/aoc -i input-pting -d 6` | 23.3 ± 4.4 | 12.4 | 35.1 | 13.12 ± 6.93 |
| `kcen/2022/06/solve input-aspidites` | 170.1 ± 23.8 | 143.1 | 246.4 | 95.64 ± 49.07 |
| `kcen/2022/06/solve input-kcen` | 190.6 ± 28.2 | 162.7 | 270.3 | 107.16 ± 55.22 |
| `kcen/2022/06/solve input-lanjian` | 182.2 ± 35.0 | 150.3 | 267.2 | 102.44 ± 54.26 |
| `kcen/2022/06/solve input-mattcl` | 154.1 ± 14.8 | 134.2 | 185.4 | 86.60 ± 43.55 |
| `kcen/2022/06/solve input-pting` | 176.4 ± 31.8 | 142.6 | 275.5 | 99.15 ± 52.10 |
| `lanjian/day_06 input-aspidites` | 1.8 ± 0.9 | 0.4 | 6.7 | 1.00 |
| `lanjian/day_06 input-kcen` | 1.9 ± 1.1 | 0.5 | 14.2 | 1.06 ± 0.83 |
| `lanjian/day_06 input-lanjian` | 2.0 ± 1.3 | 0.5 | 18.5 | 1.12 ± 0.90 |
| `lanjian/day_06 input-mattcl` | 2.0 ± 1.0 | 0.3 | 8.8 | 1.10 ± 0.78 |
| `lanjian/day_06 input-pting` | 4.9 ± 6.8 | 0.5 | 73.4 | 2.77 ± 4.05 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.1 ± 1.0 | 0.6 | 10.2 | 1.18 ± 0.79 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.1 ± 0.9 | 0.7 | 9.4 | 1.16 ± 0.77 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.2 ± 0.9 | 0.8 | 6.3 | 1.22 ± 0.77 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.5 ± 1.2 | 0.6 | 10.8 | 1.39 ± 0.97 |
| `mattcl-solver/aoc run 6 input-pting` | 2.4 ± 1.2 | 0.6 | 10.1 | 1.35 ± 0.97 |
| `python pting/day06.py input-aspidites` | 54.6 ± 7.5 | 43.2 | 76.0 | 30.71 ± 15.74 |
| `python pting/day06.py input-kcen` | 51.1 ± 17.8 | 38.0 | 141.8 | 28.73 ± 17.36 |
| `python pting/day06.py input-lanjian` | 52.7 ± 13.5 | 39.2 | 102.9 | 29.61 ± 16.46 |
| `python pting/day06.py input-mattcl` | 54.4 ± 13.6 | 40.2 | 117.3 | 30.60 ± 16.94 |
| `python pting/day06.py input-pting` | 53.0 ± 6.6 | 43.3 | 69.3 | 29.77 ± 15.16 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
