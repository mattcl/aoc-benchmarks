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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.0 ± 2.5 | 11.6 | 26.2 | 12.74 ± 4.78 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.4 ± 1.3 | 11.6 | 22.6 | 12.14 ± 4.12 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.4 ± 1.2 | 11.6 | 25.5 | 12.12 ± 4.08 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.4 ± 1.1 | 11.6 | 22.5 | 12.17 ± 4.07 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.3 ± 1.8 | 11.5 | 23.6 | 12.01 ± 4.25 |
| `kcen/2022/03/solve input-aspidites` | 229.2 ± 11.3 | 216.9 | 250.1 | 224.40 ± 73.28 |
| `kcen/2022/03/solve input-kcen` | 228.3 ± 11.6 | 212.3 | 248.3 | 223.54 ± 73.04 |
| `kcen/2022/03/solve input-lanjian` | 228.4 ± 11.2 | 208.3 | 244.5 | 223.64 ± 73.02 |
| `kcen/2022/03/solve input-mattcl` | 229.3 ± 13.6 | 213.7 | 267.4 | 224.52 ± 73.69 |
| `kcen/2022/03/solve input-pting` | 238.6 ± 17.0 | 217.6 | 270.2 | 233.58 ± 77.21 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.5 | 0.5 | 3.8 | 1.30 ± 0.64 |
| `lanjian/day_03 input-kcen` | 1.1 ± 0.5 | 0.5 | 8.7 | 1.12 ± 0.64 |
| `lanjian/day_03 input-lanjian` | 1.4 ± 0.5 | 0.5 | 5.4 | 1.37 ± 0.66 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.4 | 0.6 | 7.8 | 1.16 ± 0.55 |
| `lanjian/day_03 input-pting` | 1.0 ± 0.3 | 0.5 | 3.3 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.4 ± 0.6 | 0.6 | 6.9 | 1.39 ± 0.75 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.1 ± 0.4 | 0.5 | 4.8 | 1.05 ± 0.55 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.2 ± 0.5 | 0.6 | 8.4 | 1.20 ± 0.59 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.1 ± 0.3 | 0.5 | 3.4 | 1.05 ± 0.45 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.7 | 0.6 | 10.0 | 1.27 ± 0.83 |
| `python pting/day03.py input-aspidites` | 35.7 ± 4.6 | 29.6 | 53.8 | 34.97 ± 12.16 |
| `python pting/day03.py input-kcen` | 33.0 ± 3.6 | 28.2 | 48.6 | 32.31 ± 11.02 |
| `python pting/day03.py input-lanjian` | 34.8 ± 4.2 | 28.9 | 47.7 | 34.11 ± 11.74 |
| `python pting/day03.py input-mattcl` | 34.5 ± 4.3 | 29.3 | 54.3 | 33.77 ± 11.69 |
| `python pting/day03.py input-pting` | 34.8 ± 4.7 | 28.9 | 56.2 | 34.08 ± 11.93 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
