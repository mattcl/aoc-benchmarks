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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 15.5 ± 4.8 | 12.7 | 61.1 | 6.04 ± 3.08 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 15.2 ± 2.3 | 12.7 | 29.9 | 5.91 ± 2.55 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 16.3 ± 3.9 | 12.7 | 36.8 | 6.34 ± 2.96 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.6 ± 3.0 | 12.7 | 36.2 | 6.05 ± 2.70 |
| `aspidites-solver/aoc -i input-pting -d 2` | 16.1 ± 4.6 | 12.5 | 43.4 | 6.24 ± 3.09 |
| `kcen/2022/02/solve input-aspidites` | 3.1 ± 1.8 | 0.9 | 16.9 | 1.19 ± 0.84 |
| `kcen/2022/02/solve input-kcen` | 3.0 ± 1.4 | 0.8 | 10.6 | 1.15 ± 0.71 |
| `kcen/2022/02/solve input-lanjian` | 3.4 ± 1.7 | 0.6 | 18.5 | 1.30 ± 0.84 |
| `kcen/2022/02/solve input-mattcl` | 3.5 ± 1.7 | 0.6 | 16.3 | 1.36 ± 0.85 |
| `kcen/2022/02/solve input-pting` | 2.7 ± 1.3 | 0.7 | 9.4 | 1.04 ± 0.66 |
| `lanjian/day_02 input-aspidites` | 3.3 ± 1.5 | 1.1 | 21.2 | 1.27 ± 0.76 |
| `lanjian/day_02 input-kcen` | 3.8 ± 1.8 | 1.3 | 14.7 | 1.48 ± 0.91 |
| `lanjian/day_02 input-lanjian` | 3.6 ± 1.4 | 1.2 | 11.5 | 1.40 ± 0.79 |
| `lanjian/day_02 input-mattcl` | 3.8 ± 1.3 | 1.4 | 17.5 | 1.46 ± 0.79 |
| `lanjian/day_02 input-pting` | 3.3 ± 1.3 | 1.1 | 11.0 | 1.29 ± 0.72 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.5 ± 1.3 | 0.9 | 10.9 | 1.35 ± 0.74 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.1 ± 1.4 | 1.0 | 15.5 | 1.21 ± 0.73 |
| `mattcl-solver/aoc run 2 input-lanjian` | 6.6 ± 8.1 | 1.0 | 95.4 | 2.55 ± 3.33 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.1 ± 1.4 | 0.8 | 10.9 | 1.20 ± 0.72 |
| `mattcl-solver/aoc run 2 input-pting` | 2.6 ± 1.0 | 0.8 | 6.1 | 1.00 |
| `python pting/day02.py input-aspidites` | 55.1 ± 9.0 | 42.3 | 77.1 | 21.43 ± 9.31 |
| `python pting/day02.py input-kcen` | 55.9 ± 9.3 | 43.6 | 79.7 | 21.74 ± 9.46 |
| `python pting/day02.py input-lanjian` | 55.7 ± 9.1 | 44.2 | 79.2 | 21.66 ± 9.41 |
| `python pting/day02.py input-mattcl` | 55.9 ± 8.8 | 45.7 | 93.0 | 21.74 ± 9.40 |
| `python pting/day02.py input-pting` | 96.3 ± 41.5 | 48.7 | 202.7 | 37.43 ± 22.07 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
