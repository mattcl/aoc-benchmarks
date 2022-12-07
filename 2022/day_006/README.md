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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 26.0 ± 3.3 | 23.4 | 46.6 | 13.92 ± 11.72 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 26.4 ± 5.0 | 12.8 | 45.6 | 14.15 ± 12.08 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.1 ± 3.3 | 23.3 | 42.7 | 13.98 ± 11.77 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 25.9 ± 3.5 | 13.2 | 43.0 | 13.88 ± 11.70 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.9 ± 4.4 | 23.8 | 49.7 | 14.43 ± 12.24 |
| `kcen/2022/06/solve input-aspidites` | 185.5 ± 20.9 | 160.8 | 235.0 | 99.47 ± 83.55 |
| `kcen/2022/06/solve input-kcen` | 212.6 ± 34.2 | 163.1 | 280.1 | 114.04 ± 96.68 |
| `kcen/2022/06/solve input-lanjian` | 221.1 ± 19.8 | 178.5 | 257.6 | 118.58 ± 99.27 |
| `kcen/2022/06/solve input-mattcl` | 190.3 ± 21.4 | 156.6 | 233.9 | 102.04 ± 85.71 |
| `kcen/2022/06/solve input-pting` | 192.7 ± 19.4 | 166.5 | 230.0 | 103.33 ± 86.64 |
| `lanjian/day_06 input-aspidites` | 2.2 ± 3.0 | 0.0 | 72.6 | 1.20 ± 1.91 |
| `lanjian/day_06 input-kcen` | 2.1 ± 1.4 | 0.1 | 9.3 | 1.10 ± 1.17 |
| `lanjian/day_06 input-lanjian` | 2.2 ± 1.2 | 0.3 | 9.5 | 1.17 ± 1.16 |
| `lanjian/day_06 input-mattcl` | 1.9 ± 1.6 | 0.1 | 15.9 | 1.00 |
| `lanjian/day_06 input-pting` | 2.0 ± 1.7 | 0.1 | 15.5 | 1.08 ± 1.30 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.6 ± 1.3 | 0.4 | 9.5 | 1.41 ± 1.36 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.5 ± 1.3 | 0.4 | 11.0 | 1.34 ± 1.31 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.2 ± 1.1 | 0.4 | 9.0 | 1.16 ± 1.14 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.4 ± 1.2 | 0.3 | 14.3 | 1.29 ± 1.26 |
| `mattcl-solver/aoc run 6 input-pting` | 2.2 ± 1.7 | 0.1 | 19.2 | 1.20 ± 1.35 |
| `python pting/day06.py input-aspidites` | 58.1 ± 8.6 | 44.6 | 81.5 | 31.14 ± 26.32 |
| `python pting/day06.py input-kcen` | 57.1 ± 7.5 | 46.5 | 80.9 | 30.64 ± 25.82 |
| `python pting/day06.py input-lanjian` | 56.7 ± 8.4 | 43.5 | 86.8 | 30.43 ± 25.73 |
| `python pting/day06.py input-mattcl` | 56.8 ± 11.1 | 41.8 | 80.3 | 30.47 ± 26.05 |
| `python pting/day06.py input-pting` | 85.3 ± 31.0 | 49.6 | 171.3 | 45.75 ± 41.55 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
