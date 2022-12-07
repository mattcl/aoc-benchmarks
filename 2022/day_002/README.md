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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.8 ± 2.1 | 12.9 | 31.7 | 5.39 ± 2.85 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 15.4 ± 2.9 | 12.6 | 27.9 | 5.61 ± 3.05 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.4 ± 2.6 | 12.8 | 28.0 | 5.63 ± 3.02 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.2 ± 2.2 | 13.0 | 27.3 | 5.53 ± 2.93 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.3 ± 1.7 | 11.7 | 24.9 | 5.22 ± 2.73 |
| `kcen/2022/02/solve input-aspidites` | 3.0 ± 1.6 | 1.0 | 18.5 | 1.11 ± 0.81 |
| `kcen/2022/02/solve input-kcen` | 2.7 ± 1.4 | 1.0 | 14.1 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 4.1 ± 1.5 | 1.4 | 15.2 | 1.50 ± 0.94 |
| `kcen/2022/02/solve input-mattcl` | 3.3 ± 1.6 | 0.9 | 14.3 | 1.20 ± 0.85 |
| `kcen/2022/02/solve input-pting` | 2.8 ± 1.1 | 0.9 | 7.2 | 1.03 ± 0.66 |
| `lanjian/day_02 input-aspidites` | 4.1 ± 1.7 | 1.6 | 20.0 | 1.51 ± 0.99 |
| `lanjian/day_02 input-kcen` | 3.1 ± 1.1 | 1.4 | 9.1 | 1.15 ± 0.70 |
| `lanjian/day_02 input-lanjian` | 4.4 ± 1.6 | 1.5 | 16.4 | 1.61 ± 1.01 |
| `lanjian/day_02 input-mattcl` | 3.9 ± 1.1 | 1.7 | 9.1 | 1.42 ± 0.83 |
| `lanjian/day_02 input-pting` | 6.0 ± 7.5 | 1.3 | 50.5 | 2.20 ± 2.97 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.3 ± 1.4 | 0.9 | 12.8 | 1.20 ± 0.80 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.8 ± 1.1 | 1.0 | 8.3 | 1.03 ± 0.67 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.7 ± 1.4 | 1.0 | 13.7 | 1.34 ± 0.85 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.1 ± 1.4 | 1.1 | 14.7 | 1.15 ± 0.77 |
| `mattcl-solver/aoc run 2 input-pting` | 4.0 ± 2.8 | 1.0 | 23.0 | 1.45 ± 1.25 |
| `python pting/day02.py input-aspidites` | 52.8 ± 6.7 | 42.3 | 72.4 | 19.29 ± 10.12 |
| `python pting/day02.py input-kcen` | 51.2 ± 6.3 | 40.6 | 74.9 | 18.70 ± 9.80 |
| `python pting/day02.py input-lanjian` | 60.3 ± 10.4 | 45.1 | 96.7 | 22.02 ± 11.84 |
| `python pting/day02.py input-mattcl` | 55.3 ± 10.6 | 42.9 | 87.3 | 20.19 ± 10.99 |
| `python pting/day02.py input-pting` | 53.9 ± 6.3 | 43.9 | 76.3 | 19.67 ± 10.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
