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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.5 ± 0.9 | 11.8 | 23.4 | 11.33 ± 2.38 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.0 ± 2.1 | 11.9 | 23.1 | 11.77 ± 2.98 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.3 ± 1.1 | 11.8 | 23.4 | 11.14 ± 2.40 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 14.1 ± 4.1 | 11.8 | 32.7 | 12.75 ± 4.49 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.1 ± 2.3 | 11.8 | 29.3 | 11.81 ± 3.14 |
| `kcen/2022/03/solve input-aspidites` | 231.5 ± 11.4 | 214.6 | 250.4 | 209.31 ± 42.58 |
| `kcen/2022/03/solve input-kcen` | 235.3 ± 6.9 | 224.0 | 247.4 | 212.78 ± 42.47 |
| `kcen/2022/03/solve input-lanjian` | 216.0 ± 5.9 | 208.8 | 230.2 | 195.30 ± 38.93 |
| `kcen/2022/03/solve input-mattcl` | 223.4 ± 17.0 | 205.6 | 262.9 | 202.01 ± 42.73 |
| `kcen/2022/03/solve input-pting` | 238.9 ± 12.6 | 224.3 | 261.8 | 215.97 ± 44.14 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.3 | 0.8 | 3.3 | 1.17 ± 0.37 |
| `lanjian/day_03 input-kcen` | 1.6 ± 0.4 | 0.8 | 4.6 | 1.43 ± 0.47 |
| `lanjian/day_03 input-lanjian` | 1.1 ± 0.2 | 0.7 | 2.7 | 1.00 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.5 | 0.8 | 8.7 | 1.11 ± 0.46 |
| `lanjian/day_03 input-pting` | 1.4 ± 0.4 | 0.8 | 5.9 | 1.25 ± 0.46 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.6 ± 0.9 | 0.9 | 12.3 | 1.48 ± 0.83 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.6 ± 0.4 | 1.0 | 6.1 | 1.47 ± 0.46 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.2 ± 0.3 | 0.9 | 6.2 | 1.12 ± 0.38 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.2 ± 0.3 | 0.8 | 7.8 | 1.04 ± 0.35 |
| `mattcl-solver/aoc run 3 input-pting` | 1.4 ± 0.3 | 0.8 | 3.1 | 1.27 ± 0.40 |
| `python pting/day03.py input-aspidites` | 34.1 ± 4.0 | 29.0 | 49.4 | 30.85 ± 7.11 |
| `python pting/day03.py input-kcen` | 34.3 ± 3.6 | 29.3 | 44.2 | 31.04 ± 6.96 |
| `python pting/day03.py input-lanjian` | 31.9 ± 2.9 | 28.6 | 42.0 | 28.88 ± 6.26 |
| `python pting/day03.py input-mattcl` | 33.1 ± 2.6 | 29.4 | 42.8 | 29.91 ± 6.37 |
| `python pting/day03.py input-pting` | 34.1 ± 3.8 | 29.7 | 44.6 | 30.80 ± 7.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
