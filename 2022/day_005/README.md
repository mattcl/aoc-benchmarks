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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.4 ± 3.1 | 18.7 | 43.5 | 13.09 ± 7.25 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.5 ± 2.3 | 23.2 | 37.7 | 13.11 ± 7.18 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.7 ± 1.4 | 22.7 | 35.2 | 12.70 ± 6.90 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 39.7 ± 22.0 | 23.1 | 147.0 | 20.44 ± 15.81 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.2 ± 3.1 | 23.1 | 38.2 | 13.47 ± 7.45 |
| `kcen/2022/05/solve input-aspidites` | 155.7 ± 13.3 | 133.6 | 177.6 | 80.11 ± 43.81 |
| `kcen/2022/05/solve input-kcen` | 175.1 ± 15.3 | 150.3 | 206.5 | 90.07 ± 49.28 |
| `kcen/2022/05/solve input-lanjian` | 148.1 ± 12.2 | 126.4 | 177.4 | 76.17 ± 41.62 |
| `kcen/2022/05/solve input-mattcl` | 145.8 ± 15.0 | 123.2 | 173.7 | 75.01 ± 41.25 |
| `kcen/2022/05/solve input-pting` | 169.8 ± 11.4 | 148.2 | 191.3 | 87.37 ± 47.55 |
| `lanjian/day_05 input-aspidites` | 2.4 ± 1.4 | 0.6 | 18.6 | 1.22 ± 0.99 |
| `lanjian/day_05 input-kcen` | 2.7 ± 1.4 | 1.0 | 19.1 | 1.41 ± 1.04 |
| `lanjian/day_05 input-lanjian` | 2.8 ± 1.0 | 0.9 | 11.5 | 1.42 ± 0.94 |
| `lanjian/day_05 input-mattcl` | 2.4 ± 1.2 | 0.6 | 10.3 | 1.21 ± 0.89 |
| `lanjian/day_05 input-pting` | 2.6 ± 1.0 | 0.8 | 9.5 | 1.32 ± 0.89 |
| `mattcl-solver/aoc run 5 input-aspidites` | 1.9 ± 1.1 | 0.8 | 17.8 | 1.00 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.9 ± 1.1 | 1.2 | 14.6 | 1.51 ± 1.00 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.9 ± 1.1 | 1.0 | 11.3 | 1.51 ± 0.99 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.4 ± 1.0 | 0.9 | 8.9 | 1.26 ± 0.84 |
| `mattcl-solver/aoc run 5 input-pting` | 2.9 ± 0.9 | 1.1 | 6.6 | 1.51 ± 0.93 |
| `python pting/day05.py input-aspidites` | 58.5 ± 7.7 | 46.0 | 82.5 | 30.11 ± 16.74 |
| `python pting/day05.py input-kcen` | 60.4 ± 10.2 | 45.8 | 93.2 | 31.09 ± 17.59 |
| `python pting/day05.py input-lanjian` | 56.8 ± 6.8 | 43.1 | 76.2 | 29.22 ± 16.16 |
| `python pting/day05.py input-mattcl` | 52.9 ± 7.4 | 39.7 | 72.4 | 27.19 ± 15.16 |
| `python pting/day05.py input-pting` | 57.5 ± 6.8 | 45.1 | 74.5 | 29.59 ± 16.36 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
