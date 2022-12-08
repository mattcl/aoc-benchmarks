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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.9 ± 4.7 | 23.0 | 45.3 | 15.50 ± 11.07 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.4 ± 1.9 | 23.4 | 36.7 | 14.63 ± 10.19 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.6 ± 2.5 | 23.3 | 42.3 | 14.76 ± 10.32 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.8 ± 5.5 | 23.5 | 59.8 | 16.01 ± 11.53 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.5 ± 2.7 | 23.3 | 37.5 | 14.72 ± 10.32 |
| `kcen/2022/05/solve input-aspidites` | 177.0 ± 24.4 | 146.5 | 233.6 | 102.04 ± 72.06 |
| `kcen/2022/05/solve input-kcen` | 158.1 ± 14.8 | 131.4 | 189.6 | 91.14 ± 63.70 |
| `kcen/2022/05/solve input-lanjian` | 154.5 ± 14.3 | 128.8 | 191.0 | 89.05 ± 62.22 |
| `kcen/2022/05/solve input-mattcl` | 161.8 ± 23.9 | 129.8 | 213.1 | 93.27 ± 66.06 |
| `kcen/2022/05/solve input-pting` | 161.6 ± 17.8 | 129.5 | 190.7 | 93.12 ± 65.31 |
| `lanjian/day_05 input-aspidites` | 10.7 ± 9.9 | 1.7 | 56.4 | 6.17 ± 7.14 |
| `lanjian/day_05 input-kcen` | 2.0 ± 1.1 | 0.3 | 7.0 | 1.16 ± 1.03 |
| `lanjian/day_05 input-lanjian` | 1.7 ± 1.2 | 0.3 | 11.1 | 1.00 |
| `lanjian/day_05 input-mattcl` | 1.8 ± 1.1 | 0.3 | 11.3 | 1.02 ± 0.93 |
| `lanjian/day_05 input-pting` | 2.0 ± 1.1 | 0.5 | 9.1 | 1.17 ± 1.03 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.8 ± 3.7 | 0.7 | 30.6 | 2.22 ± 2.61 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.6 ± 1.4 | 0.6 | 14.6 | 1.50 ± 1.31 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.1 ± 1.3 | 0.5 | 13.7 | 1.21 ± 1.13 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.3 ± 1.2 | 0.4 | 9.6 | 1.35 ± 1.17 |
| `mattcl-solver/aoc run 5 input-pting` | 2.7 ± 1.2 | 0.4 | 8.6 | 1.58 ± 1.30 |
| `python pting/day05.py input-aspidites` | 64.9 ± 9.3 | 50.8 | 87.9 | 37.40 ± 26.45 |
| `python pting/day05.py input-kcen` | 55.4 ± 7.1 | 44.5 | 73.7 | 31.91 ± 22.48 |
| `python pting/day05.py input-lanjian` | 54.5 ± 7.7 | 42.9 | 76.2 | 31.42 ± 22.21 |
| `python pting/day05.py input-mattcl` | 54.3 ± 6.6 | 42.0 | 73.2 | 31.30 ± 22.01 |
| `python pting/day05.py input-pting` | 59.7 ± 6.5 | 48.7 | 83.8 | 34.39 ± 24.11 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
