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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 29.4 ± 6.0 | 24.2 | 57.1 | 9.45 ± 3.97 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 43.2 ± 30.4 | 24.4 | 177.3 | 13.90 ± 11.03 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 29.0 ± 5.0 | 25.1 | 51.4 | 9.32 ± 3.79 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 29.0 ± 5.8 | 24.1 | 58.2 | 9.31 ± 3.90 |
| `aspidites-solver/aoc -i input-pting -d 5` | 33.5 ± 9.0 | 24.6 | 70.7 | 10.78 ± 4.90 |
| `kcen/2022/05/solve input-aspidites` | 158.3 ± 15.2 | 144.5 | 211.9 | 50.89 ± 19.34 |
| `kcen/2022/05/solve input-kcen` | 163.2 ± 13.0 | 145.4 | 187.2 | 52.49 ± 19.74 |
| `kcen/2022/05/solve input-lanjian` | 186.7 ± 25.2 | 159.4 | 231.0 | 60.02 ± 23.50 |
| `kcen/2022/05/solve input-mattcl` | 317.8 ± 156.3 | 152.9 | 563.1 | 102.19 ± 62.76 |
| `kcen/2022/05/solve input-pting` | 182.7 ± 30.0 | 147.7 | 240.8 | 58.74 ± 23.65 |
| `lanjian/day_05 input-aspidites` | 3.2 ± 1.2 | 1.1 | 11.5 | 1.04 ± 0.54 |
| `lanjian/day_05 input-kcen` | 3.1 ± 1.1 | 1.1 | 9.2 | 1.00 |
| `lanjian/day_05 input-lanjian` | 3.3 ± 1.2 | 1.1 | 8.3 | 1.05 ± 0.55 |
| `lanjian/day_05 input-mattcl` | 3.2 ± 1.3 | 1.1 | 11.4 | 1.03 ± 0.57 |
| `lanjian/day_05 input-pting` | 3.6 ± 1.8 | 1.3 | 19.8 | 1.16 ± 0.72 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.4 ± 1.2 | 1.2 | 10.6 | 1.09 ± 0.55 |
| `mattcl-solver/aoc run 5 input-kcen` | 4.0 ± 1.4 | 1.7 | 16.4 | 1.29 ± 0.65 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.2 ± 1.3 | 1.1 | 16.1 | 1.04 ± 0.55 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.8 ± 1.4 | 1.4 | 15.0 | 1.22 ± 0.62 |
| `mattcl-solver/aoc run 5 input-pting` | 3.8 ± 1.7 | 1.4 | 13.9 | 1.23 ± 0.70 |
| `python pting/day05.py input-aspidites` | 66.1 ± 32.3 | 48.5 | 279.6 | 21.26 ± 12.99 |
| `python pting/day05.py input-kcen` | 61.7 ± 9.3 | 45.8 | 89.2 | 19.84 ± 7.88 |
| `python pting/day05.py input-lanjian` | 58.9 ± 8.8 | 45.7 | 78.9 | 18.93 ± 7.51 |
| `python pting/day05.py input-mattcl` | 59.4 ± 9.4 | 47.4 | 78.8 | 19.11 ± 7.65 |
| `python pting/day05.py input-pting` | 61.7 ± 8.7 | 48.1 | 88.6 | 19.83 ± 7.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
