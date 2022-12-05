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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.1 ± 0.6 | 11.2 | 14.4 | 11.15 ± 2.55 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 11.8 ± 0.5 | 11.2 | 14.8 | 10.88 ± 2.47 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 11.9 ± 0.7 | 11.1 | 18.5 | 11.00 ± 2.54 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.0 ± 0.8 | 11.3 | 21.9 | 11.09 ± 2.58 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.0 ± 0.6 | 11.3 | 16.7 | 11.10 ± 2.54 |
| `kcen/2022/02/solve input-aspidites` | 1.5 ± 0.4 | 0.8 | 4.0 | 1.38 ± 0.47 |
| `kcen/2022/02/solve input-kcen` | 1.3 ± 0.7 | 0.7 | 13.1 | 1.18 ± 0.69 |
| `kcen/2022/02/solve input-lanjian` | 1.1 ± 0.2 | 0.8 | 3.0 | 1.02 ± 0.31 |
| `kcen/2022/02/solve input-mattcl` | 1.4 ± 0.6 | 0.8 | 7.4 | 1.28 ± 0.59 |
| `kcen/2022/02/solve input-pting` | 1.5 ± 0.4 | 0.7 | 4.0 | 1.35 ± 0.46 |
| `lanjian/day_02 input-aspidites` | 1.9 ± 0.6 | 0.9 | 10.9 | 1.75 ± 0.68 |
| `lanjian/day_02 input-kcen` | 1.4 ± 0.4 | 1.1 | 11.3 | 1.32 ± 0.49 |
| `lanjian/day_02 input-lanjian` | 1.3 ± 0.2 | 1.0 | 2.8 | 1.23 ± 0.32 |
| `lanjian/day_02 input-mattcl` | 1.6 ± 0.5 | 1.0 | 6.0 | 1.44 ± 0.58 |
| `lanjian/day_02 input-pting` | 1.8 ± 0.5 | 1.1 | 10.2 | 1.65 ± 0.62 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.6 ± 0.7 | 0.9 | 10.4 | 1.51 ± 0.71 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.4 | 0.9 | 4.6 | 1.20 ± 0.44 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.1 ± 0.2 | 0.9 | 5.9 | 1.00 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.2 ± 0.3 | 0.8 | 5.7 | 1.07 ± 0.36 |
| `mattcl-solver/aoc run 2 input-pting` | 1.4 ± 0.3 | 0.8 | 3.3 | 1.29 ± 0.39 |
| `python pting/day02.py input-aspidites` | 33.3 ± 2.4 | 28.9 | 40.0 | 30.80 ± 7.24 |
| `python pting/day02.py input-kcen` | 31.9 ± 2.1 | 28.3 | 39.2 | 29.54 ± 6.88 |
| `python pting/day02.py input-lanjian` | 33.3 ± 3.1 | 28.3 | 42.3 | 30.77 ± 7.44 |
| `python pting/day02.py input-mattcl` | 32.8 ± 4.0 | 28.0 | 43.7 | 30.33 ± 7.72 |
| `python pting/day02.py input-pting` | 32.6 ± 3.4 | 28.0 | 49.2 | 30.17 ± 7.44 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
