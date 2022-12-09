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
| `aspidites-solver/aoc -i input-aspidites -d 6` | 24.2 ± 4.9 | 12.7 | 38.0 | 16.17 ± 8.71 |
| `aspidites-solver/aoc -i input-kcen -d 6` | 22.4 ± 4.8 | 12.6 | 27.8 | 15.01 ± 8.15 |
| `aspidites-solver/aoc -i input-lanjian -d 6` | 25.3 ± 2.7 | 22.9 | 40.4 | 16.92 ± 8.61 |
| `aspidites-solver/aoc -i input-mattcl -d 6` | 17.9 ± 5.9 | 12.6 | 37.0 | 11.95 ± 7.13 |
| `aspidites-solver/aoc -i input-pting -d 6` | 25.5 ± 3.3 | 13.2 | 41.4 | 17.07 ± 8.78 |
| `kcen/2022/06/solve input-aspidites` | 171.6 ± 17.7 | 146.2 | 207.5 | 114.81 ± 58.39 |
| `kcen/2022/06/solve input-kcen` | 199.6 ± 46.7 | 145.1 | 317.2 | 133.55 ± 73.49 |
| `kcen/2022/06/solve input-lanjian` | 174.7 ± 20.3 | 146.1 | 212.0 | 116.89 ± 59.77 |
| `kcen/2022/06/solve input-mattcl` | 190.5 ± 19.7 | 152.5 | 213.4 | 127.45 ± 64.82 |
| `kcen/2022/06/solve input-pting` | 156.1 ± 15.3 | 134.6 | 198.2 | 104.46 ± 53.02 |
| `lanjian/day_06 input-aspidites` | 2.1 ± 0.9 | 0.5 | 6.5 | 1.39 ± 0.94 |
| `lanjian/day_06 input-kcen` | 2.4 ± 1.0 | 0.5 | 9.4 | 1.61 ± 1.02 |
| `lanjian/day_06 input-lanjian` | 2.4 ± 1.2 | 0.6 | 13.2 | 1.58 ± 1.10 |
| `lanjian/day_06 input-mattcl` | 2.0 ± 1.2 | 0.5 | 15.5 | 1.34 ± 1.06 |
| `lanjian/day_06 input-pting` | 1.5 ± 0.7 | 0.5 | 5.0 | 1.00 |
| `mattcl-solver/aoc run 6 input-aspidites` | 2.5 ± 1.1 | 0.6 | 12.5 | 1.65 ± 1.11 |
| `mattcl-solver/aoc run 6 input-kcen` | 6.4 ± 5.0 | 1.7 | 36.6 | 4.28 ± 3.98 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.6 ± 1.2 | 0.8 | 8.1 | 1.74 ± 1.20 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.9 ± 1.3 | 1.0 | 10.8 | 1.95 ± 1.29 |
| `mattcl-solver/aoc run 6 input-pting` | 2.6 ± 1.2 | 0.8 | 10.1 | 1.73 ± 1.16 |
| `python pting/day06.py input-aspidites` | 57.4 ± 23.0 | 42.7 | 199.5 | 38.40 ± 24.57 |
| `python pting/day06.py input-kcen` | 51.3 ± 7.6 | 39.2 | 82.1 | 34.34 ± 17.84 |
| `python pting/day06.py input-lanjian` | 81.5 ± 25.0 | 45.1 | 142.7 | 54.54 ± 31.90 |
| `python pting/day06.py input-mattcl` | 57.7 ± 20.1 | 42.5 | 160.2 | 38.62 ± 23.47 |
| `python pting/day06.py input-pting` | 53.1 ± 16.5 | 42.6 | 164.5 | 35.54 ± 20.85 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-aspidites|<pre>1760</pre>|<pre>2974</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
|input-kcen|<pre>1794</pre>|<pre>2851</pre>|
