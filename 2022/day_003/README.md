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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 23.2 ± 5.1 | 13.0 | 37.6 | 12.78 ± 8.39 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 23.6 ± 4.7 | 13.0 | 35.9 | 13.02 ± 8.46 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 26.1 ± 1.8 | 23.9 | 35.3 | 14.36 ± 8.94 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 24.3 ± 4.5 | 13.3 | 41.4 | 13.38 ± 8.64 |
| `aspidites-solver/aoc -i input-pting -d 3` | 24.7 ± 4.1 | 12.8 | 35.6 | 13.60 ± 8.71 |
| `kcen/2022/03/solve input-aspidites` | 370.2 ± 33.1 | 313.8 | 418.5 | 203.90 ± 127.48 |
| `kcen/2022/03/solve input-kcen` | 378.7 ± 36.1 | 337.6 | 449.0 | 208.55 ± 130.56 |
| `kcen/2022/03/solve input-lanjian` | 415.4 ± 42.0 | 348.4 | 461.9 | 228.76 ± 143.42 |
| `kcen/2022/03/solve input-mattcl` | 363.4 ± 43.7 | 323.4 | 445.0 | 200.12 ± 126.15 |
| `kcen/2022/03/solve input-pting` | 358.4 ± 29.4 | 320.4 | 417.6 | 197.41 ± 123.22 |
| `lanjian/day_03 input-aspidites` | 4.6 ± 4.7 | 0.8 | 33.1 | 2.55 ± 3.03 |
| `lanjian/day_03 input-kcen` | 1.9 ± 1.1 | 0.6 | 12.4 | 1.06 ± 0.88 |
| `lanjian/day_03 input-lanjian` | 2.4 ± 1.1 | 0.7 | 11.1 | 1.32 ± 1.02 |
| `lanjian/day_03 input-mattcl` | 2.0 ± 1.0 | 0.6 | 9.6 | 1.09 ± 0.89 |
| `lanjian/day_03 input-pting` | 1.8 ± 1.1 | 0.6 | 13.3 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 2.6 ± 1.4 | 0.7 | 16.0 | 1.43 ± 1.18 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.5 ± 1.0 | 0.6 | 9.0 | 1.36 ± 1.01 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.9 ± 1.7 | 0.8 | 16.5 | 1.58 ± 1.36 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.8 ± 1.3 | 0.7 | 10.5 | 1.52 ± 1.17 |
| `mattcl-solver/aoc run 3 input-pting` | 2.5 ± 1.4 | 0.7 | 17.1 | 1.37 ± 1.13 |
| `python pting/day03.py input-aspidites` | 54.7 ± 9.8 | 38.7 | 87.2 | 30.14 ± 19.42 |
| `python pting/day03.py input-kcen` | 58.5 ± 9.3 | 45.2 | 80.4 | 32.20 ± 20.57 |
| `python pting/day03.py input-lanjian` | 56.9 ± 9.0 | 41.9 | 79.9 | 31.32 ± 20.00 |
| `python pting/day03.py input-mattcl` | 56.2 ± 9.2 | 44.5 | 87.6 | 30.98 ± 19.83 |
| `python pting/day03.py input-pting` | 54.2 ± 9.0 | 43.2 | 83.1 | 29.85 ± 19.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
