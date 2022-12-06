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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 28.3 ± 4.8 | 23.9 | 39.0 | 13.72 ± 6.05 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.8 ± 4.7 | 23.7 | 47.4 | 13.51 ± 5.95 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 28.5 ± 5.1 | 24.0 | 48.8 | 13.83 ± 6.15 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.3 ± 3.0 | 24.0 | 38.4 | 12.76 ± 5.39 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.5 ± 2.2 | 23.7 | 38.1 | 12.38 ± 5.15 |
| `kcen/2022/05/solve input-aspidites` | 173.0 ± 17.4 | 143.0 | 201.2 | 83.90 ± 35.16 |
| `kcen/2022/05/solve input-kcen` | 179.2 ± 23.0 | 139.9 | 221.4 | 86.93 ± 37.09 |
| `kcen/2022/05/solve input-lanjian` | 209.4 ± 22.9 | 169.0 | 260.2 | 101.56 ± 42.79 |
| `kcen/2022/05/solve input-mattcl` | 255.3 ± 124.4 | 151.0 | 474.6 | 123.84 ± 78.62 |
| `kcen/2022/05/solve input-pting` | 166.3 ± 10.9 | 151.8 | 188.5 | 80.68 ± 33.25 |
| `lanjian/day_05 input-aspidites` | 2.5 ± 1.0 | 0.9 | 13.8 | 1.23 ± 0.70 |
| `lanjian/day_05 input-kcen` | 2.5 ± 1.1 | 0.8 | 10.1 | 1.23 ± 0.74 |
| `lanjian/day_05 input-lanjian` | 3.1 ± 1.2 | 0.9 | 11.3 | 1.52 ± 0.83 |
| `lanjian/day_05 input-mattcl` | 3.3 ± 1.3 | 1.0 | 9.8 | 1.59 ± 0.90 |
| `lanjian/day_05 input-pting` | 2.7 ± 1.1 | 1.0 | 13.9 | 1.31 ± 0.74 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.7 ± 1.0 | 1.0 | 8.1 | 1.30 ± 0.72 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.1 ± 0.8 | 0.9 | 6.7 | 1.00 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.3 ± 1.2 | 1.2 | 10.8 | 1.62 ± 0.89 |
| `mattcl-solver/aoc run 5 input-mattcl` | 4.0 ± 1.5 | 1.2 | 15.3 | 1.92 ± 1.08 |
| `mattcl-solver/aoc run 5 input-pting` | 3.3 ± 1.2 | 1.3 | 10.0 | 1.61 ± 0.88 |
| `python pting/day05.py input-aspidites` | 56.8 ± 5.7 | 46.1 | 72.0 | 27.54 ± 11.54 |
| `python pting/day05.py input-kcen` | 69.9 ± 12.2 | 55.6 | 97.5 | 33.89 ± 15.01 |
| `python pting/day05.py input-lanjian` | 69.1 ± 9.6 | 53.8 | 86.1 | 33.52 ± 14.42 |
| `python pting/day05.py input-mattcl` | 64.6 ± 7.1 | 52.2 | 83.0 | 31.31 ± 13.20 |
| `python pting/day05.py input-pting` | 53.6 ± 6.6 | 45.1 | 79.5 | 26.01 ± 11.05 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
