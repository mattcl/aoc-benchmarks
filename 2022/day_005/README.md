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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 11.0 ± 0.1 | 10.9 | 11.7 | 17.89 ± 1.62 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 11.0 ± 0.1 | 10.9 | 11.5 | 17.94 ± 1.63 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 11.0 ± 0.1 | 10.9 | 11.5 | 17.91 ± 1.62 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 11.0 ± 0.1 | 10.9 | 11.5 | 17.92 ± 1.62 |
| `aspidites-solver/aoc -i input-pting -d 5` | 11.0 ± 0.1 | 10.9 | 11.4 | 17.91 ± 1.62 |
| `kcen/2022/05/solve input-aspidites` | 60.7 ± 0.9 | 59.2 | 63.0 | 98.89 ± 9.05 |
| `kcen/2022/05/solve input-kcen` | 60.9 ± 0.7 | 59.7 | 62.6 | 99.12 ± 9.01 |
| `kcen/2022/05/solve input-lanjian` | 61.3 ± 1.6 | 59.3 | 68.9 | 99.86 ± 9.39 |
| `kcen/2022/05/solve input-mattcl` | 60.7 ± 0.6 | 59.2 | 62.1 | 98.85 ± 8.98 |
| `kcen/2022/05/solve input-pting` | 61.0 ± 0.9 | 59.5 | 63.5 | 99.28 ± 9.07 |
| `lanjian/day_05 input-aspidites` | 0.6 ± 0.1 | 0.5 | 1.5 | 1.00 |
| `lanjian/day_05 input-kcen` | 0.7 ± 0.1 | 0.5 | 2.5 | 1.07 ± 0.16 |
| `lanjian/day_05 input-lanjian` | 0.6 ± 0.2 | 0.5 | 8.6 | 1.03 ± 0.35 |
| `lanjian/day_05 input-mattcl` | 0.6 ± 0.1 | 0.5 | 2.5 | 1.03 ± 0.16 |
| `lanjian/day_05 input-pting` | 0.6 ± 0.2 | 0.5 | 4.5 | 1.04 ± 0.27 |
| `mattcl-solver/aoc run 5 input-aspidites` | 0.7 ± 0.1 | 0.6 | 2.6 | 1.07 ± 0.15 |
| `mattcl-solver/aoc run 5 input-kcen` | 0.7 ± 0.1 | 0.6 | 2.9 | 1.14 ± 0.20 |
| `mattcl-solver/aoc run 5 input-lanjian` | 0.7 ± 0.1 | 0.6 | 1.1 | 1.08 ± 0.13 |
| `mattcl-solver/aoc run 5 input-mattcl` | 0.7 ± 0.1 | 0.6 | 2.6 | 1.10 ± 0.16 |
| `mattcl-solver/aoc run 5 input-pting` | 0.7 ± 0.1 | 0.6 | 1.9 | 1.08 ± 0.15 |
| `python pting/day05.py input-aspidites` | 21.1 ± 0.4 | 20.3 | 22.9 | 34.41 ± 3.18 |
| `python pting/day05.py input-kcen` | 22.1 ± 5.5 | 20.4 | 65.6 | 35.95 ± 9.54 |
| `python pting/day05.py input-lanjian` | 21.4 ± 0.9 | 20.6 | 30.9 | 34.80 ± 3.48 |
| `python pting/day05.py input-mattcl` | 21.3 ± 0.4 | 20.5 | 22.9 | 34.62 ± 3.19 |
| `python pting/day05.py input-pting` | 21.5 ± 0.4 | 20.8 | 24.1 | 35.08 ± 3.24 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
