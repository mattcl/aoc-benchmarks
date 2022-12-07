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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 28.2 ± 4.4 | 24.5 | 44.0 | 8.11 ± 3.45 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 26.3 ± 7.1 | 13.5 | 42.1 | 7.54 ± 3.62 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 28.2 ± 4.7 | 14.7 | 50.4 | 8.09 ± 3.48 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 25.5 ± 5.2 | 13.5 | 40.7 | 7.32 ± 3.26 |
| `aspidites-solver/aoc -i input-pting -d 3` | 27.2 ± 5.3 | 13.9 | 44.1 | 7.83 ± 3.46 |
| `kcen/2022/03/solve input-aspidites` | 393.0 ± 74.6 | 317.6 | 524.8 | 112.92 ± 49.67 |
| `kcen/2022/03/solve input-kcen` | 565.6 ± 231.2 | 370.5 | 962.9 | 162.50 ± 92.57 |
| `kcen/2022/03/solve input-lanjian` | 464.9 ± 79.1 | 341.8 | 589.3 | 133.59 ± 57.67 |
| `kcen/2022/03/solve input-mattcl` | 355.0 ± 71.8 | 276.7 | 522.4 | 102.01 ± 45.42 |
| `kcen/2022/03/solve input-pting` | 392.9 ± 53.3 | 318.7 | 491.1 | 112.90 ± 47.33 |
| `lanjian/day_03 input-aspidites` | 3.5 ± 1.4 | 1.0 | 8.9 | 1.00 |
| `lanjian/day_03 input-kcen` | 4.2 ± 1.7 | 1.0 | 12.8 | 1.20 ± 0.67 |
| `lanjian/day_03 input-lanjian` | 3.6 ± 1.9 | 0.9 | 20.6 | 1.04 ± 0.68 |
| `lanjian/day_03 input-mattcl` | 4.1 ± 1.4 | 1.6 | 9.5 | 1.18 ± 0.62 |
| `lanjian/day_03 input-pting` | 4.1 ± 1.4 | 1.5 | 12.7 | 1.18 ± 0.63 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.9 ± 2.2 | 1.5 | 14.9 | 1.12 ± 0.76 |
| `mattcl-solver/aoc run 3 input-kcen` | 3.9 ± 1.7 | 1.3 | 18.1 | 1.11 ± 0.67 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.6 ± 1.6 | 1.1 | 13.2 | 1.03 ± 0.62 |
| `mattcl-solver/aoc run 3 input-mattcl` | 4.3 ± 1.8 | 1.4 | 25.9 | 1.24 ± 0.72 |
| `mattcl-solver/aoc run 3 input-pting` | 4.1 ± 1.9 | 1.4 | 10.7 | 1.18 ± 0.72 |
| `python pting/day03.py input-aspidites` | 55.8 ± 19.4 | 41.3 | 158.0 | 16.03 ± 8.45 |
| `python pting/day03.py input-kcen` | 56.5 ± 20.8 | 40.5 | 151.9 | 16.22 ± 8.78 |
| `python pting/day03.py input-lanjian` | 64.5 ± 29.7 | 39.4 | 158.1 | 18.55 ± 11.28 |
| `python pting/day03.py input-mattcl` | 61.5 ± 26.0 | 41.6 | 162.8 | 17.67 ± 10.25 |
| `python pting/day03.py input-pting` | 61.3 ± 24.0 | 42.1 | 176.7 | 17.60 ± 9.80 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
