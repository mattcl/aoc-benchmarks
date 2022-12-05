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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.7 ± 1.7 | 11.5 | 22.9 | 11.04 ± 6.69 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.1 ± 0.5 | 11.4 | 16.0 | 10.47 ± 6.20 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.5 ± 0.9 | 11.4 | 22.9 | 10.79 ± 6.42 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.8 ± 0.5 | 11.6 | 14.4 | 11.08 ± 6.56 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.0 ± 0.4 | 11.4 | 13.8 | 10.44 ± 6.17 |
| `kcen/2022/02/solve input-aspidites` | 1.5 ± 0.4 | 0.8 | 4.4 | 1.28 ± 0.84 |
| `kcen/2022/02/solve input-kcen` | 1.2 ± 0.4 | 0.7 | 5.7 | 1.07 ± 0.71 |
| `kcen/2022/02/solve input-lanjian` | 1.2 ± 0.7 | 0.7 | 10.6 | 1.00 |
| `kcen/2022/02/solve input-mattcl` | 1.6 ± 0.6 | 0.7 | 10.6 | 1.39 ± 0.95 |
| `kcen/2022/02/solve input-pting` | 1.8 ± 0.6 | 0.6 | 4.4 | 1.57 ± 1.06 |
| `lanjian/day_02 input-aspidites` | 2.2 ± 1.0 | 1.0 | 16.4 | 1.86 ± 1.39 |
| `lanjian/day_02 input-kcen` | 1.8 ± 0.6 | 1.0 | 8.1 | 1.60 ± 1.08 |
| `lanjian/day_02 input-lanjian` | 1.9 ± 0.5 | 1.1 | 7.5 | 1.64 ± 1.08 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.5 | 0.9 | 10.6 | 1.53 ± 1.02 |
| `lanjian/day_02 input-pting` | 1.7 ± 0.6 | 1.0 | 13.5 | 1.46 ± 1.01 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.0 ± 0.8 | 0.9 | 14.0 | 1.75 ± 1.25 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.5 ± 0.5 | 0.9 | 7.2 | 1.28 ± 0.86 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 0.4 | 0.8 | 4.4 | 1.32 ± 0.85 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.5 ± 0.4 | 0.8 | 4.7 | 1.26 ± 0.82 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 1.0 | 0.8 | 22.5 | 1.39 ± 1.20 |
| `python pting/day02.py input-aspidites` | 40.6 ± 6.0 | 31.9 | 58.4 | 35.15 ± 21.39 |
| `python pting/day02.py input-kcen` | 34.9 ± 3.9 | 29.2 | 46.4 | 30.23 ± 18.17 |
| `python pting/day02.py input-lanjian` | 33.1 ± 2.8 | 28.9 | 46.3 | 28.70 ± 17.12 |
| `python pting/day02.py input-mattcl` | 37.9 ± 5.4 | 30.6 | 52.9 | 32.80 ± 19.93 |
| `python pting/day02.py input-pting` | 36.6 ± 5.4 | 30.8 | 63.4 | 31.70 ± 19.30 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
