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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.4 ± 5.5 | 23.0 | 48.6 | 13.02 ± 6.32 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.4 ± 4.9 | 23.3 | 44.4 | 13.00 ± 6.20 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.8 ± 4.5 | 19.3 | 46.0 | 12.74 ± 6.02 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.3 ± 3.4 | 23.4 | 47.2 | 12.48 ± 5.75 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.1 ± 3.0 | 22.9 | 41.4 | 11.94 ± 5.47 |
| `kcen/2022/05/solve input-aspidites` | 191.0 ± 28.9 | 157.5 | 258.0 | 90.68 ± 42.39 |
| `kcen/2022/05/solve input-kcen` | 166.4 ± 13.1 | 143.9 | 190.2 | 78.97 ± 35.47 |
| `kcen/2022/05/solve input-lanjian` | 155.5 ± 15.3 | 133.4 | 191.0 | 73.80 ± 33.44 |
| `kcen/2022/05/solve input-mattcl` | 187.4 ± 25.8 | 151.1 | 239.3 | 88.96 ± 41.21 |
| `kcen/2022/05/solve input-pting` | 166.7 ± 30.1 | 135.1 | 251.3 | 79.14 ± 37.81 |
| `lanjian/day_05 input-aspidites` | 7.6 ± 11.2 | 1.3 | 104.7 | 3.62 ± 5.53 |
| `lanjian/day_05 input-kcen` | 2.6 ± 1.6 | 0.8 | 10.5 | 1.22 ± 0.92 |
| `lanjian/day_05 input-lanjian` | 3.0 ± 1.3 | 1.3 | 11.1 | 1.43 ± 0.88 |
| `lanjian/day_05 input-mattcl` | 2.1 ± 0.9 | 0.8 | 10.4 | 1.00 |
| `lanjian/day_05 input-pting` | 3.1 ± 2.0 | 0.9 | 29.1 | 1.46 ± 1.13 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.6 ± 2.1 | 1.5 | 28.9 | 1.70 ± 1.24 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.0 ± 1.8 | 1.1 | 19.2 | 1.44 ± 1.05 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.8 ± 1.7 | 0.7 | 12.8 | 1.32 ± 1.00 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.8 ± 1.3 | 0.8 | 12.9 | 1.31 ± 0.84 |
| `mattcl-solver/aoc run 5 input-pting` | 3.7 ± 2.3 | 1.0 | 19.4 | 1.78 ± 1.35 |
| `python pting/day05.py input-aspidites` | 67.6 ± 16.6 | 48.7 | 115.3 | 32.08 ± 16.23 |
| `python pting/day05.py input-kcen` | 65.0 ± 17.1 | 44.6 | 118.7 | 30.84 ± 15.87 |
| `python pting/day05.py input-lanjian` | 60.9 ± 22.6 | 45.4 | 169.9 | 28.89 ± 16.67 |
| `python pting/day05.py input-mattcl` | 58.6 ± 8.2 | 44.9 | 76.9 | 27.82 ± 12.90 |
| `python pting/day05.py input-pting` | 64.8 ± 12.4 | 48.6 | 107.6 | 30.76 ± 14.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
