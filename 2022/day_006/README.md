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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.1 ± 1.7 | 13.0 | 30.7 | 14.40 ± 6.49 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 24.4 ± 3.1 | 12.6 | 41.0 | 14.03 ± 6.49 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 27.7 ± 5.4 | 23.9 | 49.3 | 15.90 ± 7.73 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.7 ± 6.0 | 12.9 | 65.4 | 13.64 ± 6.97 |
| `aspidites-solver/aoc -i input-pting -d 6` | 26.2 ± 3.8 | 23.1 | 46.0 | 15.07 ± 7.06 |
| `kcen/2022/06/solve input-aspidites` | 189.3 ± 23.0 | 156.6 | 223.1 | 108.77 ± 50.21 |
| `kcen/2022/06/solve input-kcen` | 186.9 ± 16.7 | 154.5 | 222.2 | 107.39 ± 48.77 |
| `kcen/2022/06/solve input-lanjian` | 219.8 ± 19.3 | 185.9 | 253.4 | 126.31 ± 57.34 |
| `kcen/2022/06/solve input-mattcl` | 184.0 ± 19.2 | 156.1 | 229.6 | 105.69 ± 48.34 |
| `kcen/2022/06/solve input-pting` | 194.6 ± 24.3 | 154.6 | 261.6 | 111.80 ± 51.71 |
| `lanjian/day_06 input-aspidites` | 2.5 ± 1.0 | 0.9 | 14.5 | 1.42 ± 0.87 |
| `lanjian/day_06 input-kcen` | 1.9 ± 1.0 | 0.5 | 8.1 | 1.10 ± 0.75 |
| `lanjian/day_06 input-lanjian` | 1.7 ± 0.8 | 0.2 | 5.3 | 1.00 |
| `lanjian/day_06 input-mattcl` | 2.8 ± 1.5 | 0.9 | 12.6 | 1.62 ± 1.10 |
| `lanjian/day_06 input-pting` | 2.2 ± 1.1 | 0.2 | 15.3 | 1.25 ± 0.83 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.5 ± 1.0 | 1.1 | 12.2 | 1.45 ± 0.87 |
| `mattcl-solver/aoc run 6 input-kcen` | 3.5 ± 1.4 | 1.2 | 13.6 | 2.00 ± 1.21 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.2 ± 0.9 | 0.7 | 6.5 | 1.25 ± 0.76 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.8 ± 1.1 | 1.1 | 11.4 | 1.61 ± 0.94 |
| `mattcl-solver/aoc run 6 input-pting` | 2.5 ± 1.5 | 0.7 | 25.8 | 1.45 ± 1.07 |
| `python pting/day06.py input-aspidites` | 57.7 ± 6.0 | 46.9 | 70.3 | 33.15 ± 15.15 |
| `python pting/day06.py input-kcen` | 59.2 ± 7.7 | 40.8 | 76.4 | 33.99 ± 15.76 |
| `python pting/day06.py input-lanjian` | 74.4 ± 28.9 | 42.9 | 193.4 | 42.73 ± 25.27 |
| `python pting/day06.py input-mattcl` | 55.4 ± 6.8 | 45.6 | 71.1 | 31.84 ± 14.71 |
| `python pting/day06.py input-pting` | 54.5 ± 6.8 | 44.8 | 72.8 | 31.30 ± 14.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
