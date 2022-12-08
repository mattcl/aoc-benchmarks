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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 22.4 ± 4.7 | 12.8 | 28.7 | 15.25 ± 9.78 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 18.4 ± 5.6 | 12.6 | 27.3 | 12.56 ± 8.52 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.9 ± 4.1 | 23.7 | 49.6 | 18.33 ± 11.44 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 20.5 ± 5.9 | 12.8 | 37.2 | 13.97 ± 9.38 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.5 ± 4.4 | 23.3 | 54.4 | 17.37 ± 10.94 |
| `kcen/2022/06/solve input-aspidites` | 173.5 ± 16.1 | 152.2 | 201.7 | 118.30 ± 72.48 |
| `kcen/2022/06/solve input-kcen` | 168.2 ± 16.4 | 142.7 | 193.9 | 114.68 ± 70.35 |
| `kcen/2022/06/solve input-lanjian` | 193.3 ± 26.0 | 158.1 | 234.2 | 131.76 ± 81.74 |
| `kcen/2022/06/solve input-mattcl` | 178.0 ± 17.4 | 153.7 | 218.0 | 121.36 ± 74.45 |
| `kcen/2022/06/solve input-pting` | 157.8 ± 14.9 | 138.6 | 191.3 | 107.59 ± 65.94 |
| `lanjian/day_06 input-aspidites` | 1.9 ± 2.6 | 0.4 | 38.4 | 1.31 ± 1.97 |
| `lanjian/day_06 input-kcen` | 1.5 ± 0.9 | 0.2 | 9.0 | 1.00 |
| `lanjian/day_06 input-lanjian` | 2.8 ± 1.5 | 0.7 | 18.9 | 1.91 ± 1.53 |
| `lanjian/day_06 input-mattcl` | 2.2 ± 1.1 | 0.6 | 12.9 | 1.48 ± 1.17 |
| `lanjian/day_06 input-pting` | 1.5 ± 1.3 | 0.3 | 22.1 | 1.03 ± 1.10 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.1 ± 1.1 | 0.6 | 13.6 | 1.44 ± 1.17 |
| `mattcl-solver/aoc run 6 input-kcen` | 1.8 ± 0.9 | 0.5 | 13.9 | 1.21 ± 0.96 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.3 ± 1.7 | 1.1 | 17.5 | 2.28 ± 1.80 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.9 ± 1.4 | 0.9 | 12.3 | 1.96 ± 1.53 |
| `mattcl-solver/aoc run 6 input-pting` | 2.7 ± 1.3 | 0.9 | 14.5 | 1.84 ± 1.41 |
| `python pting/day06.py input-aspidites` | 102.2 ± 53.8 | 47.0 | 217.3 | 69.65 ± 55.91 |
| `python pting/day06.py input-kcen` | 50.8 ± 7.3 | 40.4 | 67.4 | 34.64 ± 21.56 |
| `python pting/day06.py input-lanjian` | 57.0 ± 8.8 | 44.6 | 91.2 | 38.85 ± 24.28 |
| `python pting/day06.py input-mattcl` | 51.3 ± 6.7 | 40.7 | 68.2 | 34.96 ± 21.66 |
| `python pting/day06.py input-pting` | 52.5 ± 5.0 | 42.0 | 62.8 | 35.82 ± 21.96 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
