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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 39.1 ± 25.1 | 23.1 | 122.0 | 23.33 ± 23.21 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.4 ± 3.8 | 22.3 | 50.1 | 15.14 ± 11.73 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.9 ± 2.5 | 22.6 | 45.3 | 14.89 ± 11.42 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.7 ± 3.8 | 22.6 | 40.6 | 15.34 ± 11.88 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.7 ± 3.8 | 22.4 | 47.5 | 15.34 ± 11.88 |
| `kcen/2022/05/solve input-aspidites` | 200.7 ± 57.1 | 155.1 | 349.4 | 119.83 ± 97.29 |
| `kcen/2022/05/solve input-kcen` | 162.8 ± 18.0 | 139.9 | 201.8 | 97.18 ± 74.68 |
| `kcen/2022/05/solve input-lanjian` | 166.2 ± 17.5 | 145.7 | 204.9 | 99.20 ± 76.16 |
| `kcen/2022/05/solve input-mattcl` | 167.4 ± 14.8 | 146.8 | 196.9 | 99.91 ± 76.49 |
| `kcen/2022/05/solve input-pting` | 166.1 ± 19.9 | 132.2 | 198.7 | 99.18 ± 76.35 |
| `lanjian/day_05 input-aspidites` | 1.8 ± 1.0 | 0.2 | 10.1 | 1.08 ± 1.02 |
| `lanjian/day_05 input-kcen` | 1.7 ± 1.3 | 0.0 | 18.6 | 1.00 |
| `lanjian/day_05 input-lanjian` | 2.7 ± 1.8 | 0.3 | 17.4 | 1.60 ± 1.62 |
| `lanjian/day_05 input-mattcl` | 2.2 ± 1.4 | 0.1 | 13.0 | 1.28 ± 1.27 |
| `lanjian/day_05 input-pting` | 2.2 ± 1.1 | 0.1 | 10.1 | 1.29 ± 1.16 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.5 ± 1.2 | 0.4 | 15.6 | 1.51 ± 1.35 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.2 ± 1.2 | 0.1 | 10.8 | 1.32 ± 1.25 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.3 ± 1.7 | 0.0 | 15.1 | 1.40 ± 1.46 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.4 ± 1.1 | 0.5 | 15.3 | 1.44 ± 1.27 |
| `mattcl-solver/aoc run 5 input-pting` | 2.1 ± 1.0 | 0.2 | 8.0 | 1.28 ± 1.15 |
| `python pting/day05.py input-aspidites` | 56.4 ± 8.6 | 45.7 | 85.5 | 33.68 ± 26.12 |
| `python pting/day05.py input-kcen` | 56.9 ± 7.8 | 46.0 | 78.0 | 33.95 ± 26.23 |
| `python pting/day05.py input-lanjian` | 62.0 ± 10.3 | 46.4 | 83.4 | 37.01 ± 28.80 |
| `python pting/day05.py input-mattcl` | 62.1 ± 10.1 | 46.4 | 95.4 | 37.05 ± 28.81 |
| `python pting/day05.py input-pting` | 53.3 ± 6.1 | 44.6 | 74.9 | 31.83 ± 24.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
