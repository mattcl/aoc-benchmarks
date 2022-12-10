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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 22.5 ± 4.4 | 12.5 | 33.8 | 13.89 ± 7.87 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 19.5 ± 5.5 | 12.0 | 27.5 | 12.03 ± 7.23 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 21.5 ± 5.0 | 11.9 | 43.2 | 13.29 ± 7.72 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 20.0 ± 6.6 | 12.1 | 44.0 | 12.32 ± 7.72 |
| `aspidites-solver/aoc -i input-pting -d 6` | 24.0 ± 3.2 | 12.3 | 35.9 | 14.82 ± 8.13 |
| `kcen/2022/06/solve input-aspidites` | 163.2 ± 12.7 | 147.6 | 189.6 | 100.70 ± 54.13 |
| `kcen/2022/06/solve input-kcen` | 151.8 ± 16.9 | 129.0 | 207.4 | 93.69 ± 50.91 |
| `kcen/2022/06/solve input-lanjian` | 150.8 ± 13.6 | 134.4 | 185.7 | 93.06 ± 50.20 |
| `kcen/2022/06/solve input-mattcl` | 168.5 ± 21.7 | 141.3 | 213.4 | 103.99 ± 56.90 |
| `kcen/2022/06/solve input-pting` | 162.4 ± 14.8 | 145.1 | 191.7 | 100.20 ± 54.06 |
| `lanjian/day_06 input-aspidites` | 2.0 ± 1.3 | 0.4 | 11.2 | 1.25 ± 1.06 |
| `lanjian/day_06 input-kcen` | 1.6 ± 0.9 | 0.4 | 6.2 | 1.00 |
| `lanjian/day_06 input-lanjian` | 1.6 ± 1.0 | 0.4 | 9.1 | 1.01 ± 0.80 |
| `lanjian/day_06 input-mattcl` | 3.6 ± 3.7 | 0.4 | 37.2 | 2.23 ± 2.57 |
| `lanjian/day_06 input-pting` | 1.8 ± 1.0 | 0.3 | 7.3 | 1.13 ± 0.85 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.4 ± 1.2 | 0.7 | 9.1 | 1.46 ± 1.06 |
| `mattcl-solver/aoc run 6 input-kcen` | 2.5 ± 1.3 | 0.6 | 15.1 | 1.56 ± 1.17 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.2 ± 0.8 | 1.0 | 10.9 | 1.35 ± 0.89 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.3 ± 1.0 | 0.7 | 7.4 | 1.40 ± 0.97 |
| `mattcl-solver/aoc run 6 input-pting` | 1.9 ± 0.8 | 0.8 | 6.3 | 1.20 ± 0.80 |
| `python pting/day06.py input-aspidites` | 52.4 ± 4.7 | 44.9 | 69.5 | 32.34 ± 17.44 |
| `python pting/day06.py input-kcen` | 48.0 ± 5.4 | 38.9 | 66.8 | 29.64 ± 16.11 |
| `python pting/day06.py input-lanjian` | 51.0 ± 5.7 | 39.3 | 64.2 | 31.47 ± 17.11 |
| `python pting/day06.py input-mattcl` | 50.4 ± 6.8 | 38.1 | 73.5 | 31.12 ± 17.08 |
| `python pting/day06.py input-pting` | 53.7 ± 6.5 | 41.2 | 66.6 | 33.13 ± 18.07 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
