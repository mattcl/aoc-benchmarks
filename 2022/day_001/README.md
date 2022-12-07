# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 1)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.9 ± 3.8 | 11.5 | 53.3 | 12.02 ± 10.66 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.3 ± 2.5 | 11.9 | 29.1 | 12.38 ± 10.68 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 27.1 ± 23.6 | 11.4 | 153.9 | 23.43 ± 28.40 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.2 ± 3.7 | 11.3 | 45.9 | 12.32 ± 10.89 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.1 ± 2.2 | 10.8 | 28.4 | 12.17 ± 10.45 |
| `kcen/2022/01/solve input-aspidites` | 141.7 ± 28.2 | 111.1 | 204.3 | 122.54 ± 106.33 |
| `kcen/2022/01/solve input-kcen` | 283.7 ± 106.2 | 147.0 | 445.4 | 245.33 ± 226.65 |
| `kcen/2022/01/solve input-lanjian` | 145.1 ± 15.8 | 122.8 | 175.6 | 125.44 ± 106.83 |
| `kcen/2022/01/solve input-mattcl` | 152.9 ± 24.3 | 113.7 | 200.2 | 132.20 ± 113.62 |
| `kcen/2022/01/solve input-pting` | 161.1 ± 12.4 | 129.6 | 183.3 | 139.28 ± 118.13 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 3.6 | 0.0 | 71.0 | 1.53 ± 3.33 |
| `lanjian/day_01 input-kcen` | 1.4 ± 1.1 | 0.0 | 6.2 | 1.18 ± 1.37 |
| `lanjian/day_01 input-lanjian` | 2.3 ± 1.5 | 0.1 | 13.0 | 2.00 ± 2.11 |
| `lanjian/day_01 input-mattcl` | 2.0 ± 1.9 | 0.0 | 29.4 | 1.70 ± 2.19 |
| `lanjian/day_01 input-pting` | 2.1 ± 1.5 | 0.0 | 14.5 | 1.84 ± 2.05 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 1.0 | 0.0 | 10.7 | 1.27 ± 1.39 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.9 ± 1.1 | 0.0 | 8.9 | 1.65 ± 1.71 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.4 ± 1.2 | 0.1 | 9.4 | 2.04 ± 2.03 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.8 ± 1.2 | 0.0 | 8.0 | 1.56 ± 1.67 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 1.0 | 0.0 | 7.7 | 1.00 |
| `python pting/day01.py input-aspidites` | 48.4 ± 9.4 | 34.3 | 90.1 | 41.90 ± 36.31 |
| `python pting/day01.py input-kcen` | 49.2 ± 7.3 | 38.6 | 72.3 | 42.52 ± 36.46 |
| `python pting/day01.py input-lanjian` | 44.2 ± 7.3 | 32.6 | 62.5 | 38.20 ± 32.87 |
| `python pting/day01.py input-mattcl` | 48.2 ± 8.9 | 34.6 | 81.8 | 41.64 ± 36.01 |
| `python pting/day01.py input-pting` | 50.1 ± 7.2 | 36.8 | 66.2 | 43.31 ± 37.10 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
