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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.0 ± 0.8 | 11.4 | 23.6 | 10.44 ± 2.76 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.0 ± 0.4 | 11.4 | 13.7 | 10.46 ± 2.68 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.0 ± 0.9 | 5.4 | 19.5 | 10.43 ± 2.76 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.4 ± 0.8 | 11.5 | 17.1 | 10.85 ± 2.85 |
| `aspidites-solver/aoc -i input-pting -d 2` | 11.8 ± 0.5 | 11.2 | 15.2 | 10.29 ± 2.65 |
| `kcen/2022/02/solve input-aspidites` | 1.5 ± 0.7 | 0.8 | 9.7 | 1.27 ± 0.69 |
| `kcen/2022/02/solve input-kcen` | 1.4 ± 0.4 | 0.9 | 4.8 | 1.24 ± 0.46 |
| `kcen/2022/02/solve input-lanjian` | 1.2 ± 0.3 | 0.8 | 3.9 | 1.05 ± 0.36 |
| `kcen/2022/02/solve input-mattcl` | 1.5 ± 0.4 | 0.8 | 3.9 | 1.28 ± 0.47 |
| `kcen/2022/02/solve input-pting` | 1.1 ± 0.3 | 0.8 | 3.3 | 1.00 |
| `lanjian/day_02 input-aspidites` | 1.6 ± 0.4 | 1.1 | 7.6 | 1.42 ± 0.51 |
| `lanjian/day_02 input-kcen` | 1.7 ± 0.4 | 1.1 | 5.8 | 1.49 ± 0.50 |
| `lanjian/day_02 input-lanjian` | 1.8 ± 0.4 | 1.2 | 5.0 | 1.54 ± 0.54 |
| `lanjian/day_02 input-mattcl` | 2.0 ± 0.7 | 1.3 | 7.6 | 1.72 ± 0.74 |
| `lanjian/day_02 input-pting` | 1.4 ± 0.4 | 1.1 | 6.0 | 1.26 ± 0.47 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 0.7 | 0.9 | 10.3 | 1.52 ± 0.73 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.4 ± 0.3 | 0.9 | 3.5 | 1.22 ± 0.41 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 0.4 | 1.0 | 4.6 | 1.30 ± 0.45 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.4 ± 0.5 | 1.0 | 6.7 | 1.25 ± 0.53 |
| `mattcl-solver/aoc run 2 input-pting` | 1.3 ± 0.8 | 0.9 | 14.7 | 1.17 ± 0.75 |
| `python pting/day02.py input-aspidites` | 32.4 ± 3.3 | 27.4 | 48.3 | 28.26 ± 7.74 |
| `python pting/day02.py input-kcen` | 32.8 ± 2.0 | 28.9 | 39.9 | 28.65 ± 7.50 |
| `python pting/day02.py input-lanjian` | 34.1 ± 4.1 | 28.3 | 49.9 | 29.74 ± 8.38 |
| `python pting/day02.py input-mattcl` | 33.5 ± 3.4 | 29.2 | 45.5 | 29.21 ± 7.99 |
| `python pting/day02.py input-pting` | 30.3 ± 2.2 | 27.4 | 40.9 | 26.46 ± 7.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
