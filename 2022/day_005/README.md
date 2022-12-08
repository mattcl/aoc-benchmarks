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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.4 ± 2.6 | 13.6 | 39.0 | 10.41 ± 7.47 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.7 ± 4.4 | 23.1 | 61.8 | 10.53 ± 7.71 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.2 ± 4.7 | 23.2 | 62.3 | 10.74 ± 7.88 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 28.8 ± 7.2 | 13.7 | 55.0 | 11.78 ± 8.89 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.4 ± 3.0 | 12.8 | 35.2 | 10.40 ± 7.50 |
| `kcen/2022/05/solve input-aspidites` | 155.1 ± 12.9 | 132.5 | 174.4 | 63.49 ± 45.46 |
| `kcen/2022/05/solve input-kcen` | 160.8 ± 12.5 | 143.9 | 189.4 | 65.79 ± 47.07 |
| `kcen/2022/05/solve input-lanjian` | 151.3 ± 19.3 | 122.8 | 190.7 | 61.90 ± 44.73 |
| `kcen/2022/05/solve input-mattcl` | 284.2 ± 135.6 | 138.8 | 522.0 | 116.31 ± 99.61 |
| `kcen/2022/05/solve input-pting` | 160.9 ± 11.9 | 138.9 | 180.6 | 65.85 ± 47.09 |
| `lanjian/day_05 input-aspidites` | 2.8 ± 1.4 | 0.9 | 14.6 | 1.16 ± 1.01 |
| `lanjian/day_05 input-kcen` | 2.8 ± 1.6 | 0.8 | 19.0 | 1.16 ± 1.05 |
| `lanjian/day_05 input-lanjian` | 2.4 ± 1.7 | 0.8 | 18.4 | 1.00 |
| `lanjian/day_05 input-mattcl` | 2.6 ± 1.4 | 0.7 | 12.1 | 1.06 ± 0.96 |
| `lanjian/day_05 input-pting` | 2.5 ± 1.5 | 0.7 | 16.8 | 1.01 ± 0.96 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.4 ± 1.6 | 1.2 | 12.2 | 1.39 ± 1.19 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.9 ± 1.1 | 0.8 | 10.8 | 1.18 ± 0.95 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.7 ± 1.7 | 0.9 | 27.2 | 1.09 ± 1.04 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.6 ± 1.8 | 0.6 | 30.6 | 1.08 ± 1.06 |
| `mattcl-solver/aoc run 5 input-pting` | 2.8 ± 1.0 | 1.1 | 8.6 | 1.15 ± 0.92 |
| `python pting/day05.py input-aspidites` | 53.9 ± 6.9 | 44.5 | 71.4 | 22.05 ± 15.94 |
| `python pting/day05.py input-kcen` | 56.8 ± 7.5 | 47.1 | 75.2 | 23.24 ± 16.81 |
| `python pting/day05.py input-lanjian` | 53.6 ± 7.4 | 43.5 | 73.9 | 21.93 ± 15.89 |
| `python pting/day05.py input-mattcl` | 55.5 ± 9.2 | 42.7 | 85.5 | 22.70 ± 16.57 |
| `python pting/day05.py input-pting` | 57.1 ± 8.2 | 41.4 | 80.5 | 23.36 ± 16.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
