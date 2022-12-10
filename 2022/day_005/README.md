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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.5 ± 2.5 | 22.6 | 38.2 | 14.30 ± 7.38 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 24.1 ± 2.8 | 12.0 | 38.3 | 14.09 ± 7.31 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 23.4 ± 1.8 | 12.0 | 29.3 | 13.68 ± 7.00 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 23.2 ± 3.5 | 12.2 | 39.6 | 13.55 ± 7.15 |
| `aspidites-solver/aoc -i input-pting -d 5` | 24.2 ± 2.2 | 12.2 | 35.7 | 14.14 ± 7.26 |
| `kcen/2022/05/solve input-aspidites` | 203.2 ± 55.1 | 137.9 | 314.4 | 118.69 ± 68.12 |
| `kcen/2022/05/solve input-kcen` | 143.8 ± 14.0 | 123.5 | 169.2 | 83.98 ± 43.25 |
| `kcen/2022/05/solve input-lanjian` | 147.3 ± 16.6 | 120.2 | 176.7 | 86.02 ± 44.58 |
| `kcen/2022/05/solve input-mattcl` | 137.8 ± 14.1 | 120.3 | 167.4 | 80.50 ± 41.55 |
| `kcen/2022/05/solve input-pting` | 144.6 ± 13.3 | 117.5 | 170.8 | 84.46 ± 43.42 |
| `lanjian/day_05 input-aspidites` | 2.0 ± 1.3 | 0.1 | 15.5 | 1.17 ± 0.94 |
| `lanjian/day_05 input-kcen` | 1.9 ± 1.2 | 0.1 | 13.1 | 1.12 ± 0.88 |
| `lanjian/day_05 input-lanjian` | 1.7 ± 1.1 | 0.3 | 9.6 | 1.02 ± 0.81 |
| `lanjian/day_05 input-mattcl` | 1.9 ± 1.0 | 0.2 | 13.9 | 1.14 ± 0.84 |
| `lanjian/day_05 input-pting` | 1.8 ± 0.8 | 0.5 | 5.6 | 1.05 ± 0.69 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.3 ± 1.7 | 0.4 | 14.9 | 1.34 ± 1.19 |
| `mattcl-solver/aoc run 5 input-kcen` | 1.8 ± 1.0 | 0.3 | 9.0 | 1.04 ± 0.79 |
| `mattcl-solver/aoc run 5 input-lanjian` | 1.7 ± 0.9 | 0.4 | 7.0 | 1.00 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.1 ± 1.0 | 0.4 | 16.0 | 1.23 ± 0.86 |
| `mattcl-solver/aoc run 5 input-pting` | 2.1 ± 0.9 | 0.5 | 7.6 | 1.25 ± 0.81 |
| `python pting/day05.py input-aspidites` | 53.9 ± 8.7 | 38.3 | 84.4 | 31.50 ± 16.72 |
| `python pting/day05.py input-kcen` | 50.7 ± 6.1 | 41.2 | 67.4 | 29.62 ± 15.40 |
| `python pting/day05.py input-lanjian` | 50.2 ± 5.7 | 41.5 | 69.8 | 29.32 ± 15.21 |
| `python pting/day05.py input-mattcl` | 49.5 ± 5.5 | 40.1 | 62.6 | 28.92 ± 14.98 |
| `python pting/day05.py input-pting` | 51.8 ± 7.6 | 41.5 | 72.7 | 30.28 ± 15.94 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
