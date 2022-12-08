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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.8 ± 4.4 | 23.0 | 45.8 | 11.95 ± 9.99 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.2 ± 2.2 | 22.8 | 36.3 | 11.24 ± 9.26 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.7 ± 2.5 | 12.7 | 37.9 | 10.98 ± 9.06 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 32.8 ± 14.7 | 23.5 | 110.4 | 14.58 ± 13.63 |
| `aspidites-solver/aoc -i input-pting -d 5` | 27.4 ± 5.6 | 23.4 | 47.4 | 12.20 ± 10.30 |
| `kcen/2022/05/solve input-aspidites` | 174.7 ± 22.1 | 155.1 | 226.4 | 77.79 ± 64.47 |
| `kcen/2022/05/solve input-kcen` | 170.0 ± 12.4 | 153.5 | 188.1 | 75.71 ± 62.25 |
| `kcen/2022/05/solve input-lanjian` | 160.4 ± 11.6 | 143.8 | 192.0 | 71.44 ± 58.74 |
| `kcen/2022/05/solve input-mattcl` | 165.4 ± 22.8 | 124.6 | 230.2 | 73.66 ± 61.18 |
| `kcen/2022/05/solve input-pting` | 164.4 ± 14.0 | 141.2 | 188.4 | 73.20 ± 60.28 |
| `lanjian/day_05 input-aspidites` | 2.8 ± 1.8 | 0.7 | 19.0 | 1.24 ± 1.28 |
| `lanjian/day_05 input-kcen` | 2.6 ± 2.1 | 0.3 | 20.5 | 1.17 ± 1.34 |
| `lanjian/day_05 input-lanjian` | 2.9 ± 1.5 | 0.5 | 11.9 | 1.28 ± 1.24 |
| `lanjian/day_05 input-mattcl` | 2.2 ± 1.8 | 0.3 | 20.7 | 1.00 |
| `lanjian/day_05 input-pting` | 2.4 ± 1.5 | 0.4 | 16.1 | 1.08 ± 1.10 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.5 ± 2.3 | 1.1 | 27.3 | 1.55 ± 1.63 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.7 ± 1.1 | 0.4 | 11.8 | 1.18 ± 1.09 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.7 ± 1.3 | 0.5 | 10.5 | 1.21 ± 1.15 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.4 ± 1.6 | 0.4 | 17.8 | 1.09 ± 1.15 |
| `mattcl-solver/aoc run 5 input-pting` | 2.5 ± 2.3 | 0.5 | 35.9 | 1.09 ± 1.38 |
| `python pting/day05.py input-aspidites` | 60.1 ± 8.2 | 46.9 | 85.0 | 26.75 ± 22.21 |
| `python pting/day05.py input-kcen` | 130.1 ± 86.7 | 52.1 | 339.6 | 57.91 ± 61.14 |
| `python pting/day05.py input-lanjian` | 59.5 ± 9.3 | 47.5 | 87.9 | 26.52 ± 22.11 |
| `python pting/day05.py input-mattcl` | 57.4 ± 7.4 | 44.0 | 75.8 | 25.57 ± 21.20 |
| `python pting/day05.py input-pting` | 58.2 ± 8.9 | 45.3 | 87.1 | 25.89 ± 21.58 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
