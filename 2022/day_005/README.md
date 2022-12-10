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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.1 ± 4.2 | 23.9 | 47.9 | 11.88 ± 4.58 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.3 ± 2.5 | 23.6 | 42.8 | 11.12 ± 4.09 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 31.1 ± 12.9 | 23.3 | 97.9 | 13.62 ± 7.42 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.8 ± 3.0 | 23.7 | 41.0 | 11.33 ± 4.21 |
| `aspidites-solver/aoc -i input-pting -d 5` | 27.2 ± 4.4 | 23.4 | 51.1 | 11.95 ± 4.64 |
| `kcen/2022/05/solve input-aspidites` | 224.9 ± 66.3 | 136.4 | 336.6 | 98.63 ± 45.42 |
| `kcen/2022/05/solve input-kcen` | 171.2 ± 13.7 | 153.9 | 193.5 | 75.11 ± 27.24 |
| `kcen/2022/05/solve input-lanjian` | 165.5 ± 23.8 | 137.7 | 228.0 | 72.59 ± 27.71 |
| `kcen/2022/05/solve input-mattcl` | 178.6 ± 20.6 | 136.7 | 210.3 | 78.33 ± 29.15 |
| `kcen/2022/05/solve input-pting` | 170.2 ± 20.0 | 145.1 | 204.2 | 74.67 ± 27.83 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 1.1 | 1.0 | 15.0 | 1.13 ± 0.61 |
| `lanjian/day_05 input-kcen` | 2.3 ± 0.8 | 0.8 | 6.6 | 1.00 |
| `lanjian/day_05 input-lanjian` | 2.5 ± 0.8 | 0.9 | 6.4 | 1.08 ± 0.51 |
| `lanjian/day_05 input-mattcl` | 3.5 ± 1.6 | 1.1 | 12.5 | 1.56 ± 0.89 |
| `lanjian/day_05 input-pting` | 3.2 ± 1.7 | 1.0 | 19.9 | 1.40 ± 0.90 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.8 ± 1.0 | 1.3 | 10.9 | 1.21 ± 0.62 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.8 ± 1.1 | 1.1 | 9.2 | 1.24 ± 0.64 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.0 ± 0.9 | 1.3 | 10.0 | 1.32 ± 0.61 |
| `mattcl-solver/aoc run 5 input-mattcl` | 4.5 ± 2.7 | 1.5 | 22.2 | 1.96 ± 1.38 |
| `mattcl-solver/aoc run 5 input-pting` | 3.0 ± 1.3 | 1.1 | 15.0 | 1.32 ± 0.73 |
| `python pting/day05.py input-aspidites` | 54.9 ± 8.3 | 44.2 | 72.2 | 24.06 ± 9.26 |
| `python pting/day05.py input-kcen` | 60.4 ± 9.0 | 46.6 | 91.9 | 26.50 ± 10.16 |
| `python pting/day05.py input-lanjian` | 59.6 ± 8.8 | 43.8 | 88.5 | 26.13 ± 10.01 |
| `python pting/day05.py input-mattcl` | 64.7 ± 9.3 | 50.1 | 99.6 | 28.37 ± 10.84 |
| `python pting/day05.py input-pting` | 64.1 ± 9.0 | 50.6 | 92.4 | 28.10 ± 10.70 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
