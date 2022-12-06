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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.3 ± 2.9 | 11.8 | 37.3 | 8.51 ± 6.31 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 14.2 ± 3.3 | 11.8 | 32.1 | 8.49 ± 6.36 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 13.4 ± 1.4 | 11.5 | 23.4 | 8.00 ± 5.76 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.4 ± 1.4 | 11.7 | 22.9 | 7.97 ± 5.74 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.0 ± 1.7 | 11.7 | 25.0 | 8.37 ± 6.05 |
| `kcen/2022/02/solve input-aspidites` | 2.3 ± 1.3 | 0.3 | 11.5 | 1.35 ± 1.23 |
| `kcen/2022/02/solve input-kcen` | 1.7 ± 1.2 | 0.0 | 12.5 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 2.2 ± 1.8 | 0.0 | 19.3 | 1.34 ± 1.43 |
| `kcen/2022/02/solve input-mattcl` | 1.9 ± 1.1 | 0.1 | 10.7 | 1.16 ± 1.06 |
| `kcen/2022/02/solve input-pting` | 2.2 ± 1.2 | 0.0 | 14.7 | 1.32 ± 1.19 |
| `lanjian/day_02 input-aspidites` | 2.9 ± 1.3 | 0.9 | 12.8 | 1.74 ± 1.46 |
| `lanjian/day_02 input-kcen` | 3.7 ± 1.5 | 0.9 | 12.1 | 2.22 ± 1.83 |
| `lanjian/day_02 input-lanjian` | 2.4 ± 1.2 | 0.4 | 12.8 | 1.44 ± 1.25 |
| `lanjian/day_02 input-mattcl` | 2.8 ± 1.2 | 0.7 | 12.1 | 1.68 ± 1.38 |
| `lanjian/day_02 input-pting` | 2.7 ± 1.3 | 0.7 | 16.2 | 1.62 ± 1.39 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.8 ± 1.3 | 0.4 | 10.7 | 1.66 ± 1.40 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.8 ± 1.3 | 0.6 | 14.4 | 1.68 ± 1.44 |
| `mattcl-solver/aoc run 2 input-lanjian` | 5.6 ± 5.6 | 0.2 | 42.3 | 3.32 ± 4.10 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.8 ± 1.0 | 0.2 | 9.5 | 1.09 ± 0.97 |
| `mattcl-solver/aoc run 2 input-pting` | 2.0 ± 1.2 | 0.4 | 14.8 | 1.21 ± 1.11 |
| `python pting/day02.py input-aspidites` | 58.5 ± 8.2 | 44.8 | 76.2 | 34.94 ± 25.38 |
| `python pting/day02.py input-kcen` | 61.1 ± 8.4 | 48.4 | 83.4 | 36.48 ± 26.48 |
| `python pting/day02.py input-lanjian` | 59.2 ± 8.3 | 43.5 | 78.8 | 35.33 ± 25.67 |
| `python pting/day02.py input-mattcl` | 61.3 ± 8.9 | 46.9 | 87.3 | 36.61 ± 26.62 |
| `python pting/day02.py input-pting` | 63.4 ± 10.1 | 46.3 | 85.3 | 37.83 ± 27.63 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
