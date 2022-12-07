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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 27.2 ± 3.8 | 23.3 | 46.1 | 11.78 ± 7.81 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 25.6 ± 2.3 | 13.1 | 38.0 | 11.09 ± 7.25 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 26.5 ± 3.4 | 23.6 | 42.6 | 11.49 ± 7.59 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.0 ± 4.4 | 12.4 | 43.6 | 10.81 ± 7.26 |
| `aspidites-solver/aoc -i input-pting -d 3` | 25.6 ± 3.0 | 13.6 | 46.2 | 11.07 ± 7.28 |
| `kcen/2022/03/solve input-aspidites` | 431.7 ± 60.2 | 360.2 | 520.6 | 186.97 ± 123.88 |
| `kcen/2022/03/solve input-kcen` | 408.6 ± 43.0 | 341.6 | 492.0 | 176.98 ± 116.14 |
| `kcen/2022/03/solve input-lanjian` | 384.3 ± 30.3 | 320.7 | 420.5 | 166.45 ± 108.61 |
| `kcen/2022/03/solve input-mattcl` | 392.9 ± 35.2 | 351.4 | 438.9 | 170.14 ± 111.26 |
| `kcen/2022/03/solve input-pting` | 398.1 ± 46.8 | 324.2 | 451.9 | 172.42 ± 113.51 |
| `lanjian/day_03 input-aspidites` | 2.4 ± 1.6 | 0.0 | 13.3 | 1.03 ± 0.97 |
| `lanjian/day_03 input-kcen` | 2.3 ± 1.5 | 0.1 | 17.0 | 1.00 |
| `lanjian/day_03 input-lanjian` | 2.3 ± 2.2 | 0.1 | 29.6 | 1.01 ± 1.16 |
| `lanjian/day_03 input-mattcl` | 2.5 ± 1.3 | 0.3 | 11.3 | 1.09 ± 0.92 |
| `lanjian/day_03 input-pting` | 2.7 ± 1.8 | 0.0 | 20.2 | 1.16 ± 1.09 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.2 ± 1.8 | 0.6 | 19.4 | 1.39 ± 1.19 |
| `mattcl-solver/aoc run 3 input-kcen` | 3.2 ± 2.0 | 0.5 | 27.5 | 1.40 ± 1.27 |
| `mattcl-solver/aoc run 3 input-lanjian` | 2.4 ± 1.3 | 0.2 | 13.7 | 1.06 ± 0.88 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.2 ± 1.7 | 0.6 | 14.6 | 1.39 ± 1.18 |
| `mattcl-solver/aoc run 3 input-pting` | 2.9 ± 1.6 | 0.1 | 12.6 | 1.27 ± 1.09 |
| `python pting/day03.py input-aspidites` | 68.4 ± 10.3 | 48.9 | 95.2 | 29.63 ± 19.71 |
| `python pting/day03.py input-kcen` | 63.3 ± 11.3 | 45.5 | 93.9 | 27.42 ± 18.42 |
| `python pting/day03.py input-lanjian` | 62.4 ± 9.4 | 46.8 | 88.7 | 27.03 ± 17.97 |
| `python pting/day03.py input-mattcl` | 60.6 ± 7.4 | 48.2 | 81.8 | 26.25 ± 17.30 |
| `python pting/day03.py input-pting` | 62.1 ± 10.0 | 47.6 | 91.9 | 26.90 ± 17.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
