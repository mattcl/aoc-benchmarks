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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.1 ± 2.3 | 11.8 | 38.7 | 5.86 ± 3.90 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 15.9 ± 3.9 | 12.2 | 30.9 | 6.64 ± 4.59 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.4 ± 2.6 | 12.5 | 27.3 | 6.44 ± 4.30 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.6 ± 5.0 | 12.0 | 40.6 | 6.52 ± 4.71 |
| `aspidites-solver/aoc -i input-pting -d 2` | 15.7 ± 3.4 | 11.8 | 28.5 | 6.54 ± 4.46 |
| `kcen/2022/02/solve input-aspidites` | 3.2 ± 3.2 | 0.2 | 23.4 | 1.35 ± 1.59 |
| `kcen/2022/02/solve input-kcen` | 2.9 ± 1.6 | 0.4 | 12.6 | 1.20 ± 1.03 |
| `kcen/2022/02/solve input-lanjian` | 2.8 ± 1.8 | 0.2 | 10.3 | 1.16 ± 1.05 |
| `kcen/2022/02/solve input-mattcl` | 2.9 ± 1.7 | 0.4 | 9.0 | 1.20 ± 1.06 |
| `kcen/2022/02/solve input-pting` | 2.4 ± 1.5 | 0.2 | 15.0 | 1.00 |
| `lanjian/day_02 input-aspidites` | 4.4 ± 2.4 | 1.2 | 19.2 | 1.84 ± 1.55 |
| `lanjian/day_02 input-kcen` | 2.9 ± 1.7 | 1.0 | 12.1 | 1.22 ± 1.06 |
| `lanjian/day_02 input-lanjian` | 2.8 ± 1.7 | 0.7 | 11.2 | 1.16 ± 1.02 |
| `lanjian/day_02 input-mattcl` | 2.9 ± 1.6 | 0.6 | 15.7 | 1.19 ± 1.03 |
| `lanjian/day_02 input-pting` | 3.8 ± 2.1 | 0.7 | 13.7 | 1.60 ± 1.35 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.5 ± 1.7 | 0.7 | 15.6 | 1.44 ± 1.17 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.6 ± 1.8 | 0.5 | 13.6 | 1.09 ± 1.02 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.9 ± 1.6 | 0.4 | 10.5 | 1.20 ± 1.01 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.4 ± 1.9 | 0.6 | 14.3 | 1.40 ± 1.21 |
| `mattcl-solver/aoc run 2 input-pting` | 3.3 ± 1.8 | 0.8 | 13.7 | 1.36 ± 1.15 |
| `python pting/day02.py input-aspidites` | 80.1 ± 33.1 | 43.3 | 187.1 | 33.42 ± 25.61 |
| `python pting/day02.py input-kcen` | 54.6 ± 12.3 | 41.9 | 107.1 | 22.77 ± 15.57 |
| `python pting/day02.py input-lanjian` | 50.6 ± 14.4 | 39.1 | 120.3 | 21.11 ± 14.90 |
| `python pting/day02.py input-mattcl` | 58.4 ± 20.6 | 35.9 | 162.7 | 24.36 ± 17.91 |
| `python pting/day02.py input-pting` | 58.4 ± 20.6 | 40.0 | 150.8 | 24.36 ± 17.92 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
