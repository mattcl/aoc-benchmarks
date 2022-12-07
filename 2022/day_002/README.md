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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 16.0 ± 3.8 | 13.1 | 30.4 | 4.63 ± 2.29 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 16.7 ± 3.3 | 13.4 | 28.8 | 4.81 ± 2.30 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 21.9 ± 13.7 | 13.0 | 85.6 | 6.33 ± 4.82 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.9 ± 2.7 | 13.3 | 27.6 | 4.58 ± 2.13 |
| `aspidites-solver/aoc -i input-pting -d 2` | 16.0 ± 2.9 | 13.2 | 29.5 | 4.62 ± 2.17 |
| `kcen/2022/02/solve input-aspidites` | 3.8 ± 1.7 | 1.0 | 12.1 | 1.08 ± 0.67 |
| `kcen/2022/02/solve input-kcen` | 3.7 ± 1.7 | 1.4 | 18.9 | 1.06 ± 0.68 |
| `kcen/2022/02/solve input-lanjian` | 3.6 ± 1.4 | 1.3 | 15.0 | 1.05 ± 0.61 |
| `kcen/2022/02/solve input-mattcl` | 3.5 ± 1.5 | 1.2 | 13.2 | 1.00 |
| `kcen/2022/02/solve input-pting` | 3.8 ± 1.2 | 1.2 | 8.4 | 1.10 ± 0.59 |
| `lanjian/day_02 input-aspidites` | 3.9 ± 1.3 | 1.5 | 13.0 | 1.12 ± 0.62 |
| `lanjian/day_02 input-kcen` | 4.5 ± 2.0 | 2.2 | 34.4 | 1.30 ± 0.80 |
| `lanjian/day_02 input-lanjian` | 4.0 ± 2.5 | 1.4 | 23.2 | 1.15 ± 0.87 |
| `lanjian/day_02 input-mattcl` | 4.0 ± 1.3 | 1.9 | 9.8 | 1.16 ± 0.62 |
| `lanjian/day_02 input-pting` | 4.0 ± 1.6 | 1.6 | 15.9 | 1.15 ± 0.67 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.5 ± 1.1 | 1.4 | 10.1 | 1.01 ± 0.55 |
| `mattcl-solver/aoc run 2 input-kcen` | 4.1 ± 1.3 | 1.5 | 13.2 | 1.18 ± 0.63 |
| `mattcl-solver/aoc run 2 input-lanjian` | 4.0 ± 1.6 | 1.4 | 16.8 | 1.16 ± 0.68 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.5 ± 1.3 | 1.4 | 10.5 | 1.00 ± 0.58 |
| `mattcl-solver/aoc run 2 input-pting` | 3.7 ± 1.3 | 1.4 | 15.4 | 1.06 ± 0.59 |
| `python pting/day02.py input-aspidites` | 56.7 ± 7.7 | 44.5 | 80.3 | 16.37 ± 7.44 |
| `python pting/day02.py input-kcen` | 83.5 ± 38.8 | 44.7 | 197.9 | 24.10 ± 15.32 |
| `python pting/day02.py input-lanjian` | 62.5 ± 9.2 | 46.9 | 90.9 | 18.05 ± 8.27 |
| `python pting/day02.py input-mattcl` | 57.8 ± 10.5 | 45.3 | 96.4 | 16.68 ± 7.84 |
| `python pting/day02.py input-pting` | 59.5 ± 8.2 | 48.6 | 80.3 | 17.16 ± 7.80 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
