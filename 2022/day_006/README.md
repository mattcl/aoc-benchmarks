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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 19.8 ± 5.8 | 12.8 | 33.4 | 11.49 ± 6.64 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 17.5 ± 5.5 | 12.6 | 28.2 | 10.13 ± 5.95 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.0 ± 1.8 | 14.7 | 38.2 | 14.51 ± 7.29 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 18.3 ± 5.5 | 12.7 | 30.3 | 10.62 ± 6.15 |
| `aspidites-solver/aoc -i input-pting -d 6` | 20.2 ± 5.6 | 12.5 | 27.5 | 11.70 ± 6.67 |
| `kcen/2022/06/solve input-aspidites` | 159.2 ± 17.6 | 138.3 | 202.7 | 92.26 ± 46.98 |
| `kcen/2022/06/solve input-kcen` | 160.5 ± 16.0 | 134.0 | 192.7 | 92.99 ± 47.14 |
| `kcen/2022/06/solve input-lanjian` | 171.9 ± 13.7 | 140.9 | 191.8 | 99.59 ± 50.13 |
| `kcen/2022/06/solve input-mattcl` | 153.8 ± 9.6 | 141.2 | 177.7 | 89.10 ± 44.64 |
| `kcen/2022/06/solve input-pting` | 156.5 ± 14.4 | 130.5 | 185.4 | 90.69 ± 45.84 |
| `lanjian/day_06 input-aspidites` | 1.7 ± 0.9 | 0.6 | 8.6 | 1.00 |
| `lanjian/day_06 input-kcen` | 2.2 ± 0.9 | 0.7 | 12.4 | 1.28 ± 0.82 |
| `lanjian/day_06 input-lanjian` | 2.0 ± 0.7 | 0.7 | 5.1 | 1.18 ± 0.72 |
| `lanjian/day_06 input-mattcl` | 1.8 ± 0.8 | 0.7 | 5.7 | 1.04 ± 0.68 |
| `lanjian/day_06 input-pting` | 2.3 ± 1.0 | 0.8 | 8.6 | 1.34 ± 0.87 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.2 ± 2.1 | 0.8 | 56.4 | 1.25 ± 1.36 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.7 ± 1.1 | 0.9 | 11.3 | 1.54 ± 1.00 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.3 ± 0.9 | 0.9 | 10.6 | 1.33 ± 0.83 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.7 ± 1.1 | 1.0 | 10.0 | 1.58 ± 1.02 |
| `mattcl-solver/aoc run 6 input-pting` | 2.5 ± 1.0 | 0.8 | 10.2 | 1.47 ± 0.94 |
| `python pting/day06.py input-aspidites` | 51.8 ± 6.7 | 42.2 | 71.1 | 30.00 ± 15.41 |
| `python pting/day06.py input-kcen` | 48.6 ± 5.7 | 40.9 | 76.2 | 28.17 ± 14.39 |
| `python pting/day06.py input-lanjian` | 52.1 ± 6.4 | 41.3 | 72.8 | 30.20 ± 15.47 |
| `python pting/day06.py input-mattcl` | 61.0 ± 28.9 | 38.1 | 148.1 | 35.35 ± 24.28 |
| `python pting/day06.py input-pting` | 48.3 ± 6.4 | 36.7 | 62.6 | 27.97 ± 14.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
