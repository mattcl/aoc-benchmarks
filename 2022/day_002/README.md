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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 15.8 ± 4.2 | 12.9 | 57.0 | 5.89 ± 2.73 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 17.2 ± 4.1 | 13.2 | 36.2 | 6.43 ± 2.89 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 15.5 ± 3.0 | 11.9 | 33.6 | 5.80 ± 2.47 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 15.6 ± 3.0 | 13.0 | 35.9 | 5.84 ± 2.48 |
| `aspidites-solver/aoc -i input-pting -d 2` | 18.7 ± 6.6 | 13.3 | 49.1 | 6.98 ± 3.62 |
| `kcen/2022/02/solve input-aspidites` | 3.5 ± 1.4 | 1.3 | 14.2 | 1.30 ± 0.71 |
| `kcen/2022/02/solve input-kcen` | 3.6 ± 2.1 | 1.0 | 20.9 | 1.36 ± 0.94 |
| `kcen/2022/02/solve input-lanjian` | 3.4 ± 1.3 | 1.5 | 14.5 | 1.26 ± 0.68 |
| `kcen/2022/02/solve input-mattcl` | 2.7 ± 1.0 | 0.9 | 8.1 | 1.00 |
| `kcen/2022/02/solve input-pting` | 3.4 ± 1.5 | 0.9 | 15.7 | 1.26 ± 0.73 |
| `lanjian/day_02 input-aspidites` | 3.3 ± 1.2 | 1.4 | 13.2 | 1.25 ± 0.65 |
| `lanjian/day_02 input-kcen` | 3.7 ± 1.3 | 1.5 | 10.0 | 1.39 ± 0.72 |
| `lanjian/day_02 input-lanjian` | 3.8 ± 1.7 | 1.4 | 15.8 | 1.42 ± 0.82 |
| `lanjian/day_02 input-mattcl` | 3.5 ± 1.2 | 1.3 | 11.2 | 1.31 ± 0.66 |
| `lanjian/day_02 input-pting` | 4.2 ± 2.0 | 1.5 | 20.1 | 1.56 ± 0.95 |
| `mattcl-solver/aoc run 2 input-aspidites` | 3.7 ± 1.3 | 1.5 | 12.6 | 1.40 ± 0.72 |
| `mattcl-solver/aoc run 2 input-kcen` | 4.5 ± 2.1 | 1.4 | 27.2 | 1.67 ± 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.4 ± 1.1 | 1.1 | 8.9 | 1.27 ± 0.64 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.0 ± 1.6 | 1.0 | 18.9 | 1.10 ± 0.72 |
| `mattcl-solver/aoc run 2 input-pting` | 6.4 ± 6.3 | 1.2 | 53.7 | 2.37 ± 2.53 |
| `python pting/day02.py input-aspidites` | 56.6 ± 9.6 | 43.6 | 86.9 | 21.15 ± 8.78 |
| `python pting/day02.py input-kcen` | 60.7 ± 7.8 | 48.5 | 77.9 | 22.68 ± 9.07 |
| `python pting/day02.py input-lanjian` | 55.6 ± 9.1 | 45.5 | 91.4 | 20.76 ± 8.56 |
| `python pting/day02.py input-mattcl` | 55.9 ± 9.3 | 45.0 | 81.7 | 20.89 ± 8.64 |
| `python pting/day02.py input-pting` | 60.8 ± 9.8 | 46.7 | 99.6 | 22.70 ± 9.34 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
