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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 17.8 ± 6.1 | 8.1 | 38.6 | 240.81 ± 1405.21 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 19.9 ± 5.0 | 8.5 | 42.4 | 269.79 ± 1573.06 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 23.1 ± 4.2 | 19.2 | 38.5 | 312.33 ± 1820.32 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 22.4 ± 5.2 | 8.4 | 39.9 | 302.61 ± 1764.18 |
| `aspidites-solver/aoc -i input-pting -d 3` | 21.6 ± 7.1 | 8.7 | 55.5 | 292.17 ± 1704.69 |
| `kcen/2022/03/solve input-aspidites` | 368.8 ± 50.8 | 308.6 | 451.7 | 4989.04 ± 29070.95 |
| `kcen/2022/03/solve input-kcen` | 349.5 ± 47.3 | 283.2 | 453.9 | 4726.88 ± 27543.13 |
| `kcen/2022/03/solve input-lanjian` | 438.8 ± 119.0 | 334.7 | 654.5 | 5935.77 ± 34615.29 |
| `kcen/2022/03/solve input-mattcl` | 387.0 ± 42.8 | 335.2 | 462.3 | 5234.91 ± 30500.64 |
| `kcen/2022/03/solve input-pting` | 391.3 ± 105.6 | 287.6 | 671.1 | 5292.47 ± 30863.52 |
| `lanjian/day_03 input-aspidites` | 0.2 ± 0.7 | 0.0 | 11.8 | 2.65 ± 18.41 |
| `lanjian/day_03 input-kcen` | 0.2 ± 0.6 | 0.0 | 6.4 | 2.50 ± 16.88 |
| `lanjian/day_03 input-lanjian` | 0.2 ± 0.8 | 0.0 | 9.6 | 2.39 ± 17.25 |
| `lanjian/day_03 input-mattcl` | 0.1 ± 0.9 | 0.0 | 15.8 | 1.89 ± 16.15 |
| `lanjian/day_03 input-pting` | 0.1 ± 0.6 | 0.0 | 9.4 | 1.25 ± 11.14 |
| `mattcl-solver/aoc run 3 input-aspidites` | 0.4 ± 1.1 | 0.0 | 13.5 | 4.90 ± 32.32 |
| `mattcl-solver/aoc run 3 input-kcen` | 0.5 ± 0.9 | 0.0 | 5.6 | 6.24 ± 38.50 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.0 ± 3.0 | 0.0 | 29.2 | 13.82 ± 90.29 |
| `mattcl-solver/aoc run 3 input-mattcl` | 0.4 ± 0.9 | 0.0 | 7.9 | 5.84 ± 36.18 |
| `mattcl-solver/aoc run 3 input-pting` | 0.1 ± 0.4 | 0.0 | 6.6 | 1.00 |
| `python pting/day03.py input-aspidites` | 50.2 ± 12.1 | 35.7 | 92.3 | 679.17 ± 3959.82 |
| `python pting/day03.py input-kcen` | 58.3 ± 24.3 | 37.5 | 137.2 | 788.74 ± 4606.42 |
| `python pting/day03.py input-lanjian` | 56.9 ± 20.8 | 38.5 | 169.3 | 770.24 ± 4495.72 |
| `python pting/day03.py input-mattcl` | 54.0 ± 20.0 | 39.7 | 137.5 | 730.93 ± 4266.47 |
| `python pting/day03.py input-pting` | 65.9 ± 31.9 | 32.6 | 181.4 | 891.70 ± 5212.30 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
