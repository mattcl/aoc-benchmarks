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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 11.7 ± 0.5 | 11.3 | 14.4 | 10.69 ± 2.18 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 11.9 ± 0.4 | 11.2 | 13.7 | 10.83 ± 2.20 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 11.8 ± 0.6 | 11.3 | 17.5 | 10.79 ± 2.23 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 11.9 ± 0.5 | 11.2 | 14.0 | 10.82 ± 2.20 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.0 ± 0.7 | 11.2 | 18.2 | 10.90 ± 2.26 |
| `kcen/2022/02/solve input-aspidites` | 1.4 ± 0.7 | 0.9 | 11.2 | 1.30 ± 0.70 |
| `kcen/2022/02/solve input-kcen` | 1.3 ± 0.4 | 0.9 | 5.9 | 1.17 ± 0.42 |
| `kcen/2022/02/solve input-lanjian` | 1.1 ± 0.2 | 0.8 | 2.6 | 1.00 |
| `kcen/2022/02/solve input-mattcl` | 1.7 ± 0.8 | 0.9 | 10.7 | 1.57 ± 0.81 |
| `kcen/2022/02/solve input-pting` | 1.2 ± 0.5 | 0.8 | 8.4 | 1.13 ± 0.47 |
| `lanjian/day_02 input-aspidites` | 1.7 ± 1.1 | 1.1 | 19.9 | 1.57 ± 1.05 |
| `lanjian/day_02 input-kcen` | 1.7 ± 0.4 | 1.2 | 4.1 | 1.57 ± 0.47 |
| `lanjian/day_02 input-lanjian` | 1.5 ± 0.4 | 0.9 | 4.9 | 1.33 ± 0.43 |
| `lanjian/day_02 input-mattcl` | 1.5 ± 0.3 | 1.1 | 5.7 | 1.39 ± 0.40 |
| `lanjian/day_02 input-pting` | 1.6 ± 0.4 | 1.2 | 5.6 | 1.48 ± 0.50 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.2 ± 0.2 | 0.9 | 3.0 | 1.10 ± 0.31 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.4 ± 0.4 | 0.9 | 4.6 | 1.29 ± 0.44 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.4 ± 0.6 | 0.9 | 8.3 | 1.25 ± 0.58 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.2 ± 0.2 | 0.9 | 3.4 | 1.13 ± 0.31 |
| `mattcl-solver/aoc run 2 input-pting` | 1.4 ± 0.6 | 1.0 | 11.2 | 1.28 ± 0.58 |
| `python pting/day02.py input-aspidites` | 34.0 ± 7.2 | 28.6 | 86.0 | 30.97 ± 9.02 |
| `python pting/day02.py input-kcen` | 32.7 ± 2.2 | 28.1 | 39.6 | 29.78 ± 6.27 |
| `python pting/day02.py input-lanjian` | 33.0 ± 3.7 | 26.9 | 44.0 | 30.02 ± 6.88 |
| `python pting/day02.py input-mattcl` | 37.2 ± 9.7 | 28.2 | 84.4 | 33.83 ± 11.12 |
| `python pting/day02.py input-pting` | 31.8 ± 2.7 | 27.9 | 42.3 | 28.95 ± 6.29 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
