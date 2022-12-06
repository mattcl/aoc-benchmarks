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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.1 ± 3.5 | 23.5 | 40.9 | 12.85 ± 6.09 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.6 ± 2.4 | 23.1 | 36.6 | 12.60 ± 5.84 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.8 ± 3.4 | 23.6 | 38.8 | 13.18 ± 6.21 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.0 ± 4.7 | 23.6 | 52.7 | 13.29 ± 6.47 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.3 ± 3.6 | 23.4 | 36.8 | 12.93 ± 6.13 |
| `kcen/2022/05/solve input-aspidites` | 166.7 ± 19.8 | 137.9 | 215.5 | 82.01 ± 38.51 |
| `kcen/2022/05/solve input-kcen` | 170.6 ± 21.1 | 137.8 | 211.7 | 83.95 ± 39.53 |
| `kcen/2022/05/solve input-lanjian` | 170.2 ± 34.1 | 135.9 | 268.1 | 83.73 ± 41.57 |
| `kcen/2022/05/solve input-mattcl` | 156.5 ± 15.3 | 143.4 | 206.7 | 77.01 ± 35.79 |
| `kcen/2022/05/solve input-pting` | 157.5 ± 22.1 | 133.9 | 219.4 | 77.48 ± 36.84 |
| `lanjian/day_05 input-aspidites` | 2.3 ± 1.0 | 0.6 | 8.0 | 1.14 ± 0.72 |
| `lanjian/day_05 input-kcen` | 2.6 ± 1.1 | 0.6 | 8.2 | 1.28 ± 0.79 |
| `lanjian/day_05 input-lanjian` | 2.2 ± 1.4 | 0.5 | 12.8 | 1.08 ± 0.83 |
| `lanjian/day_05 input-mattcl` | 2.7 ± 1.4 | 0.7 | 14.8 | 1.33 ± 0.91 |
| `lanjian/day_05 input-pting` | 2.9 ± 1.9 | 0.6 | 32.2 | 1.42 ± 1.14 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.9 ± 1.9 | 0.7 | 21.9 | 1.44 ± 1.15 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.2 ± 1.4 | 0.9 | 14.1 | 1.57 ± 1.01 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.5 ± 1.1 | 0.6 | 14.4 | 1.22 ± 0.79 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.9 ± 1.1 | 0.7 | 9.8 | 1.41 ± 0.83 |
| `mattcl-solver/aoc run 5 input-pting` | 2.0 ± 0.9 | 0.6 | 5.0 | 1.00 |
| `python pting/day05.py input-aspidites` | 61.8 ± 9.4 | 50.8 | 85.8 | 30.40 ± 14.56 |
| `python pting/day05.py input-kcen` | 63.1 ± 9.0 | 50.2 | 89.9 | 31.07 ± 14.79 |
| `python pting/day05.py input-lanjian` | 60.6 ± 10.4 | 46.9 | 91.0 | 29.80 ± 14.48 |
| `python pting/day05.py input-mattcl` | 59.5 ± 11.1 | 45.7 | 108.1 | 29.29 ± 14.38 |
| `python pting/day05.py input-pting` | 66.5 ± 10.8 | 51.9 | 102.2 | 32.73 ± 15.79 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
