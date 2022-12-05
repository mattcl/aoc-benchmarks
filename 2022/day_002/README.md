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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.3 ± 0.6 | 11.5 | 15.4 | 9.65 ± 3.64 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 13.0 ± 0.9 | 11.8 | 18.0 | 10.18 ± 3.88 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.8 ± 0.8 | 11.5 | 16.0 | 10.08 ± 3.82 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.1 ± 0.9 | 11.7 | 17.4 | 10.29 ± 3.92 |
| `aspidites-solver/aoc -i input-pting -d 2` | 13.0 ± 1.5 | 11.2 | 21.9 | 10.17 ± 3.98 |
| `kcen/2022/02/solve input-aspidites` | 1.6 ± 0.5 | 0.9 | 5.0 | 1.23 ± 0.61 |
| `kcen/2022/02/solve input-kcen` | 2.3 ± 0.9 | 0.9 | 9.0 | 1.77 ± 1.00 |
| `kcen/2022/02/solve input-lanjian` | 1.8 ± 0.6 | 0.8 | 4.9 | 1.38 ± 0.68 |
| `kcen/2022/02/solve input-mattcl` | 1.9 ± 0.6 | 0.8 | 4.4 | 1.46 ± 0.73 |
| `kcen/2022/02/solve input-pting` | 1.3 ± 0.5 | 0.7 | 5.2 | 1.00 |
| `lanjian/day_02 input-aspidites` | 2.9 ± 1.4 | 1.2 | 23.2 | 2.29 ± 1.43 |
| `lanjian/day_02 input-kcen` | 2.8 ± 0.8 | 1.2 | 7.5 | 2.21 ± 1.05 |
| `lanjian/day_02 input-lanjian` | 2.1 ± 0.9 | 1.1 | 17.7 | 1.65 ± 0.94 |
| `lanjian/day_02 input-mattcl` | 2.4 ± 0.8 | 1.1 | 7.7 | 1.88 ± 0.92 |
| `lanjian/day_02 input-pting` | 2.1 ± 0.6 | 0.9 | 5.2 | 1.66 ± 0.80 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.9 ± 0.8 | 0.9 | 9.4 | 1.52 ± 0.88 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.8 ± 0.6 | 0.8 | 4.3 | 1.45 ± 0.73 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.2 ± 1.0 | 1.0 | 10.1 | 1.74 ± 0.99 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.0 ± 0.6 | 0.9 | 5.5 | 1.55 ± 0.74 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.5 | 0.9 | 6.5 | 1.27 ± 0.64 |
| `python pting/day02.py input-aspidites` | 36.3 ± 4.9 | 28.2 | 51.6 | 28.51 ± 11.36 |
| `python pting/day02.py input-kcen` | 41.3 ± 9.4 | 31.2 | 74.9 | 32.41 ± 14.21 |
| `python pting/day02.py input-lanjian` | 36.4 ± 5.5 | 29.0 | 69.2 | 28.61 ± 11.56 |
| `python pting/day02.py input-mattcl` | 39.1 ± 8.0 | 28.5 | 67.3 | 30.69 ± 13.12 |
| `python pting/day02.py input-pting` | 39.7 ± 9.9 | 30.6 | 72.8 | 31.16 ± 14.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
