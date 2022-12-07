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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 13.5 ± 2.0 | 10.8 | 24.2 | 10.34 ± 11.27 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 13.6 ± 2.8 | 11.0 | 29.1 | 10.42 ± 11.44 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 13.0 ± 2.1 | 11.0 | 24.6 | 9.97 ± 10.88 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 14.1 ± 3.3 | 11.2 | 33.6 | 10.81 ± 11.94 |
| `aspidites-solver/aoc -i input-pting -d 2` | 13.7 ± 3.1 | 11.2 | 27.4 | 10.49 ± 11.57 |
| `kcen/2022/02/solve input-aspidites` | 1.3 ± 1.4 | 0.0 | 10.9 | 1.00 |
| `kcen/2022/02/solve input-kcen` | 2.4 ± 1.9 | 0.0 | 12.2 | 1.86 ± 2.47 |
| `kcen/2022/02/solve input-lanjian` | 2.0 ± 1.5 | 0.0 | 13.0 | 1.55 ± 2.04 |
| `kcen/2022/02/solve input-mattcl` | 1.9 ± 2.9 | 0.0 | 25.5 | 1.46 ± 2.73 |
| `kcen/2022/02/solve input-pting` | 2.2 ± 1.7 | 0.0 | 13.3 | 1.70 ± 2.27 |
| `lanjian/day_02 input-aspidites` | 2.9 ± 1.9 | 0.5 | 13.3 | 2.24 ± 2.82 |
| `lanjian/day_02 input-kcen` | 2.9 ± 3.0 | 0.3 | 19.5 | 2.19 ± 3.28 |
| `lanjian/day_02 input-lanjian` | 2.1 ± 1.5 | 0.1 | 12.5 | 1.58 ± 2.03 |
| `lanjian/day_02 input-mattcl` | 2.5 ± 1.9 | 0.0 | 11.2 | 1.88 ± 2.50 |
| `lanjian/day_02 input-pting` | 6.9 ± 9.3 | 0.2 | 69.0 | 5.29 ± 9.12 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.4 ± 2.0 | 0.1 | 20.3 | 1.80 ± 2.48 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.0 ± 1.4 | 0.0 | 12.6 | 1.50 ± 1.96 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.7 ± 2.2 | 0.0 | 19.4 | 2.11 ± 2.85 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.0 ± 1.8 | 0.0 | 14.6 | 1.51 ± 2.13 |
| `mattcl-solver/aoc run 2 input-pting` | 2.0 ± 2.0 | 0.0 | 23.5 | 1.52 ± 2.22 |
| `python pting/day02.py input-aspidites` | 51.4 ± 14.2 | 39.5 | 123.4 | 39.37 ± 43.84 |
| `python pting/day02.py input-kcen` | 54.9 ± 28.2 | 34.4 | 166.8 | 42.03 ± 50.22 |
| `python pting/day02.py input-lanjian` | 51.3 ± 12.3 | 38.3 | 117.7 | 39.26 ± 43.38 |
| `python pting/day02.py input-mattcl` | 55.5 ± 28.0 | 38.2 | 168.7 | 42.51 ± 50.64 |
| `python pting/day02.py input-pting` | 58.0 ± 23.9 | 39.4 | 128.7 | 44.40 ± 51.27 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
