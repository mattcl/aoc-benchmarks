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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 15.4 ± 4.7 | 12.0 | 26.6 | 12.84 ± 8.51 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 20.9 ± 5.2 | 12.8 | 29.0 | 17.41 ± 11.11 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 21.0 ± 5.1 | 12.2 | 26.9 | 17.46 ± 11.11 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 20.3 ± 7.0 | 12.4 | 44.1 | 16.84 ± 11.47 |
| `aspidites-solver/aoc -i input-pting -d 6` | 19.7 ± 5.3 | 12.2 | 25.3 | 16.34 ± 10.56 |
| `kcen/2022/06/solve input-aspidites` | 125.8 ± 12.4 | 113.7 | 154.7 | 104.56 ± 62.35 |
| `kcen/2022/06/solve input-kcen` | 134.5 ± 9.6 | 120.2 | 153.8 | 111.80 ± 66.24 |
| `kcen/2022/06/solve input-lanjian` | 137.7 ± 12.7 | 116.8 | 175.0 | 114.51 ± 68.17 |
| `kcen/2022/06/solve input-mattcl` | 137.6 ± 11.6 | 117.4 | 161.1 | 114.39 ± 67.97 |
| `kcen/2022/06/solve input-pting` | 138.2 ± 14.7 | 119.3 | 180.3 | 114.87 ± 68.66 |
| `lanjian/day_06 input-aspidites` | 1.2 ± 0.7 | 0.3 | 5.6 | 1.00 |
| `lanjian/day_06 input-kcen` | 1.4 ± 1.1 | 0.2 | 30.8 | 1.17 ± 1.16 |
| `lanjian/day_06 input-lanjian` | 1.7 ± 0.7 | 0.3 | 5.8 | 1.39 ± 0.98 |
| `lanjian/day_06 input-mattcl` | 1.6 ± 0.7 | 0.2 | 8.2 | 1.31 ± 0.97 |
| `lanjian/day_06 input-pting` | 1.7 ± 2.2 | 0.3 | 38.6 | 1.39 ± 2.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.4 ± 1.3 | 0.8 | 11.8 | 2.00 ± 1.58 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.8 ± 0.8 | 0.6 | 7.2 | 1.47 ± 1.07 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.2 ± 0.9 | 0.6 | 11.5 | 1.84 ± 1.30 |
| `mattcl-solver/aoc run 6 input-mattcl` | 1.7 ± 0.7 | 0.5 | 5.9 | 1.40 ± 1.01 |
| `mattcl-solver/aoc run 6 input-pting` | 1.6 ± 0.7 | 0.5 | 7.1 | 1.36 ± 0.97 |
| `python pting/day06.py input-aspidites` | 41.3 ± 4.3 | 35.7 | 55.4 | 34.33 ± 20.50 |
| `python pting/day06.py input-kcen` | 40.6 ± 4.9 | 34.1 | 55.7 | 33.74 ± 20.26 |
| `python pting/day06.py input-lanjian` | 41.9 ± 3.9 | 34.7 | 51.3 | 34.87 ± 20.77 |
| `python pting/day06.py input-mattcl` | 40.7 ± 5.6 | 32.4 | 62.1 | 33.86 ± 20.46 |
| `python pting/day06.py input-pting` | 46.7 ± 6.8 | 35.2 | 64.3 | 38.82 ± 23.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
