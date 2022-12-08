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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.6 ± 4.5 | 23.9 | 56.9 | 9.20 ± 4.14 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.1 ± 2.3 | 23.6 | 37.1 | 9.01 ± 3.83 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.7 ± 3.2 | 23.8 | 46.5 | 9.21 ± 3.99 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 28.5 ± 4.9 | 24.0 | 45.3 | 9.85 ± 4.43 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.8 ± 3.5 | 23.6 | 39.5 | 9.26 ± 4.04 |
| `kcen/2022/05/solve input-aspidites` | 187.6 ± 25.2 | 161.1 | 230.9 | 64.81 ± 28.37 |
| `kcen/2022/05/solve input-kcen` | 179.9 ± 28.3 | 146.4 | 221.7 | 62.15 ± 27.68 |
| `kcen/2022/05/solve input-lanjian` | 166.2 ± 18.9 | 142.7 | 212.2 | 57.42 ± 24.79 |
| `kcen/2022/05/solve input-mattcl` | 172.8 ± 20.3 | 145.7 | 212.9 | 59.68 ± 25.83 |
| `kcen/2022/05/solve input-pting` | 250.5 ± 95.0 | 156.8 | 501.7 | 86.53 ± 48.75 |
| `lanjian/day_05 input-aspidites` | 3.0 ± 1.1 | 1.1 | 8.9 | 1.05 ± 0.57 |
| `lanjian/day_05 input-kcen` | 3.3 ± 1.0 | 1.0 | 9.0 | 1.13 ± 0.59 |
| `lanjian/day_05 input-lanjian` | 3.2 ± 1.8 | 1.1 | 41.8 | 1.11 ± 0.78 |
| `lanjian/day_05 input-mattcl` | 3.2 ± 1.4 | 1.1 | 11.4 | 1.10 ± 0.66 |
| `lanjian/day_05 input-pting` | 2.9 ± 1.2 | 0.8 | 13.1 | 1.00 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.7 ± 1.5 | 1.2 | 13.7 | 1.29 ± 0.74 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.9 ± 1.3 | 1.0 | 13.3 | 1.36 ± 0.73 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.9 ± 1.9 | 1.4 | 25.5 | 1.35 ± 0.87 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.5 ± 1.3 | 1.2 | 9.4 | 1.20 ± 0.67 |
| `mattcl-solver/aoc run 5 input-pting` | 3.8 ± 1.4 | 1.7 | 23.7 | 1.31 ± 0.72 |
| `python pting/day05.py input-aspidites` | 64.7 ± 10.3 | 48.1 | 91.4 | 22.35 ± 9.97 |
| `python pting/day05.py input-kcen` | 66.1 ± 8.8 | 50.9 | 93.9 | 22.83 ± 9.99 |
| `python pting/day05.py input-lanjian` | 60.3 ± 9.4 | 48.1 | 94.0 | 20.82 ± 9.27 |
| `python pting/day05.py input-mattcl` | 65.4 ± 10.1 | 49.7 | 95.7 | 22.58 ± 10.03 |
| `python pting/day05.py input-pting` | 61.0 ± 8.2 | 50.7 | 85.0 | 21.07 ± 9.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
