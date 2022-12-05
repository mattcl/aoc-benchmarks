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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.2 ± 0.9 | 11.6 | 23.0 | 13.45 ± 2.84 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.6 ± 1.8 | 11.7 | 25.2 | 13.96 ± 3.42 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.2 ± 1.2 | 11.6 | 22.2 | 13.48 ± 2.99 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.5 ± 3.8 | 11.5 | 60.0 | 13.77 ± 4.97 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.5 ± 0.8 | 11.7 | 22.0 | 13.76 ± 2.87 |
| `kcen/2022/03/solve input-aspidites` | 219.7 ± 13.0 | 197.1 | 243.1 | 242.59 ± 50.35 |
| `kcen/2022/03/solve input-kcen` | 230.9 ± 18.2 | 198.1 | 264.5 | 254.87 ± 54.55 |
| `kcen/2022/03/solve input-lanjian` | 229.4 ± 12.5 | 210.3 | 251.8 | 253.25 ± 52.25 |
| `kcen/2022/03/solve input-mattcl` | 244.9 ± 45.3 | 200.6 | 388.1 | 270.36 ± 73.42 |
| `kcen/2022/03/solve input-pting` | 216.6 ± 8.3 | 207.4 | 238.8 | 239.14 ± 48.45 |
| `lanjian/day_03 input-aspidites` | 0.9 ± 0.2 | 0.7 | 3.3 | 1.04 ± 0.32 |
| `lanjian/day_03 input-kcen` | 1.0 ± 0.3 | 0.7 | 6.5 | 1.14 ± 0.39 |
| `lanjian/day_03 input-lanjian` | 1.0 ± 0.2 | 0.6 | 4.2 | 1.15 ± 0.35 |
| `lanjian/day_03 input-mattcl` | 0.9 ± 0.4 | 0.6 | 9.9 | 1.01 ± 0.50 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.4 | 0.7 | 6.3 | 1.33 ± 0.56 |
| `mattcl-solver/aoc run 3 input-aspidites` | 0.9 ± 0.2 | 0.7 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.1 ± 0.2 | 0.7 | 2.8 | 1.21 ± 0.36 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.4 | 0.7 | 7.9 | 1.57 ± 0.58 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.0 ± 0.2 | 0.6 | 4.4 | 1.05 ± 0.32 |
| `mattcl-solver/aoc run 3 input-pting` | 1.2 ± 0.2 | 0.8 | 3.4 | 1.35 ± 0.37 |
| `python pting/day03.py input-aspidites` | 31.3 ± 2.5 | 27.1 | 42.0 | 34.57 ± 7.42 |
| `python pting/day03.py input-kcen` | 32.0 ± 3.9 | 27.4 | 58.1 | 35.32 ± 8.27 |
| `python pting/day03.py input-lanjian` | 32.2 ± 3.7 | 27.4 | 43.5 | 35.57 ± 8.18 |
| `python pting/day03.py input-mattcl` | 29.1 ± 1.3 | 26.8 | 32.9 | 32.12 ± 6.56 |
| `python pting/day03.py input-pting` | 32.3 ± 2.2 | 28.1 | 36.9 | 35.63 ± 7.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
