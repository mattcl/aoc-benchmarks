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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 15.5 ± 3.3 | 12.9 | 35.8 | 6.33 ± 2.63 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 15.2 ± 2.7 | 12.8 | 29.9 | 6.24 ± 2.48 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.7 ± 3.4 | 12.8 | 32.5 | 6.42 ± 2.67 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 14.4 ± 2.7 | 12.6 | 32.1 | 5.90 ± 2.37 |
| `aspidites-solver/aoc -i input-pting -d 2` | 15.2 ± 3.1 | 12.2 | 36.8 | 6.20 ± 2.53 |
| `kcen/2022/02/solve input-aspidites` | 3.5 ± 2.1 | 1.0 | 21.7 | 1.43 ± 1.01 |
| `kcen/2022/02/solve input-kcen` | 3.0 ± 1.3 | 0.9 | 18.1 | 1.24 ± 0.70 |
| `kcen/2022/02/solve input-lanjian` | 3.4 ± 1.4 | 0.9 | 9.1 | 1.40 ± 0.77 |
| `kcen/2022/02/solve input-mattcl` | 2.9 ± 1.3 | 0.8 | 11.4 | 1.17 ± 0.67 |
| `kcen/2022/02/solve input-pting` | 2.9 ± 1.5 | 0.9 | 12.7 | 1.18 ± 0.73 |
| `lanjian/day_02 input-aspidites` | 3.1 ± 1.0 | 1.2 | 11.6 | 1.25 ± 0.60 |
| `lanjian/day_02 input-kcen` | 3.1 ± 1.1 | 1.1 | 12.3 | 1.25 ± 0.62 |
| `lanjian/day_02 input-lanjian` | 3.4 ± 2.0 | 1.2 | 18.3 | 1.39 ± 0.97 |
| `lanjian/day_02 input-mattcl` | 3.2 ± 1.3 | 1.3 | 19.1 | 1.29 ± 0.70 |
| `lanjian/day_02 input-pting` | 3.6 ± 1.4 | 1.5 | 23.0 | 1.48 ± 0.78 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.7 ± 1.4 | 1.0 | 20.4 | 1.09 ± 0.68 |
| `mattcl-solver/aoc run 2 input-kcen` | 3.6 ± 1.3 | 1.0 | 10.9 | 1.46 ± 0.75 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.0 ± 1.2 | 1.0 | 12.5 | 1.23 ± 0.66 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.4 ± 0.9 | 0.9 | 10.3 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 2.6 ± 1.3 | 0.9 | 15.3 | 1.05 ± 0.64 |
| `python pting/day02.py input-aspidites` | 67.2 ± 10.2 | 48.4 | 96.6 | 27.49 ± 10.60 |
| `python pting/day02.py input-kcen` | 58.5 ± 6.7 | 48.1 | 83.3 | 23.92 ± 8.91 |
| `python pting/day02.py input-lanjian` | 58.4 ± 7.1 | 46.5 | 79.4 | 23.88 ± 8.95 |
| `python pting/day02.py input-mattcl` | 59.6 ± 9.1 | 43.2 | 78.4 | 24.36 ± 9.40 |
| `python pting/day02.py input-pting` | 68.3 ± 9.9 | 49.3 | 92.2 | 27.94 ± 10.69 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
