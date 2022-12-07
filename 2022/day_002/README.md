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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 16.7 ± 5.0 | 12.4 | 41.9 | 6.97 ± 5.30 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 17.3 ± 6.3 | 12.0 | 64.0 | 7.24 ± 5.72 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 16.8 ± 4.8 | 11.1 | 36.2 | 7.03 ± 5.31 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.5 ± 4.0 | 11.9 | 36.8 | 6.46 ± 4.82 |
| `aspidites-solver/aoc -i input-pting -d 2` | 31.0 ± 33.1 | 12.0 | 204.1 | 12.94 ± 16.54 |
| `kcen/2022/02/solve input-aspidites` | 3.1 ± 2.0 | 0.3 | 15.9 | 1.30 ± 1.22 |
| `kcen/2022/02/solve input-kcen` | 2.4 ± 1.7 | 0.1 | 11.4 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 3.4 ± 2.4 | 0.5 | 18.5 | 1.41 ± 1.39 |
| `kcen/2022/02/solve input-mattcl` | 3.5 ± 1.8 | 0.2 | 14.7 | 1.44 ± 1.25 |
| `kcen/2022/02/solve input-pting` | 3.7 ± 2.5 | 0.2 | 21.6 | 1.54 ± 1.50 |
| `lanjian/day_02 input-aspidites` | 4.1 ± 2.1 | 1.0 | 22.2 | 1.73 ± 1.49 |
| `lanjian/day_02 input-kcen` | 3.8 ± 2.3 | 1.0 | 12.8 | 1.60 ± 1.48 |
| `lanjian/day_02 input-lanjian` | 4.2 ± 2.1 | 0.5 | 20.6 | 1.75 ± 1.50 |
| `lanjian/day_02 input-mattcl` | 3.5 ± 3.1 | 0.9 | 53.5 | 1.45 ± 1.65 |
| `lanjian/day_02 input-pting` | 3.6 ± 1.8 | 0.7 | 10.2 | 1.48 ± 1.28 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.9 ± 1.8 | 0.5 | 12.1 | 1.62 ± 1.36 |
| `mattcl-solver/aoc run 2 input-kcen` | 4.0 ± 1.7 | 1.2 | 14.2 | 1.68 ± 1.37 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.9 ± 1.6 | 0.3 | 11.5 | 1.20 ± 1.09 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.4 ± 2.0 | 0.7 | 20.6 | 1.41 ± 1.30 |
| `mattcl-solver/aoc run 2 input-pting` | 2.8 ± 1.5 | 0.3 | 9.0 | 1.16 ± 1.02 |
| `python pting/day02.py input-aspidites` | 61.4 ± 26.5 | 40.2 | 147.5 | 25.63 ± 21.09 |
| `python pting/day02.py input-kcen` | 71.5 ± 29.9 | 42.3 | 170.6 | 29.85 ± 24.35 |
| `python pting/day02.py input-lanjian` | 99.9 ± 65.4 | 45.6 | 307.6 | 41.70 ± 39.98 |
| `python pting/day02.py input-mattcl` | 60.4 ± 23.9 | 41.0 | 155.0 | 25.21 ± 20.29 |
| `python pting/day02.py input-pting` | 64.7 ± 17.8 | 44.6 | 139.1 | 27.00 ± 20.31 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
