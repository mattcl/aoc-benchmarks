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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.3 ± 0.4 | 11.5 | 13.7 | 10.21 ± 2.10 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.2 ± 0.7 | 11.4 | 15.7 | 10.13 ± 2.15 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.6 ± 1.5 | 11.5 | 27.6 | 10.51 ± 2.48 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.1 ± 0.8 | 5.4 | 16.1 | 10.05 ± 2.15 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.2 ± 0.7 | 11.3 | 16.0 | 10.13 ± 2.15 |
| `kcen/2022/02/solve input-aspidites` | 1.5 ± 0.3 | 0.9 | 5.9 | 1.24 ± 0.38 |
| `kcen/2022/02/solve input-kcen` | 1.3 ± 0.5 | 0.8 | 5.1 | 1.10 ± 0.45 |
| `kcen/2022/02/solve input-lanjian` | 1.3 ± 0.4 | 0.9 | 9.1 | 1.05 ± 0.39 |
| `kcen/2022/02/solve input-mattcl` | 1.2 ± 0.2 | 0.9 | 3.1 | 1.00 |
| `kcen/2022/02/solve input-pting` | 1.7 ± 0.8 | 0.9 | 13.8 | 1.41 ± 0.70 |
| `lanjian/day_02 input-aspidites` | 1.9 ± 0.4 | 1.3 | 4.8 | 1.58 ± 0.46 |
| `lanjian/day_02 input-kcen` | 2.0 ± 0.6 | 1.2 | 6.6 | 1.67 ± 0.64 |
| `lanjian/day_02 input-lanjian` | 1.6 ± 0.4 | 1.1 | 6.4 | 1.30 ± 0.40 |
| `lanjian/day_02 input-mattcl` | 1.9 ± 0.5 | 1.1 | 6.1 | 1.55 ± 0.51 |
| `lanjian/day_02 input-pting` | 1.8 ± 0.4 | 1.1 | 6.4 | 1.50 ± 0.47 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.8 ± 0.4 | 1.1 | 4.1 | 1.51 ± 0.46 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.4 ± 0.4 | 0.9 | 5.6 | 1.19 ± 0.44 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.3 ± 0.3 | 1.0 | 7.8 | 1.09 ± 0.35 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.6 | 0.9 | 8.7 | 1.42 ± 0.55 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.4 | 1.0 | 5.8 | 1.32 ± 0.41 |
| `python pting/day02.py input-aspidites` | 34.3 ± 3.7 | 29.9 | 49.9 | 28.53 ± 6.57 |
| `python pting/day02.py input-kcen` | 32.5 ± 3.7 | 27.8 | 45.6 | 26.99 ± 6.31 |
| `python pting/day02.py input-lanjian` | 31.6 ± 3.0 | 28.5 | 42.5 | 26.30 ± 5.90 |
| `python pting/day02.py input-mattcl` | 32.9 ± 3.3 | 28.8 | 42.7 | 27.38 ± 6.20 |
| `python pting/day02.py input-pting` | 33.0 ± 3.5 | 28.8 | 47.2 | 27.43 ± 6.32 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
