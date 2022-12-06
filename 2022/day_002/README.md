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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.0 ± 1.6 | 12.2 | 24.5 | 5.89 ± 2.76 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 14.2 ± 1.1 | 12.6 | 20.2 | 5.95 ± 2.74 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 17.2 ± 4.9 | 12.7 | 36.6 | 7.23 ± 3.88 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.0 ± 2.2 | 12.6 | 28.9 | 6.28 ± 3.00 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.2 ± 1.9 | 12.2 | 25.7 | 5.98 ± 2.83 |
| `kcen/2022/02/solve input-aspidites` | 2.8 ± 1.4 | 0.8 | 12.5 | 1.17 ± 0.79 |
| `kcen/2022/02/solve input-kcen` | 2.5 ± 1.2 | 0.3 | 9.7 | 1.06 ± 0.69 |
| `kcen/2022/02/solve input-lanjian` | 3.6 ± 1.7 | 0.9 | 12.0 | 1.51 ± 0.99 |
| `kcen/2022/02/solve input-mattcl` | 2.8 ± 1.5 | 0.8 | 10.9 | 1.18 ± 0.84 |
| `kcen/2022/02/solve input-pting` | 2.8 ± 1.4 | 0.7 | 16.9 | 1.17 ± 0.78 |
| `lanjian/day_02 input-aspidites` | 3.0 ± 1.3 | 0.7 | 11.0 | 1.27 ± 0.80 |
| `lanjian/day_02 input-kcen` | 4.0 ± 2.1 | 1.1 | 20.0 | 1.67 ± 1.17 |
| `lanjian/day_02 input-lanjian` | 3.1 ± 1.2 | 1.1 | 10.9 | 1.31 ± 0.78 |
| `lanjian/day_02 input-mattcl` | 3.2 ± 1.2 | 1.2 | 11.7 | 1.34 ± 0.80 |
| `lanjian/day_02 input-pting` | 2.8 ± 1.3 | 0.8 | 12.3 | 1.20 ± 0.77 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.5 ± 1.4 | 0.5 | 13.9 | 1.06 ± 0.76 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.0 ± 1.6 | 0.6 | 22.3 | 1.25 ± 0.89 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.0 ± 1.3 | 0.8 | 9.9 | 1.26 ± 0.81 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.9 ± 1.6 | 0.7 | 20.0 | 1.23 ± 0.88 |
| `mattcl-solver/aoc run 2 input-pting` | 2.4 ± 1.1 | 0.8 | 7.0 | 1.00 |
| `python pting/day02.py input-aspidites` | 57.0 ± 8.4 | 45.0 | 89.4 | 23.96 ± 11.43 |
| `python pting/day02.py input-kcen` | 63.9 ± 9.7 | 48.4 | 97.1 | 26.85 ± 12.85 |
| `python pting/day02.py input-lanjian` | 63.7 ± 11.2 | 48.3 | 97.7 | 26.74 ± 13.02 |
| `python pting/day02.py input-mattcl` | 60.8 ± 8.8 | 44.7 | 81.7 | 25.54 ± 12.17 |
| `python pting/day02.py input-pting` | 79.6 ± 40.2 | 45.8 | 182.5 | 33.43 ± 22.69 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
