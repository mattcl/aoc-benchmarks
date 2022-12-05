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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.5 ± 2.3 | 11.7 | 40.6 | 11.79 ± 6.12 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.5 ± 2.1 | 11.7 | 23.3 | 11.86 ± 6.11 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.3 ± 2.6 | 11.9 | 27.3 | 12.61 ± 6.60 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.1 ± 2.9 | 11.6 | 25.2 | 12.38 ± 6.62 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.9 ± 3.7 | 11.8 | 35.5 | 13.10 ± 7.26 |
| `kcen/2022/03/solve input-aspidites` | 229.0 ± 11.1 | 210.0 | 240.3 | 216.43 ± 105.75 |
| `kcen/2022/03/solve input-kcen` | 220.4 ± 8.7 | 208.6 | 233.9 | 208.28 ± 101.61 |
| `kcen/2022/03/solve input-lanjian` | 251.4 ± 20.4 | 215.4 | 287.0 | 237.65 ± 117.15 |
| `kcen/2022/03/solve input-mattcl` | 249.0 ± 18.2 | 224.2 | 282.2 | 235.38 ± 115.73 |
| `kcen/2022/03/solve input-pting` | 245.3 ± 26.5 | 208.3 | 278.4 | 231.85 ± 115.48 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.7 | 0.6 | 9.0 | 1.22 ± 0.86 |
| `lanjian/day_03 input-kcen` | 1.1 ± 0.5 | 0.6 | 8.3 | 1.00 |
| `lanjian/day_03 input-lanjian` | 1.9 ± 0.9 | 0.8 | 9.6 | 1.78 ± 1.20 |
| `lanjian/day_03 input-mattcl` | 1.3 ± 0.4 | 0.6 | 3.3 | 1.20 ± 0.67 |
| `lanjian/day_03 input-pting` | 1.1 ± 0.4 | 0.6 | 7.5 | 1.06 ± 0.64 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.3 ± 0.6 | 0.7 | 9.8 | 1.26 ± 0.83 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.6 ± 0.7 | 0.9 | 8.4 | 1.53 ± 1.00 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.8 ± 0.9 | 0.8 | 10.8 | 1.69 ± 1.19 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.4 ± 0.4 | 0.7 | 4.2 | 1.31 ± 0.76 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.4 | 0.7 | 4.6 | 1.20 ± 0.68 |
| `python pting/day03.py input-aspidites` | 33.8 ± 4.7 | 28.0 | 57.2 | 31.94 ± 16.16 |
| `python pting/day03.py input-kcen` | 34.9 ± 4.4 | 29.4 | 52.6 | 32.97 ± 16.56 |
| `python pting/day03.py input-lanjian` | 38.3 ± 6.8 | 30.3 | 64.0 | 36.24 ± 18.74 |
| `python pting/day03.py input-mattcl` | 35.3 ± 3.9 | 30.3 | 47.0 | 33.33 ± 16.62 |
| `python pting/day03.py input-pting` | 34.8 ± 4.0 | 28.8 | 47.9 | 32.91 ± 16.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
