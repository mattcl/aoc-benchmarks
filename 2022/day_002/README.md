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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 15.5 ± 2.6 | 12.7 | 28.2 | 5.57 ± 3.12 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 18.1 ± 7.3 | 12.7 | 55.2 | 6.49 ± 4.34 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.8 ± 3.4 | 12.1 | 31.1 | 5.65 ± 3.26 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.2 ± 3.0 | 12.3 | 43.7 | 5.43 ± 3.10 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.6 ± 1.3 | 12.3 | 19.9 | 5.22 ± 2.83 |
| `kcen/2022/02/solve input-aspidites` | 3.4 ± 1.5 | 1.0 | 19.1 | 1.20 ± 0.84 |
| `kcen/2022/02/solve input-kcen` | 3.1 ± 1.8 | 0.8 | 12.1 | 1.11 ± 0.89 |
| `kcen/2022/02/solve input-lanjian` | 3.5 ± 1.6 | 1.1 | 12.5 | 1.27 ± 0.88 |
| `kcen/2022/02/solve input-mattcl` | 2.8 ± 1.5 | 0.7 | 13.0 | 1.00 |
| `kcen/2022/02/solve input-pting` | 3.7 ± 1.7 | 0.9 | 18.0 | 1.31 ± 0.92 |
| `lanjian/day_02 input-aspidites` | 3.7 ± 1.6 | 1.4 | 13.5 | 1.33 ± 0.91 |
| `lanjian/day_02 input-kcen` | 4.4 ± 2.2 | 1.5 | 15.4 | 1.59 ± 1.15 |
| `lanjian/day_02 input-lanjian` | 3.9 ± 1.7 | 1.4 | 16.8 | 1.40 ± 0.97 |
| `lanjian/day_02 input-mattcl` | 3.1 ± 1.3 | 1.2 | 9.2 | 1.12 ± 0.76 |
| `lanjian/day_02 input-pting` | 3.9 ± 1.5 | 1.6 | 10.1 | 1.41 ± 0.92 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.6 ± 1.5 | 1.1 | 13.6 | 1.29 ± 0.88 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.9 ± 1.6 | 1.4 | 15.5 | 1.41 ± 0.95 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.4 ± 1.9 | 1.1 | 12.1 | 1.23 ± 0.94 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.9 ± 1.8 | 1.1 | 24.7 | 1.38 ± 0.98 |
| `mattcl-solver/aoc run 2 input-pting` | 3.8 ± 1.4 | 1.4 | 11.2 | 1.36 ± 0.89 |
| `python pting/day02.py input-aspidites` | 66.1 ± 25.0 | 47.2 | 153.3 | 23.69 ± 15.52 |
| `python pting/day02.py input-kcen` | 57.4 ± 12.0 | 44.7 | 109.7 | 20.58 ± 11.83 |
| `python pting/day02.py input-lanjian` | 63.3 ± 25.3 | 42.0 | 164.2 | 22.67 ± 15.15 |
| `python pting/day02.py input-mattcl` | 58.9 ± 12.7 | 43.1 | 98.4 | 21.10 ± 12.17 |
| `python pting/day02.py input-pting` | 61.7 ± 26.1 | 43.0 | 184.8 | 22.10 ± 15.08 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
