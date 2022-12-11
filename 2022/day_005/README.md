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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 11.0 ± 0.1 | 10.9 | 11.9 | 17.57 ± 2.02 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 11.4 ± 1.4 | 10.9 | 21.4 | 18.12 ± 3.07 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 11.1 ± 0.7 | 10.8 | 22.7 | 17.75 ± 2.36 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 11.0 ± 0.1 | 10.9 | 11.6 | 17.50 ± 2.01 |
| `aspidites-solver/aoc -i input-pting -d 5` | 11.0 ± 0.2 | 10.9 | 12.8 | 17.57 ± 2.03 |
| `kcen/2022/05/solve input-aspidites` | 61.3 ± 1.0 | 59.5 | 63.5 | 97.63 ± 11.31 |
| `kcen/2022/05/solve input-kcen` | 61.2 ± 0.9 | 59.6 | 63.6 | 97.51 ± 11.26 |
| `kcen/2022/05/solve input-lanjian` | 62.2 ± 1.4 | 59.3 | 65.0 | 98.95 ± 11.56 |
| `kcen/2022/05/solve input-mattcl` | 60.9 ± 1.0 | 59.1 | 64.0 | 96.98 ± 11.23 |
| `kcen/2022/05/solve input-pting` | 61.1 ± 0.9 | 59.5 | 64.4 | 97.22 ± 11.24 |
| `lanjian/day_05 input-aspidites` | 0.6 ± 0.1 | 0.5 | 2.5 | 1.00 |
| `lanjian/day_05 input-kcen` | 0.7 ± 0.2 | 0.5 | 8.1 | 1.04 ± 0.29 |
| `lanjian/day_05 input-lanjian` | 0.7 ± 0.1 | 0.5 | 2.5 | 1.04 ± 0.18 |
| `lanjian/day_05 input-mattcl` | 0.7 ± 0.2 | 0.5 | 3.9 | 1.04 ± 0.29 |
| `lanjian/day_05 input-pting` | 0.6 ± 0.1 | 0.5 | 6.0 | 1.02 ± 0.25 |
| `mattcl-solver/aoc run 5 input-aspidites` | 0.7 ± 0.1 | 0.6 | 2.6 | 1.06 ± 0.18 |
| `mattcl-solver/aoc run 5 input-kcen` | 0.7 ± 0.1 | 0.6 | 1.6 | 1.09 ± 0.17 |
| `mattcl-solver/aoc run 5 input-lanjian` | 0.7 ± 0.1 | 0.6 | 2.4 | 1.09 ± 0.17 |
| `mattcl-solver/aoc run 5 input-mattcl` | 0.7 ± 0.1 | 0.6 | 2.8 | 1.06 ± 0.17 |
| `mattcl-solver/aoc run 5 input-pting` | 0.7 ± 0.1 | 0.6 | 2.5 | 1.10 ± 0.19 |
| `python pting/day05/day05.py input-aspidites` | 21.4 ± 0.6 | 20.8 | 26.1 | 34.14 ± 4.01 |
| `python pting/day05/day05.py input-kcen` | 21.4 ± 0.4 | 20.5 | 23.9 | 34.09 ± 3.97 |
| `python pting/day05/day05.py input-lanjian` | 21.5 ± 1.8 | 20.4 | 38.0 | 34.27 ± 4.85 |
| `python pting/day05/day05.py input-mattcl` | 21.3 ± 0.5 | 20.5 | 24.7 | 33.93 ± 3.98 |
| `python pting/day05/day05.py input-pting` | 21.4 ± 0.4 | 20.6 | 22.9 | 34.02 ± 3.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
