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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 23.4 ± 7.8 | 12.5 | 43.0 | 11.00 ± 7.78 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 21.8 ± 6.1 | 12.7 | 35.3 | 10.25 ± 7.03 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 19.8 ± 7.0 | 12.6 | 40.1 | 9.30 ± 6.69 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 49.3 ± 53.8 | 13.1 | 272.1 | 23.20 ± 29.16 |
| `aspidites-solver/aoc -i input-pting -d 3` | 20.0 ± 7.6 | 12.5 | 40.4 | 9.41 ± 6.89 |
| `kcen/2022/03/solve input-aspidites` | 402.7 ± 61.3 | 320.2 | 515.3 | 189.55 ± 121.89 |
| `kcen/2022/03/solve input-kcen` | 329.7 ± 22.8 | 307.2 | 373.0 | 155.20 ± 97.56 |
| `kcen/2022/03/solve input-lanjian` | 362.7 ± 48.4 | 296.2 | 446.3 | 170.72 ± 109.06 |
| `kcen/2022/03/solve input-mattcl` | 335.2 ± 49.5 | 295.5 | 459.6 | 157.79 ± 101.29 |
| `kcen/2022/03/solve input-pting` | 370.4 ± 45.0 | 300.5 | 467.5 | 174.34 ± 110.96 |
| `lanjian/day_03 input-aspidites` | 3.3 ± 1.8 | 0.9 | 16.7 | 1.54 ± 1.28 |
| `lanjian/day_03 input-kcen` | 2.4 ± 1.6 | 0.6 | 12.4 | 1.11 ± 1.02 |
| `lanjian/day_03 input-lanjian` | 2.8 ± 1.2 | 1.0 | 9.5 | 1.30 ± 1.00 |
| `lanjian/day_03 input-mattcl` | 2.1 ± 1.3 | 0.6 | 9.7 | 1.00 |
| `lanjian/day_03 input-pting` | 2.6 ± 1.4 | 0.6 | 15.2 | 1.25 ± 1.03 |
| `mattcl-solver/aoc run 3 input-aspidites` | 3.1 ± 2.1 | 0.6 | 26.4 | 1.46 ± 1.33 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.9 ± 1.3 | 0.9 | 12.9 | 1.38 ± 1.06 |
| `mattcl-solver/aoc run 3 input-lanjian` | 3.1 ± 1.6 | 0.9 | 16.2 | 1.48 ± 1.19 |
| `mattcl-solver/aoc run 3 input-mattcl` | 3.1 ± 1.4 | 0.9 | 9.5 | 1.44 ± 1.12 |
| `mattcl-solver/aoc run 3 input-pting` | 3.0 ± 2.6 | 0.9 | 33.2 | 1.40 ± 1.51 |
| `python pting/day03.py input-aspidites` | 64.4 ± 35.0 | 41.2 | 158.9 | 30.33 ± 25.09 |
| `python pting/day03.py input-kcen` | 46.1 ± 17.7 | 33.5 | 161.8 | 21.68 ± 15.91 |
| `python pting/day03.py input-lanjian` | 50.3 ± 13.1 | 35.9 | 135.7 | 23.69 ± 16.03 |
| `python pting/day03.py input-mattcl` | 58.7 ± 26.0 | 40.3 | 148.5 | 27.63 ± 21.16 |
| `python pting/day03.py input-pting` | 53.2 ± 12.4 | 41.0 | 105.2 | 25.05 ± 16.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>8298</pre>|<pre>2708</pre>|
|input-mattcl|<pre>7597</pre>|<pre>2607</pre>|
|input-aspidites|<pre>7746</pre>|<pre>2604</pre>|
|input-pting|<pre>7553</pre>|<pre>2758</pre>|
|input-kcen|<pre>8039</pre>|<pre>2510</pre>|
