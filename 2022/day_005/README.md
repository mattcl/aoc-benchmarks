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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 31.7 ± 9.0 | 23.8 | 70.2 | 14.24 ± 9.34 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.2 ± 5.9 | 21.4 | 50.3 | 12.22 ± 7.69 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 33.5 ± 10.8 | 24.4 | 76.0 | 15.03 ± 10.12 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.5 ± 2.5 | 23.7 | 38.6 | 11.44 ± 6.86 |
| `aspidites-solver/aoc -i input-pting -d 5` | 31.9 ± 8.5 | 23.1 | 51.2 | 14.32 ± 9.29 |
| `kcen/2022/05/solve input-aspidites` | 199.9 ± 51.8 | 150.9 | 349.2 | 89.76 ± 57.90 |
| `kcen/2022/05/solve input-kcen` | 159.7 ± 28.8 | 129.4 | 249.3 | 71.73 ± 44.31 |
| `kcen/2022/05/solve input-lanjian` | 196.6 ± 40.5 | 156.3 | 290.3 | 88.28 ± 55.24 |
| `kcen/2022/05/solve input-mattcl` | 190.1 ± 57.8 | 147.4 | 378.3 | 85.35 ± 56.72 |
| `kcen/2022/05/solve input-pting` | 187.3 ± 28.7 | 144.4 | 260.5 | 84.11 ± 51.34 |
| `lanjian/day_05 input-aspidites` | 2.2 ± 1.3 | 0.7 | 14.1 | 1.00 |
| `lanjian/day_05 input-kcen` | 2.8 ± 1.5 | 0.7 | 16.1 | 1.27 ± 1.01 |
| `lanjian/day_05 input-lanjian` | 2.2 ± 1.4 | 0.6 | 11.6 | 1.00 ± 0.88 |
| `lanjian/day_05 input-mattcl` | 3.5 ± 1.8 | 0.6 | 19.1 | 1.55 ± 1.23 |
| `lanjian/day_05 input-pting` | 2.4 ± 1.3 | 0.8 | 16.3 | 1.06 ± 0.87 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.4 ± 1.0 | 1.0 | 9.5 | 1.08 ± 0.78 |
| `mattcl-solver/aoc run 5 input-kcen` | 5.6 ± 4.4 | 1.0 | 44.8 | 2.53 ± 2.48 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.6 ± 1.5 | 0.8 | 14.7 | 1.16 ± 0.96 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.3 ± 1.6 | 0.8 | 13.3 | 1.47 ± 1.13 |
| `mattcl-solver/aoc run 5 input-pting` | 2.5 ± 1.7 | 0.7 | 12.3 | 1.10 ± 0.99 |
| `python pting/day05.py input-aspidites` | 68.6 ± 20.3 | 50.9 | 141.0 | 30.82 ± 20.37 |
| `python pting/day05.py input-kcen` | 67.0 ± 28.2 | 44.9 | 175.0 | 30.07 ± 21.82 |
| `python pting/day05.py input-lanjian` | 83.8 ± 41.5 | 44.7 | 205.0 | 37.64 ± 29.01 |
| `python pting/day05.py input-mattcl` | 74.7 ± 38.8 | 46.3 | 221.5 | 33.56 ± 26.40 |
| `python pting/day05.py input-pting` | 67.7 ± 20.3 | 52.3 | 145.3 | 30.39 ± 20.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
