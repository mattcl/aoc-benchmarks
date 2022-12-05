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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.3 ± 0.5 | 11.7 | 14.2 | 9.10 ± 5.98 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.3 ± 0.5 | 11.4 | 14.9 | 9.06 ± 5.96 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.5 ± 1.2 | 11.6 | 25.0 | 9.21 ± 6.10 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.2 ± 0.5 | 11.4 | 15.7 | 8.99 ± 5.91 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.9 ± 0.6 | 11.7 | 16.0 | 9.49 ± 6.24 |
| `kcen/2022/02/solve input-aspidites` | 1.6 ± 0.4 | 0.9 | 4.3 | 1.21 ± 0.86 |
| `kcen/2022/02/solve input-kcen` | 1.4 ± 0.9 | 0.8 | 27.4 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 1.8 ± 0.5 | 0.9 | 7.3 | 1.34 ± 0.96 |
| `kcen/2022/02/solve input-mattcl` | 1.5 ± 0.5 | 0.8 | 6.3 | 1.11 ± 0.83 |
| `kcen/2022/02/solve input-pting` | 2.2 ± 1.4 | 0.9 | 16.3 | 1.61 ± 1.49 |
| `lanjian/day_02 input-aspidites` | 2.0 ± 0.8 | 1.2 | 12.2 | 1.50 ± 1.14 |
| `lanjian/day_02 input-kcen` | 1.9 ± 0.4 | 1.2 | 4.7 | 1.42 ± 0.99 |
| `lanjian/day_02 input-lanjian` | 2.4 ± 1.2 | 1.3 | 18.6 | 1.75 ± 1.46 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.5 | 1.1 | 9.2 | 1.35 ± 0.97 |
| `lanjian/day_02 input-pting` | 2.4 ± 0.6 | 1.2 | 5.9 | 1.79 ± 1.25 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.6 ± 0.6 | 1.0 | 7.0 | 1.22 ± 0.90 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.5 ± 0.4 | 0.9 | 4.6 | 1.10 ± 0.78 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 1.2 | 0.9 | 23.4 | 1.34 ± 1.25 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.5 ± 0.4 | 0.8 | 4.3 | 1.09 ± 0.79 |
| `mattcl-solver/aoc run 2 input-pting` | 1.9 ± 0.7 | 0.9 | 14.5 | 1.42 ± 1.08 |
| `python pting/day02.py input-aspidites` | 37.5 ± 5.8 | 30.3 | 57.0 | 27.66 ± 18.65 |
| `python pting/day02.py input-kcen` | 34.3 ± 3.1 | 28.2 | 46.7 | 25.33 ± 16.77 |
| `python pting/day02.py input-lanjian` | 35.8 ± 3.9 | 30.4 | 48.5 | 26.47 ± 17.61 |
| `python pting/day02.py input-mattcl` | 34.2 ± 5.4 | 28.9 | 60.2 | 25.28 ± 17.06 |
| `python pting/day02.py input-pting` | 35.5 ± 3.9 | 30.3 | 46.8 | 26.24 ± 17.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
