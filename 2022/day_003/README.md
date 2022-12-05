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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.9 ± 3.2 | 11.8 | 26.7 | 13.09 ± 5.36 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.5 ± 1.3 | 11.6 | 23.1 | 11.83 ± 4.16 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.4 ± 2.0 | 12.3 | 24.1 | 12.61 ± 4.63 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.3 ± 3.0 | 11.8 | 39.1 | 12.51 ± 5.09 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.5 ± 1.5 | 11.7 | 26.1 | 11.78 ± 4.21 |
| `kcen/2022/03/solve input-aspidites` | 255.7 ± 21.9 | 206.9 | 292.5 | 241.24 ± 83.76 |
| `kcen/2022/03/solve input-kcen` | 229.9 ± 18.0 | 197.7 | 250.8 | 216.97 ± 74.95 |
| `kcen/2022/03/solve input-lanjian` | 247.3 ± 23.1 | 214.3 | 290.6 | 233.38 ± 81.48 |
| `kcen/2022/03/solve input-mattcl` | 237.7 ± 11.0 | 222.0 | 258.1 | 224.31 ± 76.17 |
| `kcen/2022/03/solve input-pting` | 234.6 ± 9.4 | 222.3 | 256.0 | 221.39 ± 75.00 |
| `lanjian/day_03 input-aspidites` | 1.1 ± 0.4 | 0.6 | 4.0 | 1.03 ± 0.49 |
| `lanjian/day_03 input-kcen` | 1.1 ± 0.4 | 0.6 | 5.9 | 1.00 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.3 | 0.5 | 3.3 | 1.15 ± 0.50 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.4 | 0.7 | 4.5 | 1.18 ± 0.56 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.3 | 0.6 | 3.3 | 1.09 ± 0.49 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.5 ± 1.1 | 0.8 | 16.2 | 1.41 ± 1.14 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.2 ± 0.4 | 0.7 | 3.2 | 1.10 ± 0.50 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.3 ± 0.4 | 0.7 | 4.8 | 1.26 ± 0.55 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.4 ± 0.6 | 0.7 | 12.4 | 1.32 ± 0.71 |
| `mattcl-solver/aoc run 3 input-pting` | 1.1 ± 0.4 | 0.7 | 8.7 | 1.04 ± 0.53 |
| `python pting/day03.py input-aspidites` | 34.4 ± 5.0 | 28.8 | 56.6 | 32.43 ± 11.88 |
| `python pting/day03.py input-kcen` | 30.7 ± 2.1 | 27.6 | 40.4 | 28.94 ± 9.93 |
| `python pting/day03.py input-lanjian` | 37.3 ± 4.2 | 30.7 | 48.5 | 35.17 ± 12.47 |
| `python pting/day03.py input-mattcl` | 33.8 ± 3.3 | 28.8 | 45.3 | 31.92 ± 11.18 |
| `python pting/day03.py input-pting` | 34.9 ± 3.6 | 29.5 | 46.5 | 32.94 ± 11.59 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
