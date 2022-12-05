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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.6 ± 2.8 | 12.1 | 24.6 | 13.14 ± 5.88 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.4 ± 1.8 | 11.6 | 22.5 | 11.98 ± 5.07 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.5 ± 1.4 | 11.6 | 25.9 | 12.03 ± 4.98 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.7 ± 2.5 | 11.7 | 32.7 | 12.23 ± 5.43 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.0 ± 2.3 | 11.7 | 27.8 | 12.55 ± 5.47 |
| `kcen/2022/03/solve input-aspidites` | 241.3 ± 17.7 | 212.4 | 263.5 | 232.45 ± 94.12 |
| `kcen/2022/03/solve input-kcen` | 218.1 ± 11.6 | 206.0 | 251.6 | 210.09 ± 84.39 |
| `kcen/2022/03/solve input-lanjian` | 223.3 ± 12.2 | 202.8 | 245.8 | 215.13 ± 86.47 |
| `kcen/2022/03/solve input-mattcl` | 223.0 ± 12.5 | 199.9 | 240.6 | 214.83 ± 86.38 |
| `kcen/2022/03/solve input-pting` | 230.8 ± 12.2 | 209.6 | 250.8 | 222.36 ± 89.32 |
| `lanjian/day_03 input-aspidites` | 1.2 ± 0.4 | 0.6 | 3.2 | 1.16 ± 0.57 |
| `lanjian/day_03 input-kcen` | 1.0 ± 0.4 | 0.6 | 8.9 | 1.00 |
| `lanjian/day_03 input-lanjian` | 1.3 ± 0.4 | 0.6 | 3.8 | 1.27 ± 0.64 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.7 | 0.6 | 9.8 | 1.19 ± 0.84 |
| `lanjian/day_03 input-pting` | 1.4 ± 0.6 | 0.7 | 10.4 | 1.33 ± 0.77 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.3 ± 0.6 | 0.7 | 6.9 | 1.29 ± 0.78 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.2 ± 0.3 | 0.7 | 3.5 | 1.11 ± 0.55 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.5 | 0.7 | 15.3 | 1.37 ± 0.75 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.4 ± 0.7 | 0.7 | 7.2 | 1.31 ± 0.85 |
| `mattcl-solver/aoc run 3 input-pting` | 1.6 ± 0.4 | 0.7 | 5.8 | 1.56 ± 0.75 |
| `python pting/day03.py input-aspidites` | 33.5 ± 3.6 | 29.3 | 44.5 | 32.32 ± 13.33 |
| `python pting/day03.py input-kcen` | 33.8 ± 4.1 | 28.6 | 47.7 | 32.60 ± 13.57 |
| `python pting/day03.py input-lanjian` | 33.0 ± 3.6 | 29.0 | 43.5 | 31.84 ± 13.13 |
| `python pting/day03.py input-mattcl` | 31.3 ± 3.6 | 27.4 | 47.4 | 30.13 ± 12.48 |
| `python pting/day03.py input-pting` | 35.2 ± 3.9 | 29.2 | 43.6 | 33.91 ± 14.01 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
