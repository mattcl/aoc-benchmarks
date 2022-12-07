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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 23.4 ± 2.1 | 21.2 | 32.6 | 32.23 ± 44.22 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 28.7 ± 8.4 | 22.0 | 60.4 | 39.62 ± 55.45 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.5 ± 3.5 | 21.4 | 39.5 | 33.83 ± 46.56 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.2 ± 6.2 | 21.5 | 52.7 | 36.14 ± 50.19 |
| `aspidites-solver/aoc -i input-pting -d 5` | 29.4 ± 8.5 | 22.2 | 76.8 | 40.54 ± 56.70 |
| `kcen/2022/05/solve input-aspidites` | 182.3 ± 19.2 | 160.2 | 216.4 | 251.42 ± 345.16 |
| `kcen/2022/05/solve input-kcen` | 196.0 ± 24.0 | 158.3 | 238.6 | 270.32 ± 371.51 |
| `kcen/2022/05/solve input-lanjian` | 187.2 ± 17.6 | 154.4 | 209.2 | 258.17 ± 354.21 |
| `kcen/2022/05/solve input-mattcl` | 166.2 ± 18.3 | 140.7 | 195.3 | 229.29 ± 314.88 |
| `kcen/2022/05/solve input-pting` | 186.7 ± 32.5 | 149.2 | 267.7 | 257.50 ± 355.31 |
| `lanjian/day_05 input-aspidites` | 0.8 ± 1.3 | 0.0 | 13.6 | 1.12 ± 2.40 |
| `lanjian/day_05 input-kcen` | 1.9 ± 3.9 | 0.0 | 37.8 | 2.57 ± 6.46 |
| `lanjian/day_05 input-lanjian` | 0.7 ± 1.0 | 0.0 | 10.6 | 1.00 |
| `lanjian/day_05 input-mattcl` | 0.9 ± 2.3 | 0.0 | 52.8 | 1.24 ± 3.58 |
| `lanjian/day_05 input-pting` | 0.8 ± 1.1 | 0.0 | 9.8 | 1.07 ± 2.11 |
| `mattcl-solver/aoc run 5 input-aspidites` | 1.0 ± 1.3 | 0.0 | 10.7 | 1.43 ± 2.63 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.8 ± 5.8 | 0.0 | 37.0 | 5.26 ± 10.75 |
| `mattcl-solver/aoc run 5 input-lanjian` | 0.7 ± 1.4 | 0.0 | 14.0 | 1.03 ± 2.38 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.6 ± 5.9 | 0.0 | 58.4 | 4.93 ± 10.52 |
| `mattcl-solver/aoc run 5 input-pting` | 1.1 ± 1.3 | 0.0 | 11.0 | 1.55 ± 2.77 |
| `python pting/day05.py input-aspidites` | 67.0 ± 10.6 | 50.1 | 98.4 | 92.39 ± 127.31 |
| `python pting/day05.py input-kcen` | 61.5 ± 8.7 | 45.6 | 94.9 | 84.79 ± 116.67 |
| `python pting/day05.py input-lanjian` | 60.6 ± 8.5 | 49.4 | 89.8 | 83.55 ± 114.96 |
| `python pting/day05.py input-mattcl` | 55.8 ± 8.9 | 44.0 | 83.1 | 76.98 ± 106.09 |
| `python pting/day05.py input-pting` | 63.4 ± 9.4 | 47.1 | 88.1 | 87.47 ± 120.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
