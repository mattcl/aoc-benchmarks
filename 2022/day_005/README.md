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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.0 ± 3.2 | 23.9 | 38.1 | 9.06 ± 3.82 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 38.6 ± 18.7 | 24.3 | 102.6 | 12.96 ± 8.19 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.5 ± 2.8 | 23.9 | 40.5 | 8.90 ± 3.72 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.4 ± 4.4 | 24.1 | 59.9 | 9.21 ± 4.00 |
| `aspidites-solver/aoc -i input-pting -d 5` | 31.2 ± 8.2 | 23.8 | 62.0 | 10.49 ± 5.06 |
| `kcen/2022/05/solve input-aspidites` | 166.1 ± 16.4 | 144.9 | 194.0 | 55.79 ± 23.21 |
| `kcen/2022/05/solve input-kcen` | 184.4 ± 20.5 | 156.3 | 217.8 | 61.91 ± 25.95 |
| `kcen/2022/05/solve input-lanjian` | 172.8 ± 17.9 | 153.8 | 227.2 | 58.03 ± 24.21 |
| `kcen/2022/05/solve input-mattcl` | 173.0 ± 15.7 | 143.7 | 201.1 | 58.11 ± 24.07 |
| `kcen/2022/05/solve input-pting` | 180.6 ± 21.1 | 149.9 | 224.7 | 60.64 ± 25.51 |
| `lanjian/day_05 input-aspidites` | 3.2 ± 1.3 | 0.8 | 11.2 | 1.08 ± 0.62 |
| `lanjian/day_05 input-kcen` | 3.8 ± 2.1 | 1.3 | 17.6 | 1.27 ± 0.86 |
| `lanjian/day_05 input-lanjian` | 3.0 ± 1.2 | 1.0 | 9.1 | 1.00 |
| `lanjian/day_05 input-mattcl` | 3.5 ± 2.3 | 1.2 | 57.6 | 1.17 ± 0.90 |
| `lanjian/day_05 input-pting` | 3.6 ± 1.7 | 1.2 | 22.6 | 1.22 ± 0.75 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.5 ± 1.4 | 1.1 | 10.1 | 1.16 ± 0.66 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.6 ± 1.9 | 1.3 | 15.1 | 1.21 ± 0.81 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.6 ± 1.3 | 1.4 | 15.4 | 1.21 ± 0.66 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.5 ± 1.1 | 1.1 | 9.3 | 1.18 ± 0.61 |
| `mattcl-solver/aoc run 5 input-pting` | 3.2 ± 1.6 | 1.0 | 13.4 | 1.07 ± 0.70 |
| `python pting/day05.py input-aspidites` | 62.4 ± 8.8 | 46.7 | 79.3 | 20.96 ± 8.98 |
| `python pting/day05.py input-kcen` | 67.5 ± 10.6 | 53.0 | 94.2 | 22.68 ± 9.84 |
| `python pting/day05.py input-lanjian` | 59.8 ± 8.8 | 46.7 | 83.1 | 20.10 ± 8.65 |
| `python pting/day05.py input-mattcl` | 84.5 ± 33.3 | 52.1 | 184.2 | 28.39 ± 16.03 |
| `python pting/day05.py input-pting` | 60.9 ± 8.7 | 45.4 | 91.5 | 20.44 ± 8.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
