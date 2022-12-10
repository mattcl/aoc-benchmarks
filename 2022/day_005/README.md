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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.5 ± 1.0 | 23.0 | 28.1 | 13.00 ± 6.63 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.6 ± 4.4 | 22.7 | 55.8 | 13.60 ± 7.29 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.4 ± 1.2 | 22.7 | 31.7 | 12.95 ± 6.61 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.5 ± 3.2 | 22.9 | 39.7 | 13.53 ± 7.08 |
| `aspidites-solver/aoc -i input-pting -d 5` | 79.5 ± 62.7 | 23.5 | 353.2 | 42.27 ± 39.64 |
| `kcen/2022/05/solve input-aspidites` | 150.4 ± 14.8 | 127.0 | 190.2 | 79.92 ± 41.37 |
| `kcen/2022/05/solve input-kcen` | 173.9 ± 20.9 | 139.0 | 211.3 | 92.45 ± 48.28 |
| `kcen/2022/05/solve input-lanjian` | 164.0 ± 14.9 | 136.3 | 193.7 | 87.18 ± 45.01 |
| `kcen/2022/05/solve input-mattcl` | 160.5 ± 18.7 | 130.7 | 196.5 | 85.30 ± 44.48 |
| `kcen/2022/05/solve input-pting` | 164.9 ± 23.3 | 136.2 | 211.7 | 87.64 ± 46.23 |
| `lanjian/day_05 input-aspidites` | 2.0 ± 0.9 | 0.5 | 9.5 | 1.06 ± 0.71 |
| `lanjian/day_05 input-kcen` | 2.0 ± 1.0 | 0.3 | 14.0 | 1.08 ± 0.78 |
| `lanjian/day_05 input-lanjian` | 1.9 ± 1.0 | 0.4 | 7.6 | 1.00 |
| `lanjian/day_05 input-mattcl` | 1.9 ± 0.9 | 0.3 | 6.4 | 1.01 ± 0.71 |
| `lanjian/day_05 input-pting` | 1.9 ± 1.0 | 0.1 | 10.7 | 1.03 ± 0.75 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.1 ± 0.8 | 0.7 | 8.3 | 1.12 ± 0.72 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.9 ± 1.8 | 0.9 | 16.6 | 1.53 ± 1.24 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.4 ± 1.2 | 0.7 | 12.0 | 1.26 ± 0.89 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.0 ± 0.9 | 0.3 | 12.3 | 1.09 ± 0.75 |
| `mattcl-solver/aoc run 5 input-pting` | 2.2 ± 1.1 | 0.3 | 12.4 | 1.14 ± 0.83 |
| `python pting/day05.py input-aspidites` | 59.0 ± 7.2 | 46.7 | 83.7 | 31.35 ± 16.38 |
| `python pting/day05.py input-kcen` | 53.7 ± 7.3 | 40.9 | 72.7 | 28.54 ± 15.02 |
| `python pting/day05.py input-lanjian` | 55.4 ± 7.3 | 43.9 | 75.9 | 29.46 ± 15.47 |
| `python pting/day05.py input-mattcl` | 56.3 ± 7.4 | 45.3 | 71.5 | 29.94 ± 15.72 |
| `python pting/day05.py input-pting` | 59.6 ± 6.2 | 47.2 | 68.2 | 31.66 ± 16.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
