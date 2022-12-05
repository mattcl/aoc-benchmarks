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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.1 ± 0.5 | 11.4 | 15.1 | 11.18 ± 3.86 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.1 ± 1.5 | 11.2 | 25.4 | 11.19 ± 4.07 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 11.9 ± 0.9 | 11.2 | 19.6 | 11.00 ± 3.85 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.3 ± 0.7 | 11.6 | 17.7 | 11.33 ± 3.93 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.4 ± 1.3 | 11.5 | 30.5 | 11.41 ± 4.09 |
| `kcen/2022/02/solve input-aspidites` | 1.5 ± 0.7 | 0.8 | 9.7 | 1.42 ± 0.80 |
| `kcen/2022/02/solve input-kcen` | 1.1 ± 0.4 | 0.7 | 6.6 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 1.2 ± 0.4 | 0.8 | 5.2 | 1.14 ± 0.52 |
| `kcen/2022/02/solve input-mattcl` | 1.3 ± 0.4 | 0.7 | 6.6 | 1.17 ± 0.56 |
| `kcen/2022/02/solve input-pting` | 1.7 ± 0.6 | 0.8 | 4.1 | 1.56 ± 0.77 |
| `lanjian/day_02 input-aspidites` | 1.8 ± 0.7 | 1.1 | 13.6 | 1.68 ± 0.85 |
| `lanjian/day_02 input-kcen` | 1.7 ± 0.4 | 1.1 | 4.1 | 1.62 ± 0.67 |
| `lanjian/day_02 input-lanjian` | 1.7 ± 0.7 | 1.0 | 8.7 | 1.59 ± 0.85 |
| `lanjian/day_02 input-mattcl` | 1.3 ± 0.3 | 1.0 | 3.2 | 1.25 ± 0.49 |
| `lanjian/day_02 input-pting` | 1.7 ± 0.5 | 1.1 | 9.6 | 1.55 ± 0.71 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.4 ± 0.4 | 0.8 | 3.9 | 1.30 ± 0.56 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.6 ± 0.4 | 0.9 | 4.2 | 1.52 ± 0.65 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.6 ± 0.7 | 0.8 | 12.2 | 1.50 ± 0.82 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.4 ± 0.6 | 0.8 | 11.2 | 1.28 ± 0.69 |
| `mattcl-solver/aoc run 2 input-pting` | 1.4 ± 0.7 | 0.8 | 10.4 | 1.29 ± 0.76 |
| `python pting/day02.py input-aspidites` | 37.4 ± 6.7 | 29.1 | 72.8 | 34.48 ± 13.33 |
| `python pting/day02.py input-kcen` | 30.7 ± 1.8 | 28.1 | 37.0 | 28.37 ± 9.85 |
| `python pting/day02.py input-lanjian` | 33.4 ± 4.0 | 28.8 | 55.1 | 30.79 ± 11.15 |
| `python pting/day02.py input-mattcl` | 32.3 ± 3.0 | 28.5 | 47.4 | 29.79 ± 10.56 |
| `python pting/day02.py input-pting` | 34.4 ± 4.0 | 29.1 | 50.3 | 31.75 ± 11.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
