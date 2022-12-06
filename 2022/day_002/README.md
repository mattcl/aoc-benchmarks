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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 21.0 ± 16.2 | 12.5 | 139.9 | 8.44 ± 7.48 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 15.5 ± 4.0 | 12.5 | 40.2 | 6.22 ± 3.14 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.8 ± 3.5 | 12.8 | 32.5 | 6.34 ± 3.08 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.4 ± 3.1 | 13.0 | 42.4 | 6.20 ± 2.95 |
| `aspidites-solver/aoc -i input-pting -d 2` | 16.2 ± 4.6 | 12.3 | 43.0 | 6.49 ± 3.37 |
| `kcen/2022/02/solve input-aspidites` | 2.5 ± 1.1 | 0.7 | 6.2 | 1.00 |
| `kcen/2022/02/solve input-kcen` | 3.0 ± 1.6 | 1.0 | 13.3 | 1.22 ± 0.82 |
| `kcen/2022/02/solve input-lanjian` | 2.7 ± 1.3 | 0.9 | 12.6 | 1.09 ± 0.70 |
| `kcen/2022/02/solve input-mattcl` | 2.7 ± 1.5 | 0.7 | 12.2 | 1.09 ± 0.75 |
| `kcen/2022/02/solve input-pting` | 3.5 ± 1.4 | 1.3 | 9.1 | 1.41 ± 0.83 |
| `lanjian/day_02 input-aspidites` | 3.7 ± 1.7 | 1.7 | 18.7 | 1.50 ± 0.94 |
| `lanjian/day_02 input-kcen` | 4.2 ± 2.0 | 1.7 | 18.6 | 1.70 ± 1.08 |
| `lanjian/day_02 input-lanjian` | 4.1 ± 1.8 | 1.3 | 16.2 | 1.64 ± 1.02 |
| `lanjian/day_02 input-mattcl` | 3.7 ± 1.4 | 1.6 | 15.2 | 1.49 ± 0.86 |
| `lanjian/day_02 input-pting` | 4.2 ± 1.7 | 1.6 | 12.0 | 1.69 ± 0.99 |
| `mattcl-solver/aoc run 2 input-aspidites` | 4.0 ± 1.6 | 1.1 | 14.1 | 1.61 ± 0.95 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.5 ± 2.3 | 0.9 | 27.5 | 1.41 ± 1.10 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.0 ± 1.2 | 1.1 | 11.1 | 1.20 ± 0.71 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.8 ± 1.4 | 1.1 | 17.8 | 1.11 ± 0.75 |
| `mattcl-solver/aoc run 2 input-pting` | 4.9 ± 3.6 | 2.3 | 29.5 | 1.98 ± 1.67 |
| `python pting/day02.py input-aspidites` | 59.9 ± 8.1 | 43.6 | 83.4 | 24.05 ± 10.91 |
| `python pting/day02.py input-kcen` | 57.2 ± 7.1 | 43.2 | 77.3 | 22.99 ± 10.35 |
| `python pting/day02.py input-lanjian` | 59.7 ± 7.6 | 44.1 | 84.7 | 23.97 ± 10.82 |
| `python pting/day02.py input-mattcl` | 61.2 ± 8.0 | 46.0 | 84.3 | 24.57 ± 11.11 |
| `python pting/day02.py input-pting` | 66.3 ± 23.8 | 45.2 | 170.4 | 26.62 ± 14.97 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
