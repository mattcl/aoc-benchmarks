# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 3)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.2 ± 1.1 | 11.6 | 22.9 | 12.56 ± 4.84 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.2 ± 3.3 | 12.2 | 27.4 | 14.68 ± 6.46 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.1 ± 2.0 | 11.7 | 24.7 | 13.48 ± 5.45 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.6 ± 1.8 | 11.6 | 24.4 | 13.00 ± 5.20 |
| `aspidites-solver/aoc -i input-pting -d 3` | 14.7 ± 3.5 | 12.1 | 25.3 | 15.14 ± 6.74 |
| `kcen/2022/03/solve input-aspidites` | 227.3 ± 9.8 | 214.8 | 247.1 | 234.80 ± 88.57 |
| `kcen/2022/03/solve input-kcen` | 260.9 ± 18.8 | 226.5 | 285.6 | 269.48 ± 102.82 |
| `kcen/2022/03/solve input-lanjian` | 242.5 ± 10.9 | 230.4 | 265.9 | 250.50 ± 94.53 |
| `kcen/2022/03/solve input-mattcl` | 213.0 ± 10.8 | 199.7 | 235.4 | 220.01 ± 83.19 |
| `kcen/2022/03/solve input-pting` | 256.6 ± 30.1 | 225.2 | 305.7 | 265.00 ± 104.04 |
| `lanjian/day_03 input-aspidites` | 1.2 ± 0.7 | 0.6 | 8.9 | 1.27 ± 0.90 |
| `lanjian/day_03 input-kcen` | 1.6 ± 0.7 | 0.7 | 11.7 | 1.61 ± 0.95 |
| `lanjian/day_03 input-lanjian` | 1.0 ± 0.3 | 0.7 | 10.0 | 1.07 ± 0.54 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.4 | 0.7 | 3.8 | 1.28 ± 0.60 |
| `lanjian/day_03 input-pting` | 1.0 ± 0.4 | 0.6 | 8.4 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.2 ± 0.5 | 0.7 | 7.5 | 1.28 ± 0.70 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.9 ± 0.7 | 0.8 | 8.0 | 1.96 ± 1.03 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.3 ± 0.7 | 0.7 | 11.3 | 1.36 ± 0.89 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.3 ± 0.4 | 0.7 | 5.1 | 1.37 ± 0.65 |
| `mattcl-solver/aoc run 3 input-pting` | 1.1 ± 0.3 | 0.7 | 8.0 | 1.14 ± 0.54 |
| `python pting/day03.py input-aspidites` | 32.4 ± 3.4 | 27.8 | 43.5 | 33.49 ± 13.03 |
| `python pting/day03.py input-kcen` | 37.4 ± 4.1 | 31.2 | 48.8 | 38.62 ± 15.07 |
| `python pting/day03.py input-lanjian` | 32.7 ± 2.9 | 27.7 | 44.5 | 33.73 ± 12.98 |
| `python pting/day03.py input-mattcl` | 36.7 ± 8.4 | 28.6 | 73.8 | 37.90 ± 16.64 |
| `python pting/day03.py input-pting` | 36.7 ± 5.9 | 27.8 | 55.8 | 37.91 ± 15.46 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
