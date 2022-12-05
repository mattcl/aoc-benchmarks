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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.3 ± 1.0 | 11.4 | 23.9 | 10.62 ± 2.82 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.0 ± 0.9 | 11.2 | 22.6 | 10.39 ± 2.75 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.0 ± 0.4 | 11.4 | 14.1 | 10.38 ± 2.65 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.6 ± 1.1 | 11.5 | 22.9 | 10.91 ± 2.93 |
| `aspidites-solver/aoc -i input-pting -d 2` | 11.9 ± 0.5 | 11.3 | 14.9 | 10.32 ± 2.64 |
| `kcen/2022/02/solve input-aspidites` | 1.2 ± 0.3 | 0.9 | 3.2 | 1.04 ± 0.34 |
| `kcen/2022/02/solve input-kcen` | 1.2 ± 0.3 | 0.9 | 3.4 | 1.08 ± 0.36 |
| `kcen/2022/02/solve input-lanjian` | 1.4 ± 0.4 | 0.9 | 4.0 | 1.25 ± 0.45 |
| `kcen/2022/02/solve input-mattcl` | 1.7 ± 0.8 | 0.9 | 13.7 | 1.47 ± 0.78 |
| `kcen/2022/02/solve input-pting` | 1.2 ± 0.3 | 0.8 | 4.8 | 1.00 |
| `lanjian/day_02 input-aspidites` | 2.0 ± 0.7 | 1.1 | 10.5 | 1.71 ± 0.78 |
| `lanjian/day_02 input-kcen` | 1.8 ± 0.4 | 1.1 | 3.6 | 1.53 ± 0.49 |
| `lanjian/day_02 input-lanjian` | 2.1 ± 0.6 | 1.3 | 9.0 | 1.79 ± 0.71 |
| `lanjian/day_02 input-mattcl` | 1.9 ± 0.7 | 1.2 | 10.5 | 1.68 ± 0.77 |
| `lanjian/day_02 input-pting` | 1.8 ± 0.8 | 1.1 | 14.2 | 1.55 ± 0.78 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.6 ± 0.7 | 0.8 | 8.6 | 1.37 ± 0.73 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.6 ± 0.6 | 1.0 | 10.1 | 1.39 ± 0.66 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.6 ± 0.4 | 0.9 | 6.0 | 1.40 ± 0.52 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.6 ± 0.9 | 0.9 | 16.2 | 1.40 ± 0.82 |
| `mattcl-solver/aoc run 2 input-pting` | 1.5 ± 0.4 | 0.9 | 4.1 | 1.28 ± 0.50 |
| `python pting/day02.py input-aspidites` | 33.6 ± 5.2 | 28.8 | 66.4 | 29.10 ± 8.62 |
| `python pting/day02.py input-kcen` | 32.6 ± 3.4 | 29.4 | 54.2 | 28.22 ± 7.72 |
| `python pting/day02.py input-lanjian` | 36.6 ± 2.7 | 30.2 | 47.2 | 31.71 ± 8.36 |
| `python pting/day02.py input-mattcl` | 34.7 ± 5.7 | 28.6 | 54.8 | 30.02 ± 9.06 |
| `python pting/day02.py input-pting` | 33.3 ± 3.8 | 28.9 | 45.7 | 28.82 ± 8.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
