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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.4 ± 4.1 | 10.8 | 27.2 | 22.21 ± 17.74 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.9 ± 4.8 | 10.9 | 33.4 | 23.11 ± 18.83 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 15.2 ± 4.9 | 11.1 | 25.6 | 25.26 ± 20.34 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 15.6 ± 5.3 | 11.0 | 25.2 | 25.95 ± 21.08 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.1 ± 3.2 | 11.1 | 24.4 | 21.71 ± 16.89 |
| `kcen/2022/03/solve input-aspidites` | 252.0 ± 21.9 | 223.4 | 302.4 | 418.65 ± 310.79 |
| `kcen/2022/03/solve input-kcen` | 225.6 ± 27.7 | 193.4 | 265.8 | 374.73 ± 280.07 |
| `kcen/2022/03/solve input-lanjian` | 250.5 ± 19.1 | 225.3 | 288.7 | 416.08 ± 308.39 |
| `kcen/2022/03/solve input-mattcl` | 250.1 ± 20.2 | 209.1 | 278.2 | 415.48 ± 308.15 |
| `kcen/2022/03/solve input-pting` | 259.4 ± 22.4 | 221.5 | 305.6 | 430.84 ± 319.82 |
| `lanjian/day_03 input-aspidites` | 0.7 ± 0.6 | 0.0 | 4.9 | 1.18 ± 1.34 |
| `lanjian/day_03 input-kcen` | 0.9 ± 0.6 | 0.0 | 4.1 | 1.46 ± 1.43 |
| `lanjian/day_03 input-lanjian` | 1.0 ± 0.8 | 0.0 | 6.7 | 1.66 ± 1.75 |
| `lanjian/day_03 input-mattcl` | 0.9 ± 0.6 | 0.1 | 4.1 | 1.57 ± 1.52 |
| `lanjian/day_03 input-pting` | 0.6 ± 0.4 | 0.0 | 4.2 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.4 ± 0.8 | 0.1 | 5.9 | 2.25 ± 2.11 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.0 ± 0.5 | 0.4 | 4.3 | 1.67 ± 1.49 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.5 ± 0.8 | 0.3 | 10.5 | 2.50 ± 2.26 |
| `mattcl-solver/aoc run 3 input-mattcl` | 0.8 ± 0.6 | 0.1 | 4.3 | 1.38 ± 1.43 |
| `mattcl-solver/aoc run 3 input-pting` | 0.9 ± 1.3 | 0.0 | 11.6 | 1.54 ± 2.41 |
| `python pting/day03.py input-aspidites` | 35.5 ± 5.4 | 28.4 | 56.9 | 58.91 ± 44.36 |
| `python pting/day03.py input-kcen` | 35.7 ± 7.9 | 26.4 | 79.2 | 59.28 ± 45.62 |
| `python pting/day03.py input-lanjian` | 36.1 ± 8.6 | 26.1 | 64.2 | 59.97 ± 46.47 |
| `python pting/day03.py input-mattcl` | 34.0 ± 3.6 | 28.0 | 45.5 | 56.49 ± 42.07 |
| `python pting/day03.py input-pting` | 32.9 ± 3.3 | 27.2 | 48.2 | 54.66 ± 40.67 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
