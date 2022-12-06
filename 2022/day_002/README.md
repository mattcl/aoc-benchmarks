# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 2)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.7 ± 2.3 | 12.4 | 27.4 | 4.81 ± 2.06 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 15.7 ± 3.2 | 12.8 | 29.2 | 5.15 ± 2.30 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.3 ± 2.9 | 12.8 | 27.8 | 5.03 ± 2.22 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 18.0 ± 5.7 | 12.7 | 44.9 | 5.90 ± 3.01 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.7 ± 2.3 | 12.7 | 25.2 | 4.84 ± 2.06 |
| `kcen/2022/02/solve input-aspidites` | 3.0 ± 1.2 | 0.8 | 7.7 | 1.00 |
| `kcen/2022/02/solve input-kcen` | 4.6 ± 5.7 | 0.7 | 46.4 | 1.52 ± 1.96 |
| `kcen/2022/02/solve input-lanjian` | 3.2 ± 1.6 | 1.2 | 15.9 | 1.03 ± 0.67 |
| `kcen/2022/02/solve input-mattcl` | 4.1 ± 2.0 | 1.0 | 17.3 | 1.35 ± 0.84 |
| `kcen/2022/02/solve input-pting` | 3.8 ± 1.8 | 0.8 | 13.3 | 1.25 ± 0.77 |
| `lanjian/day_02 input-aspidites` | 4.4 ± 1.9 | 1.7 | 19.0 | 1.46 ± 0.85 |
| `lanjian/day_02 input-kcen` | 4.2 ± 1.8 | 1.6 | 11.2 | 1.38 ± 0.80 |
| `lanjian/day_02 input-lanjian` | 3.8 ± 1.8 | 1.4 | 18.8 | 1.25 ± 0.77 |
| `lanjian/day_02 input-mattcl` | 7.0 ± 6.4 | 1.8 | 51.1 | 2.31 ± 2.30 |
| `lanjian/day_02 input-pting` | 3.6 ± 1.8 | 1.4 | 16.4 | 1.18 ± 0.75 |
| `mattcl-solver/aoc run 2 input-aspidites` | 4.2 ± 1.9 | 1.3 | 18.7 | 1.37 ± 0.82 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.5 ± 1.0 | 1.3 | 8.9 | 1.15 ± 0.57 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.1 ± 1.0 | 1.1 | 9.0 | 1.03 ± 0.52 |
| `mattcl-solver/aoc run 2 input-mattcl` | 4.1 ± 1.9 | 1.3 | 16.9 | 1.34 ± 0.81 |
| `mattcl-solver/aoc run 2 input-pting` | 4.0 ± 1.7 | 1.4 | 17.0 | 1.30 ± 0.75 |
| `python pting/day02.py input-aspidites` | 66.1 ± 14.4 | 48.2 | 140.3 | 21.67 ± 9.84 |
| `python pting/day02.py input-kcen` | 69.3 ± 24.9 | 50.2 | 194.9 | 22.72 ± 12.19 |
| `python pting/day02.py input-lanjian` | 79.4 ± 42.1 | 53.0 | 201.9 | 26.04 ± 17.26 |
| `python pting/day02.py input-mattcl` | 87.2 ± 41.5 | 57.2 | 193.1 | 28.61 ± 17.75 |
| `python pting/day02.py input-pting` | 68.9 ± 17.0 | 48.3 | 125.6 | 22.59 ± 10.59 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
