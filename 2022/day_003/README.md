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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.3 ± 3.3 | 11.9 | 35.7 | 13.11 ± 4.97 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.9 ± 1.4 | 11.9 | 23.9 | 12.68 ± 3.92 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.1 ± 1.0 | 11.6 | 23.3 | 11.90 ± 3.59 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 12.7 ± 2.1 | 11.6 | 23.1 | 12.49 ± 4.15 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.2 ± 2.7 | 11.5 | 25.2 | 12.95 ± 4.59 |
| `kcen/2022/03/solve input-aspidites` | 257.8 ± 18.9 | 232.1 | 290.9 | 253.43 ± 75.45 |
| `kcen/2022/03/solve input-kcen` | 229.1 ± 10.5 | 216.0 | 253.2 | 225.22 ± 65.80 |
| `kcen/2022/03/solve input-lanjian` | 212.2 ± 9.7 | 199.7 | 233.1 | 208.58 ± 60.94 |
| `kcen/2022/03/solve input-mattcl` | 220.0 ± 10.7 | 200.4 | 237.5 | 216.30 ± 63.30 |
| `kcen/2022/03/solve input-pting` | 230.3 ± 17.4 | 202.5 | 257.2 | 226.38 ± 67.52 |
| `lanjian/day_03 input-aspidites` | 1.1 ± 0.3 | 0.6 | 3.9 | 1.06 ± 0.44 |
| `lanjian/day_03 input-kcen` | 1.4 ± 0.5 | 0.6 | 5.3 | 1.39 ± 0.65 |
| `lanjian/day_03 input-lanjian` | 1.3 ± 0.7 | 0.6 | 10.3 | 1.27 ± 0.76 |
| `lanjian/day_03 input-mattcl` | 1.1 ± 0.4 | 0.6 | 4.3 | 1.06 ± 0.53 |
| `lanjian/day_03 input-pting` | 1.1 ± 0.4 | 0.7 | 6.2 | 1.13 ± 0.50 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.2 ± 0.4 | 0.6 | 5.7 | 1.19 ± 0.50 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.2 ± 0.4 | 0.6 | 3.6 | 1.16 ± 0.53 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.3 ± 0.5 | 0.8 | 4.9 | 1.26 ± 0.62 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.0 ± 0.3 | 0.7 | 3.9 | 1.00 |
| `mattcl-solver/aoc run 3 input-pting` | 1.2 ± 0.4 | 0.7 | 4.0 | 1.16 ± 0.50 |
| `python pting/day03.py input-aspidites` | 31.0 ± 3.2 | 27.1 | 44.1 | 30.44 ± 9.32 |
| `python pting/day03.py input-kcen` | 34.8 ± 3.8 | 29.0 | 51.9 | 34.17 ± 10.53 |
| `python pting/day03.py input-lanjian` | 32.6 ± 3.9 | 29.3 | 51.0 | 32.03 ± 10.00 |
| `python pting/day03.py input-mattcl` | 32.2 ± 2.7 | 28.5 | 43.2 | 31.61 ± 9.49 |
| `python pting/day03.py input-pting` | 34.0 ± 4.7 | 28.3 | 56.3 | 33.43 ± 10.69 |
\n## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
