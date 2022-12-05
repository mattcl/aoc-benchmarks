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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.7 ± 0.4 | 11.8 | 14.9 | 9.88 ± 2.38 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.3 ± 0.5 | 11.6 | 17.0 | 9.59 ± 2.33 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.2 ± 0.5 | 11.6 | 14.2 | 9.52 ± 2.30 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.3 ± 2.1 | 11.7 | 28.1 | 10.32 ± 2.94 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.3 ± 1.1 | 11.4 | 22.4 | 9.55 ± 2.42 |
| `kcen/2022/02/solve input-aspidites` | 1.6 ± 0.6 | 0.8 | 10.4 | 1.26 ± 0.55 |
| `kcen/2022/02/solve input-kcen` | 1.4 ± 0.4 | 0.9 | 3.9 | 1.08 ± 0.40 |
| `kcen/2022/02/solve input-lanjian` | 1.5 ± 0.4 | 0.9 | 4.3 | 1.13 ± 0.40 |
| `kcen/2022/02/solve input-mattcl` | 1.8 ± 1.0 | 0.9 | 12.8 | 1.42 ± 0.84 |
| `kcen/2022/02/solve input-pting` | 1.5 ± 0.4 | 0.8 | 5.1 | 1.20 ± 0.45 |
| `lanjian/day_02 input-aspidites` | 1.6 ± 0.3 | 1.1 | 4.0 | 1.22 ± 0.38 |
| `lanjian/day_02 input-kcen` | 1.6 ± 0.4 | 1.0 | 4.4 | 1.21 ± 0.41 |
| `lanjian/day_02 input-lanjian` | 1.6 ± 0.5 | 1.1 | 10.8 | 1.22 ± 0.51 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.4 | 1.1 | 5.0 | 1.40 ± 0.45 |
| `lanjian/day_02 input-pting` | 1.8 ± 0.6 | 1.1 | 7.4 | 1.38 ± 0.55 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.6 ± 0.8 | 0.9 | 13.2 | 1.26 ± 0.71 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.3 | 0.9 | 3.8 | 1.04 ± 0.36 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.3 ± 0.3 | 0.9 | 4.9 | 1.00 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.8 | 1.0 | 14.8 | 1.35 ± 0.71 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.4 | 0.9 | 4.0 | 1.25 ± 0.42 |
| `python pting/day02.py input-aspidites` | 35.8 ± 6.2 | 28.1 | 66.5 | 27.84 ± 8.21 |
| `python pting/day02.py input-kcen` | 32.3 ± 2.9 | 28.4 | 43.4 | 25.10 ± 6.39 |
| `python pting/day02.py input-lanjian` | 33.3 ± 3.5 | 29.3 | 44.8 | 25.91 ± 6.77 |
| `python pting/day02.py input-mattcl` | 34.6 ± 4.0 | 28.8 | 54.4 | 26.90 ± 7.13 |
| `python pting/day02.py input-pting` | 32.8 ± 3.0 | 29.1 | 42.6 | 25.54 ± 6.54 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
