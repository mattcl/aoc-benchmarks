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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.1 ± 4.7 | 23.2 | 55.3 | 10.82 ± 4.80 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.2 ± 2.0 | 23.3 | 36.6 | 10.45 ± 4.31 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.6 ± 3.6 | 17.9 | 45.2 | 10.64 ± 4.56 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.3 ± 1.8 | 23.3 | 37.0 | 10.49 ± 4.31 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.6 ± 3.2 | 23.4 | 45.0 | 10.62 ± 4.50 |
| `kcen/2022/05/solve input-aspidites` | 272.5 ± 74.1 | 150.5 | 375.3 | 113.20 ± 55.19 |
| `kcen/2022/05/solve input-kcen` | 153.0 ± 13.3 | 134.5 | 180.0 | 63.56 ± 26.31 |
| `kcen/2022/05/solve input-lanjian` | 151.4 ± 10.3 | 138.9 | 176.3 | 62.88 ± 25.81 |
| `kcen/2022/05/solve input-mattcl` | 152.1 ± 18.2 | 127.0 | 191.4 | 63.20 ± 26.67 |
| `kcen/2022/05/solve input-pting` | 158.1 ± 15.5 | 141.0 | 197.1 | 65.66 ± 27.34 |
| `lanjian/day_05 input-aspidites` | 2.9 ± 1.4 | 1.2 | 19.5 | 1.22 ± 0.75 |
| `lanjian/day_05 input-kcen` | 2.4 ± 1.0 | 0.8 | 12.8 | 1.00 |
| `lanjian/day_05 input-lanjian` | 3.2 ± 1.3 | 1.3 | 16.1 | 1.34 ± 0.77 |
| `lanjian/day_05 input-mattcl` | 2.6 ± 1.2 | 0.9 | 13.8 | 1.08 ± 0.66 |
| `lanjian/day_05 input-pting` | 3.3 ± 1.6 | 0.8 | 13.9 | 1.36 ± 0.85 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.9 ± 0.8 | 1.1 | 10.2 | 1.19 ± 0.59 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.6 ± 1.1 | 0.9 | 11.0 | 1.08 ± 0.62 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.8 ± 1.1 | 1.2 | 19.7 | 1.17 ± 0.67 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.3 ± 0.9 | 1.5 | 7.8 | 1.36 ± 0.66 |
| `mattcl-solver/aoc run 5 input-pting` | 2.5 ± 1.1 | 1.1 | 9.2 | 1.05 ± 0.61 |
| `python pting/day05.py input-aspidites` | 59.1 ± 9.4 | 46.9 | 98.5 | 24.56 ± 10.68 |
| `python pting/day05.py input-kcen` | 55.5 ± 7.1 | 44.1 | 74.8 | 23.07 ± 9.79 |
| `python pting/day05.py input-lanjian` | 54.6 ± 7.4 | 44.7 | 72.7 | 22.67 ± 9.68 |
| `python pting/day05.py input-mattcl` | 55.3 ± 6.5 | 40.5 | 70.7 | 22.95 ± 9.68 |
| `python pting/day05.py input-pting` | 58.0 ± 7.3 | 45.5 | 73.3 | 24.10 ± 10.21 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
