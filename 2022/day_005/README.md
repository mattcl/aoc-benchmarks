# Day 5 benchmarks

[link to problem](http://adventofcode.com/2022/day/5)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 5)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.1 ± 3.6 | 23.2 | 51.3 | 10.49 ± 4.98 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.3 ± 3.3 | 23.7 | 45.0 | 10.53 ± 4.96 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.8 ± 2.4 | 23.3 | 35.9 | 10.34 ± 4.80 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.5 ± 1.8 | 23.6 | 38.0 | 10.23 ± 4.70 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.3 ± 1.9 | 23.5 | 35.6 | 10.14 ± 4.67 |
| `kcen/2022/05/solve input-aspidites` | 154.4 ± 19.6 | 130.2 | 215.6 | 61.93 ± 29.21 |
| `kcen/2022/05/solve input-kcen` | 163.5 ± 13.7 | 137.6 | 192.8 | 65.59 ± 30.30 |
| `kcen/2022/05/solve input-lanjian` | 163.5 ± 14.2 | 139.9 | 185.4 | 65.60 ± 30.34 |
| `kcen/2022/05/solve input-mattcl` | 158.9 ± 17.7 | 138.4 | 211.6 | 63.74 ± 29.81 |
| `kcen/2022/05/solve input-pting` | 159.9 ± 18.3 | 134.0 | 190.5 | 64.14 ± 30.04 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 1.0 | 0.9 | 12.5 | 1.03 ± 0.63 |
| `lanjian/day_05 input-kcen` | 2.7 ± 1.1 | 0.9 | 12.8 | 1.09 ± 0.67 |
| `lanjian/day_05 input-lanjian` | 2.5 ± 1.2 | 1.0 | 13.1 | 1.02 ± 0.66 |
| `lanjian/day_05 input-mattcl` | 2.6 ± 1.4 | 0.7 | 13.6 | 1.04 ± 0.75 |
| `lanjian/day_05 input-pting` | 3.8 ± 3.3 | 0.9 | 47.8 | 1.52 ± 1.50 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.5 ± 1.1 | 1.0 | 11.1 | 1.00 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.9 ± 1.4 | 1.1 | 22.9 | 1.18 ± 0.76 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.1 ± 1.4 | 1.2 | 12.2 | 1.24 ± 0.79 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.1 ± 1.9 | 1.0 | 15.6 | 1.23 ± 0.95 |
| `mattcl-solver/aoc run 5 input-pting` | 2.6 ± 1.0 | 1.0 | 7.4 | 1.04 ± 0.63 |
| `python pting/day05.py input-aspidites` | 53.4 ± 7.5 | 40.6 | 78.5 | 21.42 ± 10.19 |
| `python pting/day05.py input-kcen` | 55.7 ± 6.8 | 43.8 | 80.7 | 22.36 ± 10.52 |
| `python pting/day05.py input-lanjian` | 55.3 ± 7.1 | 45.2 | 78.2 | 22.19 ± 10.48 |
| `python pting/day05.py input-mattcl` | 57.8 ± 11.7 | 42.6 | 91.1 | 23.18 ± 11.52 |
| `python pting/day05.py input-pting` | 55.4 ± 8.6 | 43.0 | 89.5 | 22.24 ± 10.67 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
