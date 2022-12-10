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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.4 ± 2.6 | 23.1 | 37.1 | 12.54 ± 7.12 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 31.2 ± 12.8 | 23.4 | 103.4 | 15.40 ± 10.67 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.7 ± 1.9 | 23.1 | 34.7 | 12.21 ± 6.87 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 39.3 ± 22.3 | 23.9 | 119.5 | 19.42 ± 15.47 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.4 ± 4.0 | 23.3 | 44.8 | 13.04 ± 7.54 |
| `kcen/2022/05/solve input-aspidites` | 169.1 ± 17.7 | 141.7 | 200.4 | 83.53 ± 47.44 |
| `kcen/2022/05/solve input-kcen` | 163.0 ± 12.5 | 143.5 | 181.8 | 80.52 ± 45.37 |
| `kcen/2022/05/solve input-lanjian` | 157.0 ± 16.8 | 125.9 | 187.3 | 77.58 ± 44.09 |
| `kcen/2022/05/solve input-mattcl` | 202.3 ± 47.0 | 146.7 | 303.2 | 99.92 ± 60.41 |
| `kcen/2022/05/solve input-pting` | 203.0 ± 25.5 | 138.9 | 234.4 | 100.27 ± 57.37 |
| `lanjian/day_05 input-aspidites` | 2.4 ± 1.6 | 0.7 | 22.9 | 1.20 ± 1.03 |
| `lanjian/day_05 input-kcen` | 2.4 ± 1.3 | 0.9 | 11.4 | 1.19 ± 0.93 |
| `lanjian/day_05 input-lanjian` | 2.0 ± 1.1 | 0.5 | 17.2 | 1.00 |
| `lanjian/day_05 input-mattcl` | 2.1 ± 0.8 | 0.7 | 5.4 | 1.06 ± 0.70 |
| `lanjian/day_05 input-pting` | 2.1 ± 1.1 | 0.4 | 15.1 | 1.06 ± 0.82 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.0 ± 1.2 | 1.1 | 8.6 | 1.47 ± 1.00 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.6 ± 1.3 | 0.7 | 17.7 | 1.29 ± 0.96 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.4 ± 1.3 | 0.7 | 16.4 | 1.18 ± 0.92 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.5 ± 1.0 | 0.7 | 11.5 | 1.22 ± 0.83 |
| `mattcl-solver/aoc run 5 input-pting` | 2.4 ± 1.2 | 0.4 | 11.8 | 1.20 ± 0.89 |
| `python pting/day05.py input-aspidites` | 57.6 ± 7.6 | 45.8 | 75.8 | 28.45 ± 16.32 |
| `python pting/day05.py input-kcen` | 62.2 ± 8.8 | 46.4 | 88.1 | 30.73 ± 17.69 |
| `python pting/day05.py input-lanjian` | 60.6 ± 8.1 | 49.1 | 81.6 | 29.95 ± 17.19 |
| `python pting/day05.py input-mattcl` | 60.6 ± 7.3 | 48.2 | 77.9 | 29.93 ± 17.10 |
| `python pting/day05.py input-pting` | 58.1 ± 8.4 | 44.0 | 88.4 | 28.70 ± 16.55 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
