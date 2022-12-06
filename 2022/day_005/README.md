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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.7 ± 5.0 | 23.7 | 49.9 | 10.68 ± 4.85 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.7 ± 4.8 | 23.9 | 45.2 | 10.66 ± 4.80 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.6 ± 3.6 | 23.7 | 38.1 | 10.23 ± 4.47 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.3 ± 2.6 | 23.5 | 45.0 | 9.76 ± 4.18 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.1 ± 3.4 | 23.4 | 37.0 | 10.06 ± 4.38 |
| `kcen/2022/05/solve input-aspidites` | 200.6 ± 16.1 | 173.6 | 227.7 | 77.28 ± 32.74 |
| `kcen/2022/05/solve input-kcen` | 173.0 ± 19.0 | 143.4 | 220.8 | 66.64 ± 28.66 |
| `kcen/2022/05/solve input-lanjian` | 180.4 ± 21.8 | 148.9 | 216.5 | 69.51 ± 30.10 |
| `kcen/2022/05/solve input-mattcl` | 174.1 ± 14.6 | 149.7 | 198.4 | 67.07 ± 28.45 |
| `kcen/2022/05/solve input-pting` | 186.5 ± 20.0 | 158.9 | 211.1 | 71.84 ± 30.85 |
| `lanjian/day_05 input-aspidites` | 2.9 ± 1.3 | 1.0 | 10.0 | 1.11 ± 0.68 |
| `lanjian/day_05 input-kcen` | 3.2 ± 1.4 | 0.9 | 14.1 | 1.23 ± 0.73 |
| `lanjian/day_05 input-lanjian` | 3.0 ± 1.3 | 1.0 | 13.9 | 1.17 ± 0.68 |
| `lanjian/day_05 input-mattcl` | 2.9 ± 1.2 | 0.9 | 13.8 | 1.11 ± 0.66 |
| `lanjian/day_05 input-pting` | 2.7 ± 1.5 | 1.1 | 25.2 | 1.03 ± 0.71 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.7 ± 1.3 | 0.9 | 14.1 | 1.05 ± 0.65 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.0 ± 1.0 | 0.8 | 11.1 | 1.14 ± 0.61 |
| `mattcl-solver/aoc run 5 input-lanjian` | 4.3 ± 3.0 | 0.8 | 27.0 | 1.67 ± 1.36 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.6 ± 1.1 | 0.9 | 9.0 | 1.00 |
| `mattcl-solver/aoc run 5 input-pting` | 3.0 ± 1.2 | 0.9 | 9.9 | 1.16 ± 0.68 |
| `python pting/day05.py input-aspidites` | 63.6 ± 9.7 | 49.0 | 84.3 | 24.49 ± 10.84 |
| `python pting/day05.py input-kcen` | 59.5 ± 7.5 | 49.8 | 82.8 | 22.92 ± 9.96 |
| `python pting/day05.py input-lanjian` | 59.6 ± 6.9 | 46.9 | 74.7 | 22.98 ± 9.91 |
| `python pting/day05.py input-mattcl` | 59.5 ± 6.1 | 50.6 | 77.6 | 22.92 ± 9.82 |
| `python pting/day05.py input-pting` | 68.0 ± 11.3 | 55.0 | 118.0 | 26.18 ± 11.73 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
