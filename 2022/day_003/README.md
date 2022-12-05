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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.9 ± 3.7 | 11.6 | 23.9 | 17.91 ± 7.46 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.8 ± 4.4 | 11.6 | 28.9 | 19.09 ± 8.36 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.5 ± 3.8 | 11.4 | 37.0 | 17.50 ± 7.50 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 11.8 ± 0.7 | 11.3 | 21.5 | 15.20 ± 5.00 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.8 ± 3.5 | 11.6 | 25.2 | 17.87 ± 7.31 |
| `kcen/2022/03/solve input-aspidites` | 265.1 ± 28.5 | 237.7 | 337.9 | 342.68 ± 116.48 |
| `kcen/2022/03/solve input-kcen` | 274.4 ± 21.8 | 250.9 | 320.7 | 354.70 ± 117.77 |
| `kcen/2022/03/solve input-lanjian` | 255.3 ± 26.2 | 212.8 | 307.1 | 329.95 ± 111.66 |
| `kcen/2022/03/solve input-mattcl` | 224.0 ± 11.0 | 208.1 | 242.5 | 289.56 ± 94.44 |
| `kcen/2022/03/solve input-pting` | 231.7 ± 20.8 | 210.5 | 269.7 | 299.54 ± 100.26 |
| `lanjian/day_03 input-aspidites` | 0.8 ± 0.2 | 0.5 | 2.9 | 1.00 |
| `lanjian/day_03 input-kcen` | 1.3 ± 0.5 | 0.5 | 3.1 | 1.64 ± 0.79 |
| `lanjian/day_03 input-lanjian` | 1.0 ± 0.5 | 0.5 | 3.8 | 1.30 ± 0.73 |
| `lanjian/day_03 input-mattcl` | 1.6 ± 0.9 | 0.6 | 8.9 | 2.09 ± 1.29 |
| `lanjian/day_03 input-pting` | 1.0 ± 0.4 | 0.5 | 3.9 | 1.32 ± 0.70 |
| `mattcl-solver/aoc run 3 input-aspidites` | 0.8 ± 0.2 | 0.5 | 2.5 | 1.01 ± 0.40 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.3 ± 0.5 | 0.6 | 4.4 | 1.69 ± 0.86 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.3 ± 0.5 | 0.6 | 6.0 | 1.72 ± 0.86 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.0 ± 0.6 | 0.5 | 5.8 | 1.35 ± 0.91 |
| `mattcl-solver/aoc run 3 input-pting` | 1.6 ± 0.6 | 0.6 | 7.5 | 2.10 ± 1.02 |
| `python pting/day03.py input-aspidites` | 34.3 ± 4.4 | 28.3 | 47.8 | 44.34 ± 15.39 |
| `python pting/day03.py input-kcen` | 36.7 ± 4.3 | 31.0 | 58.3 | 47.44 ± 16.27 |
| `python pting/day03.py input-lanjian` | 37.3 ± 7.4 | 31.7 | 64.8 | 48.21 ± 18.26 |
| `python pting/day03.py input-mattcl` | 39.3 ± 7.8 | 31.0 | 72.2 | 50.75 ± 19.22 |
| `python pting/day03.py input-pting` | 34.3 ± 4.5 | 28.2 | 52.0 | 44.39 ± 15.44 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
