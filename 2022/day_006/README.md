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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 23.9 ± 3.7 | 12.7 | 28.6 | 12.92 ± 10.56 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 24.6 ± 3.5 | 12.7 | 35.9 | 13.29 ± 10.84 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.2 ± 2.6 | 23.1 | 43.4 | 13.66 ± 11.06 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 22.8 ± 4.9 | 13.0 | 30.8 | 12.37 ± 10.27 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.7 ± 4.4 | 23.5 | 50.7 | 14.44 ± 11.83 |
| `kcen/2022/06/solve input-aspidites` | 168.2 ± 11.5 | 152.1 | 188.8 | 91.03 ± 73.36 |
| `kcen/2022/06/solve input-kcen` | 181.3 ± 14.2 | 148.8 | 205.0 | 98.16 ± 79.19 |
| `kcen/2022/06/solve input-lanjian` | 166.5 ± 11.1 | 149.4 | 184.8 | 90.11 ± 72.60 |
| `kcen/2022/06/solve input-mattcl` | 176.2 ± 11.6 | 152.7 | 196.9 | 95.36 ± 76.83 |
| `kcen/2022/06/solve input-pting` | 306.2 ± 183.3 | 149.8 | 632.3 | 165.73 ± 166.00 |
| `lanjian/day_06 input-aspidites` | 2.2 ± 1.9 | 0.2 | 26.1 | 1.18 ± 1.41 |
| `lanjian/day_06 input-kcen` | 1.8 ± 1.5 | 0.1 | 20.4 | 1.00 |
| `lanjian/day_06 input-lanjian` | 5.6 ± 10.8 | 0.4 | 99.0 | 3.01 ± 6.30 |
| `lanjian/day_06 input-mattcl` | 2.0 ± 1.4 | 0.2 | 16.8 | 1.08 ± 1.16 |
| `lanjian/day_06 input-pting` | 3.0 ± 2.5 | 0.4 | 22.3 | 1.61 ± 1.85 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.2 ± 1.4 | 0.5 | 20.2 | 1.21 ± 1.25 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.2 ± 1.4 | 0.6 | 16.3 | 1.17 ± 1.20 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.6 ± 1.2 | 0.8 | 8.1 | 1.42 ± 1.30 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.3 ± 1.3 | 0.3 | 14.4 | 1.27 ± 1.23 |
| `mattcl-solver/aoc run 6 input-pting` | 3.2 ± 2.1 | 0.7 | 19.7 | 1.73 ± 1.78 |
| `python pting/day06.py input-aspidites` | 54.9 ± 7.5 | 40.3 | 72.6 | 29.73 ± 24.21 |
| `python pting/day06.py input-kcen` | 58.9 ± 7.9 | 45.0 | 77.1 | 31.88 ± 25.96 |
| `python pting/day06.py input-lanjian` | 59.2 ± 8.4 | 45.5 | 79.0 | 32.02 ± 26.12 |
| `python pting/day06.py input-mattcl` | 51.0 ± 5.9 | 42.0 | 68.9 | 27.60 ± 22.39 |
| `python pting/day06.py input-pting` | 58.7 ± 6.5 | 45.8 | 79.4 | 31.79 ± 25.77 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
