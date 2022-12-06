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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 30.9 ± 9.9 | 23.5 | 61.5 | 9.80 ± 5.59 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 28.1 ± 6.9 | 23.4 | 50.1 | 8.91 ± 4.74 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 27.8 ± 6.2 | 23.9 | 71.2 | 8.81 ± 4.60 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 31.8 ± 9.6 | 23.8 | 60.5 | 10.06 ± 5.64 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.6 ± 4.4 | 23.0 | 51.5 | 8.42 ± 4.21 |
| `kcen/2022/05/solve input-aspidites` | 178.8 ± 30.3 | 140.8 | 258.8 | 56.65 ± 28.37 |
| `kcen/2022/05/solve input-kcen` | 195.1 ± 54.2 | 150.5 | 332.9 | 61.82 ± 33.83 |
| `kcen/2022/05/solve input-lanjian` | 188.4 ± 56.5 | 131.9 | 373.5 | 59.70 ± 33.35 |
| `kcen/2022/05/solve input-mattcl` | 163.3 ± 18.7 | 140.1 | 211.2 | 51.75 ± 25.09 |
| `kcen/2022/05/solve input-pting` | 164.9 ± 22.1 | 136.7 | 213.9 | 52.25 ± 25.61 |
| `lanjian/day_05 input-aspidites` | 3.4 ± 1.4 | 1.0 | 11.4 | 1.06 ± 0.66 |
| `lanjian/day_05 input-kcen` | 3.6 ± 2.3 | 1.1 | 38.4 | 1.14 ± 0.90 |
| `lanjian/day_05 input-lanjian` | 3.3 ± 1.3 | 1.4 | 11.3 | 1.04 ± 0.65 |
| `lanjian/day_05 input-mattcl` | 3.4 ± 2.3 | 1.0 | 17.6 | 1.09 ± 0.88 |
| `lanjian/day_05 input-pting` | 3.2 ± 1.5 | 0.9 | 9.7 | 1.00 ± 0.67 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.2 ± 1.5 | 1.1 | 11.8 | 1.00 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.3 ± 1.5 | 1.2 | 10.0 | 1.03 ± 0.67 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.5 ± 1.9 | 1.2 | 16.9 | 1.12 ± 0.81 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.8 ± 1.7 | 1.2 | 13.0 | 1.21 ± 0.79 |
| `mattcl-solver/aoc run 5 input-pting` | 4.0 ± 1.9 | 1.3 | 18.4 | 1.26 ± 0.85 |
| `python pting/day05.py input-aspidites` | 74.6 ± 34.7 | 49.5 | 170.3 | 23.65 ± 15.66 |
| `python pting/day05.py input-kcen` | 65.4 ± 26.4 | 47.0 | 183.6 | 20.71 ± 12.86 |
| `python pting/day05.py input-lanjian` | 68.3 ± 23.5 | 49.4 | 174.7 | 21.63 ± 12.62 |
| `python pting/day05.py input-mattcl` | 62.0 ± 17.8 | 44.9 | 150.8 | 19.66 ± 10.85 |
| `python pting/day05.py input-pting` | 60.2 ± 8.8 | 45.6 | 87.0 | 19.08 ± 9.41 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
