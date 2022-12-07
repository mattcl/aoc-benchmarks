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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 28.6 ± 6.6 | 23.5 | 69.3 | 10.84 ± 6.71 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.9 ± 4.3 | 23.9 | 44.5 | 10.56 ± 6.28 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 27.6 ± 6.3 | 22.8 | 67.4 | 10.46 ± 6.47 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.9 ± 5.4 | 23.3 | 48.3 | 10.58 ± 6.42 |
| `aspidites-solver/aoc -i input-pting -d 5` | 29.0 ± 5.5 | 23.9 | 45.8 | 11.00 ± 6.65 |
| `kcen/2022/05/solve input-aspidites` | 206.3 ± 31.3 | 156.3 | 262.4 | 78.19 ± 46.47 |
| `kcen/2022/05/solve input-kcen` | 176.1 ± 25.1 | 148.0 | 214.5 | 66.72 ± 39.50 |
| `kcen/2022/05/solve input-lanjian` | 331.2 ± 93.4 | 178.4 | 446.9 | 125.52 ± 80.34 |
| `kcen/2022/05/solve input-mattcl` | 184.0 ± 27.3 | 143.4 | 227.7 | 69.72 ± 41.38 |
| `kcen/2022/05/solve input-pting` | 211.2 ± 30.6 | 169.1 | 274.9 | 80.05 ± 47.44 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 1.5 | 0.7 | 16.8 | 1.00 |
| `lanjian/day_05 input-kcen` | 4.4 ± 4.4 | 0.5 | 50.0 | 1.66 ± 1.93 |
| `lanjian/day_05 input-lanjian` | 3.0 ± 2.0 | 0.9 | 39.1 | 1.12 ± 1.00 |
| `lanjian/day_05 input-mattcl` | 3.4 ± 2.0 | 0.9 | 20.9 | 1.30 ± 1.05 |
| `lanjian/day_05 input-pting` | 4.0 ± 2.2 | 0.6 | 17.5 | 1.50 ± 1.21 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.1 ± 1.3 | 1.1 | 12.7 | 1.16 ± 0.84 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.1 ± 1.5 | 0.8 | 13.9 | 1.18 ± 0.87 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.3 ± 1.5 | 1.0 | 14.5 | 1.25 ± 0.90 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.5 ± 1.7 | 0.9 | 13.9 | 1.33 ± 1.00 |
| `mattcl-solver/aoc run 5 input-pting` | 3.7 ± 1.8 | 0.6 | 15.3 | 1.39 ± 1.06 |
| `python pting/day05.py input-aspidites` | 68.7 ± 12.9 | 51.5 | 103.5 | 26.05 ± 15.75 |
| `python pting/day05.py input-kcen` | 115.9 ± 45.1 | 65.4 | 232.4 | 43.93 ± 30.48 |
| `python pting/day05.py input-lanjian` | 66.2 ± 12.0 | 42.8 | 88.2 | 25.08 ± 15.11 |
| `python pting/day05.py input-mattcl` | 68.7 ± 11.3 | 49.8 | 99.5 | 26.04 ± 15.57 |
| `python pting/day05.py input-pting` | 70.1 ± 8.9 | 52.3 | 92.0 | 26.58 ± 15.65 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
