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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.7 ± 2.4 | 22.9 | 40.0 | 11.81 ± 5.05 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.2 ± 2.4 | 23.0 | 36.0 | 12.08 ± 5.16 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.5 ± 3.4 | 12.2 | 46.9 | 11.71 ± 5.15 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 24.6 ± 2.4 | 22.7 | 39.1 | 11.77 ± 5.04 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.7 ± 3.7 | 22.8 | 47.5 | 12.31 ± 5.43 |
| `kcen/2022/05/solve input-aspidites` | 148.5 ± 12.2 | 130.6 | 170.9 | 71.05 ± 30.16 |
| `kcen/2022/05/solve input-kcen` | 153.3 ± 15.4 | 136.2 | 191.5 | 73.35 ± 31.42 |
| `kcen/2022/05/solve input-lanjian` | 147.0 ± 15.3 | 125.2 | 188.8 | 70.32 ± 30.19 |
| `kcen/2022/05/solve input-mattcl` | 161.0 ± 14.6 | 140.4 | 192.0 | 77.03 ± 32.83 |
| `kcen/2022/05/solve input-pting` | 155.6 ± 15.5 | 135.9 | 187.9 | 74.43 ± 31.87 |
| `lanjian/day_05 input-aspidites` | 2.2 ± 0.9 | 0.6 | 8.6 | 1.03 ± 0.61 |
| `lanjian/day_05 input-kcen` | 2.1 ± 0.9 | 0.4 | 8.2 | 1.00 |
| `lanjian/day_05 input-lanjian` | 2.2 ± 1.2 | 0.5 | 22.7 | 1.05 ± 0.71 |
| `lanjian/day_05 input-mattcl` | 2.2 ± 0.9 | 0.6 | 8.4 | 1.04 ± 0.62 |
| `lanjian/day_05 input-pting` | 4.0 ± 4.3 | 0.7 | 40.9 | 1.91 ± 2.23 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.1 ± 0.8 | 0.7 | 7.0 | 1.03 ± 0.59 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.5 ± 1.0 | 1.0 | 11.2 | 1.19 ± 0.68 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.8 ± 1.5 | 1.1 | 24.1 | 1.35 ± 0.90 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.3 ± 0.9 | 0.6 | 11.2 | 1.11 ± 0.64 |
| `mattcl-solver/aoc run 5 input-pting` | 2.4 ± 0.9 | 0.9 | 12.6 | 1.15 ± 0.65 |
| `python pting/day05.py input-aspidites` | 55.6 ± 7.2 | 46.2 | 77.7 | 26.60 ± 11.60 |
| `python pting/day05.py input-kcen` | 56.3 ± 10.2 | 42.2 | 100.1 | 26.92 ± 12.23 |
| `python pting/day05.py input-lanjian` | 55.2 ± 7.4 | 40.5 | 75.3 | 26.41 ± 11.56 |
| `python pting/day05.py input-mattcl` | 54.2 ± 5.8 | 42.8 | 71.5 | 25.93 ± 11.14 |
| `python pting/day05.py input-pting` | 54.1 ± 6.8 | 44.5 | 82.8 | 25.90 ± 11.26 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
