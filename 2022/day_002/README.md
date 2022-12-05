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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.8 ± 0.7 | 11.5 | 15.5 | 7.98 ± 2.42 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.8 ± 0.8 | 11.6 | 16.3 | 7.96 ± 2.42 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.9 ± 0.7 | 11.5 | 15.0 | 8.04 ± 2.43 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.0 ± 0.8 | 11.6 | 18.3 | 8.13 ± 2.48 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.5 ± 1.0 | 11.2 | 23.6 | 7.79 ± 2.41 |
| `kcen/2022/02/solve input-aspidites` | 1.6 ± 0.7 | 0.8 | 5.9 | 1.03 ± 0.53 |
| `kcen/2022/02/solve input-kcen` | 1.9 ± 0.9 | 0.9 | 9.6 | 1.21 ± 0.67 |
| `kcen/2022/02/solve input-lanjian` | 1.9 ± 1.0 | 0.6 | 8.3 | 1.21 ± 0.71 |
| `kcen/2022/02/solve input-mattcl` | 2.4 ± 1.2 | 1.1 | 11.4 | 1.49 ± 0.85 |
| `kcen/2022/02/solve input-pting` | 1.6 ± 0.6 | 0.8 | 4.9 | 1.01 ± 0.46 |
| `lanjian/day_02 input-aspidites` | 2.1 ± 0.7 | 1.2 | 5.9 | 1.28 ± 0.57 |
| `lanjian/day_02 input-kcen` | 1.8 ± 0.6 | 1.0 | 6.2 | 1.09 ± 0.48 |
| `lanjian/day_02 input-lanjian` | 2.3 ± 0.8 | 1.1 | 12.6 | 1.41 ± 0.65 |
| `lanjian/day_02 input-mattcl` | 2.4 ± 0.9 | 1.1 | 7.3 | 1.47 ± 0.72 |
| `lanjian/day_02 input-pting` | 1.8 ± 0.8 | 1.1 | 6.4 | 1.15 ± 0.59 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.9 ± 0.7 | 0.9 | 6.9 | 1.17 ± 0.55 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.6 ± 0.5 | 0.9 | 4.5 | 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.9 ± 0.9 | 0.8 | 12.1 | 1.20 ± 0.65 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.2 ± 1.0 | 0.9 | 12.4 | 1.36 ± 0.73 |
| `mattcl-solver/aoc run 2 input-pting` | 2.1 ± 1.0 | 1.0 | 11.2 | 1.30 ± 0.71 |
| `python pting/day02.py input-aspidites` | 37.1 ± 7.0 | 28.3 | 70.4 | 23.13 ± 8.15 |
| `python pting/day02.py input-kcen` | 35.4 ± 6.7 | 28.1 | 65.2 | 22.10 ± 7.82 |
| `python pting/day02.py input-lanjian` | 44.9 ± 11.5 | 32.1 | 83.6 | 27.99 ± 11.01 |
| `python pting/day02.py input-mattcl` | 38.6 ± 7.4 | 29.1 | 65.8 | 24.11 ± 8.54 |
| `python pting/day02.py input-pting` | 36.2 ± 9.9 | 28.8 | 100.5 | 22.61 ± 9.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
