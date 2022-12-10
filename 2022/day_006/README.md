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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 25.8 ± 3.1 | 23.2 | 41.9 | 14.33 ± 9.93 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 24.7 ± 1.5 | 22.9 | 37.0 | 13.73 ± 9.41 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 26.5 ± 4.1 | 23.3 | 43.8 | 14.76 ± 10.32 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 23.8 ± 5.8 | 12.9 | 48.2 | 13.26 ± 9.61 |
| `aspidites-solver/aoc -i input-pting -d 6` | 24.9 ± 1.5 | 22.4 | 34.9 | 13.85 ± 9.49 |
| `kcen/2022/06/solve input-aspidites` | 174.9 ± 20.1 | 147.8 | 214.8 | 97.28 ± 67.32 |
| `kcen/2022/06/solve input-kcen` | 175.9 ± 15.3 | 156.5 | 199.3 | 97.86 ± 67.32 |
| `kcen/2022/06/solve input-lanjian` | 197.6 ± 24.5 | 165.5 | 252.8 | 109.91 ± 76.22 |
| `kcen/2022/06/solve input-mattcl` | 188.9 ± 16.5 | 167.7 | 229.4 | 105.12 ± 72.31 |
| `kcen/2022/06/solve input-pting` | 185.0 ± 21.0 | 158.5 | 218.2 | 102.95 ± 71.21 |
| `lanjian/day_06 input-aspidites` | 1.8 ± 1.2 | 0.2 | 17.1 | 1.00 |
| `lanjian/day_06 input-kcen` | 1.8 ± 0.8 | 0.5 | 8.1 | 1.00 ± 0.82 |
| `lanjian/day_06 input-lanjian` | 2.9 ± 1.7 | 0.9 | 14.3 | 1.62 ± 1.47 |
| `lanjian/day_06 input-mattcl` | 2.4 ± 1.2 | 0.6 | 12.4 | 1.35 ± 1.14 |
| `lanjian/day_06 input-pting` | 1.9 ± 1.4 | 0.4 | 22.0 | 1.08 ± 1.06 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.7 ± 1.0 | 1.0 | 7.3 | 1.48 ± 1.14 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.6 ± 1.0 | 0.9 | 9.5 | 1.45 ± 1.12 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.0 ± 1.5 | 1.2 | 16.0 | 1.65 ± 1.39 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.4 ± 0.8 | 1.2 | 9.6 | 1.32 ± 1.00 |
| `mattcl-solver/aoc run 6 input-pting` | 2.6 ± 1.1 | 1.1 | 8.7 | 1.45 ± 1.16 |
| `python pting/day06.py input-aspidites` | 60.6 ± 7.9 | 47.5 | 81.2 | 33.70 ± 23.41 |
| `python pting/day06.py input-kcen` | 59.1 ± 9.0 | 47.1 | 87.9 | 32.88 ± 22.98 |
| `python pting/day06.py input-lanjian` | 66.0 ± 7.6 | 51.9 | 81.6 | 36.71 ± 25.40 |
| `python pting/day06.py input-mattcl` | 60.4 ± 11.7 | 46.0 | 111.3 | 33.62 ± 23.85 |
| `python pting/day06.py input-pting` | 56.5 ± 8.6 | 44.8 | 85.5 | 31.42 ± 21.96 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
