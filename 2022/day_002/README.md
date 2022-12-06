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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 14.7 ± 2.9 | 11.9 | 26.4 | 7.33 ± 5.39 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 14.5 ± 3.4 | 11.4 | 40.1 | 7.26 ± 5.41 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 14.4 ± 3.3 | 12.0 | 34.3 | 7.19 ± 5.35 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.9 ± 3.1 | 11.2 | 29.4 | 6.97 ± 5.17 |
| `aspidites-solver/aoc -i input-pting -d 2` | 14.1 ± 2.5 | 11.7 | 28.4 | 7.05 ± 5.14 |
| `kcen/2022/02/solve input-aspidites` | 2.5 ± 1.6 | 0.0 | 12.4 | 1.23 ± 1.18 |
| `kcen/2022/02/solve input-kcen` | 3.2 ± 1.9 | 0.6 | 10.9 | 1.60 ± 1.47 |
| `kcen/2022/02/solve input-lanjian` | 5.7 ± 6.5 | 0.5 | 51.7 | 2.87 ± 3.84 |
| `kcen/2022/02/solve input-mattcl` | 2.1 ± 1.2 | 0.3 | 8.2 | 1.07 ± 0.98 |
| `kcen/2022/02/solve input-pting` | 3.0 ± 1.5 | 0.5 | 13.0 | 1.52 ± 1.32 |
| `lanjian/day_02 input-aspidites` | 2.9 ± 1.9 | 0.6 | 25.5 | 1.47 ± 1.39 |
| `lanjian/day_02 input-kcen` | 4.9 ± 5.0 | 0.5 | 43.7 | 2.47 ± 3.06 |
| `lanjian/day_02 input-lanjian` | 2.8 ± 1.7 | 0.5 | 13.7 | 1.40 ± 1.30 |
| `lanjian/day_02 input-mattcl` | 3.5 ± 2.6 | 0.5 | 30.7 | 1.75 ± 1.80 |
| `lanjian/day_02 input-pting` | 4.0 ± 3.3 | 1.1 | 25.1 | 2.00 ± 2.17 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.4 ± 1.3 | 0.2 | 14.2 | 1.19 ± 1.08 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.6 ± 1.3 | 0.2 | 14.7 | 1.28 ± 1.13 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.6 ± 1.5 | 0.2 | 11.3 | 1.32 ± 1.19 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.0 ± 1.4 | 0.0 | 10.8 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 2.8 ± 1.7 | 0.6 | 18.0 | 1.38 ± 1.28 |
| `python pting/day02.py input-aspidites` | 66.8 ± 22.9 | 42.7 | 169.5 | 33.37 ± 26.23 |
| `python pting/day02.py input-kcen` | 68.7 ± 27.1 | 46.6 | 157.7 | 34.34 ± 27.82 |
| `python pting/day02.py input-lanjian` | 65.8 ± 16.8 | 47.3 | 156.1 | 32.88 ± 24.72 |
| `python pting/day02.py input-mattcl` | 58.3 ± 7.6 | 47.1 | 80.9 | 29.13 ± 20.95 |
| `python pting/day02.py input-pting` | 67.1 ± 11.6 | 47.7 | 100.8 | 33.52 ± 24.41 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
