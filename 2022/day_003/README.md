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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.6 ± 2.5 | 11.8 | 24.5 | 12.19 ± 4.02 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.9 ± 1.6 | 11.9 | 25.3 | 11.54 ± 3.49 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.9 ± 1.6 | 11.8 | 23.5 | 11.59 ± 3.49 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.8 ± 3.2 | 11.9 | 27.9 | 12.35 ± 4.42 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.4 ± 1.8 | 11.7 | 35.5 | 11.12 ± 3.44 |
| `kcen/2022/03/solve input-aspidites` | 244.7 ± 12.5 | 229.4 | 268.3 | 219.48 ± 61.38 |
| `kcen/2022/03/solve input-kcen` | 259.4 ± 26.6 | 232.6 | 310.9 | 232.64 ± 68.27 |
| `kcen/2022/03/solve input-lanjian` | 235.5 ± 10.8 | 215.6 | 247.1 | 211.28 ± 58.88 |
| `kcen/2022/03/solve input-mattcl` | 240.1 ± 13.5 | 220.0 | 262.7 | 215.36 ± 60.44 |
| `kcen/2022/03/solve input-pting` | 235.1 ± 8.4 | 216.8 | 250.8 | 210.91 ± 58.47 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.4 | 0.7 | 6.3 | 1.13 ± 0.46 |
| `lanjian/day_03 input-kcen` | 1.2 ± 0.4 | 0.7 | 4.5 | 1.08 ± 0.44 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.4 | 0.7 | 6.4 | 1.06 ± 0.44 |
| `lanjian/day_03 input-mattcl` | 1.3 ± 0.7 | 0.7 | 8.1 | 1.20 ± 0.70 |
| `lanjian/day_03 input-pting` | 1.5 ± 0.5 | 0.7 | 8.3 | 1.38 ± 0.61 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.5 ± 0.4 | 0.8 | 4.6 | 1.36 ± 0.54 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.1 ± 0.3 | 0.7 | 3.6 | 1.00 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.2 ± 0.3 | 0.8 | 3.4 | 1.08 ± 0.41 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.7 ± 0.7 | 0.8 | 6.5 | 1.53 ± 0.77 |
| `mattcl-solver/aoc run 3 input-pting` | 1.5 ± 0.4 | 0.8 | 6.4 | 1.37 ± 0.54 |
| `python pting/day03.py input-aspidites` | 34.8 ± 4.1 | 29.2 | 45.8 | 31.19 ± 9.33 |
| `python pting/day03.py input-kcen` | 34.4 ± 2.7 | 30.2 | 46.2 | 30.84 ± 8.82 |
| `python pting/day03.py input-lanjian` | 34.3 ± 3.3 | 30.0 | 48.6 | 30.81 ± 8.98 |
| `python pting/day03.py input-mattcl` | 34.7 ± 4.3 | 30.2 | 58.4 | 31.16 ± 9.38 |
| `python pting/day03.py input-pting` | 33.7 ± 3.3 | 29.5 | 45.0 | 30.27 ± 8.82 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
