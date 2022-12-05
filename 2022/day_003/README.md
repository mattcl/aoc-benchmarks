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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.7 ± 2.2 | 11.7 | 25.4 | 12.38 ± 5.22 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.3 ± 2.6 | 11.8 | 25.2 | 12.99 ± 5.62 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.7 ± 1.1 | 11.8 | 22.5 | 12.40 ± 4.89 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.4 ± 3.7 | 11.7 | 47.6 | 13.15 ± 6.18 |
| `aspidites-solver/aoc -i input-pting -d 3` | 14.3 ± 3.2 | 11.9 | 24.9 | 13.94 ± 6.22 |
| `kcen/2022/03/solve input-aspidites` | 234.8 ± 20.4 | 214.0 | 289.1 | 229.50 ± 90.39 |
| `kcen/2022/03/solve input-kcen` | 249.1 ± 9.8 | 236.9 | 269.5 | 243.54 ± 94.04 |
| `kcen/2022/03/solve input-lanjian` | 242.3 ± 10.9 | 224.4 | 256.1 | 236.87 ± 91.61 |
| `kcen/2022/03/solve input-mattcl` | 245.0 ± 14.9 | 217.6 | 265.9 | 239.52 ± 93.15 |
| `kcen/2022/03/solve input-pting` | 249.7 ± 16.1 | 229.7 | 274.2 | 244.13 ± 95.09 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.5 | 0.6 | 7.8 | 1.27 ± 0.66 |
| `lanjian/day_03 input-kcen` | 1.5 ± 0.6 | 0.6 | 10.1 | 1.45 ± 0.80 |
| `lanjian/day_03 input-lanjian` | 1.7 ± 0.8 | 0.7 | 6.7 | 1.65 ± 0.98 |
| `lanjian/day_03 input-mattcl` | 1.0 ± 0.4 | 0.6 | 7.5 | 1.00 |
| `lanjian/day_03 input-pting` | 1.5 ± 0.4 | 0.6 | 4.4 | 1.51 ± 0.72 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.5 ± 0.4 | 0.7 | 3.3 | 1.50 ± 0.70 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.4 ± 0.4 | 0.7 | 3.6 | 1.37 ± 0.66 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.5 ± 0.7 | 0.7 | 7.2 | 1.46 ± 0.86 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.4 ± 0.5 | 0.7 | 7.8 | 1.32 ± 0.68 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.5 | 0.7 | 4.0 | 1.29 ± 0.70 |
| `python pting/day03.py input-aspidites` | 32.6 ± 3.0 | 28.9 | 47.6 | 31.82 ± 12.58 |
| `python pting/day03.py input-kcen` | 36.8 ± 5.2 | 29.3 | 57.6 | 36.00 ± 14.74 |
| `python pting/day03.py input-lanjian` | 36.2 ± 4.6 | 30.3 | 52.4 | 35.40 ± 14.33 |
| `python pting/day03.py input-mattcl` | 34.4 ± 4.7 | 29.0 | 58.5 | 33.61 ± 13.70 |
| `python pting/day03.py input-pting` | 36.4 ± 4.3 | 30.2 | 51.8 | 35.60 ± 14.31 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
