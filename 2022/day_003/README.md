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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.5 ± 2.9 | 11.7 | 24.8 | 10.18 ± 6.09 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.1 ± 3.5 | 11.9 | 26.8 | 10.65 ± 6.51 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.1 ± 2.6 | 11.9 | 24.3 | 9.87 ± 5.84 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.1 ± 2.7 | 11.6 | 32.8 | 9.91 ± 5.88 |
| `aspidites-solver/aoc -i input-pting -d 3` | 14.8 ± 4.5 | 11.7 | 32.5 | 11.19 ± 7.12 |
| `kcen/2022/03/solve input-aspidites` | 249.1 ± 28.5 | 213.7 | 314.4 | 188.18 ± 107.18 |
| `kcen/2022/03/solve input-kcen` | 276.8 ± 22.8 | 237.5 | 306.4 | 209.11 ± 117.94 |
| `kcen/2022/03/solve input-lanjian` | 239.3 ± 17.2 | 221.4 | 272.8 | 180.77 ± 101.69 |
| `kcen/2022/03/solve input-mattcl` | 237.0 ± 13.0 | 217.3 | 261.6 | 179.02 ± 100.37 |
| `kcen/2022/03/solve input-pting` | 255.6 ± 27.2 | 223.9 | 307.1 | 193.03 ± 109.65 |
| `lanjian/day_03 input-aspidites` | 1.8 ± 0.7 | 0.7 | 4.5 | 1.40 ± 0.93 |
| `lanjian/day_03 input-kcen` | 1.3 ± 0.7 | 0.6 | 11.9 | 1.00 |
| `lanjian/day_03 input-lanjian` | 1.7 ± 1.3 | 0.6 | 12.7 | 1.32 ± 1.22 |
| `lanjian/day_03 input-mattcl` | 1.5 ± 0.5 | 0.6 | 4.2 | 1.16 ± 0.76 |
| `lanjian/day_03 input-pting` | 1.5 ± 0.6 | 0.7 | 7.6 | 1.11 ± 0.77 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.6 ± 0.6 | 0.7 | 5.6 | 1.23 ± 0.83 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.8 ± 0.8 | 0.6 | 8.3 | 1.37 ± 0.98 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.9 ± 1.3 | 0.7 | 13.4 | 1.45 ± 1.25 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.6 ± 0.7 | 0.7 | 7.9 | 1.20 ± 0.87 |
| `mattcl-solver/aoc run 3 input-pting` | 1.6 ± 0.6 | 0.8 | 9.0 | 1.18 ± 0.81 |
| `python pting/day03.py input-aspidites` | 38.3 ± 6.7 | 29.5 | 65.1 | 28.92 ± 16.92 |
| `python pting/day03.py input-kcen` | 37.1 ± 7.1 | 27.6 | 57.4 | 27.99 ± 16.51 |
| `python pting/day03.py input-lanjian` | 34.6 ± 4.3 | 27.1 | 46.5 | 26.13 ± 14.95 |
| `python pting/day03.py input-mattcl` | 39.7 ± 8.1 | 29.5 | 65.2 | 30.02 ± 17.83 |
| `python pting/day03.py input-pting` | 36.1 ± 5.8 | 28.6 | 73.1 | 27.30 ± 15.86 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
