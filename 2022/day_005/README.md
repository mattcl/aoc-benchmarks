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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 28.1 ± 5.1 | 23.8 | 57.6 | 11.51 ± 7.11 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.8 ± 2.1 | 23.5 | 35.9 | 10.55 ± 6.29 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.8 ± 2.4 | 23.6 | 36.0 | 10.59 ± 6.33 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.6 ± 6.3 | 23.9 | 68.2 | 11.30 ± 7.16 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.4 ± 1.9 | 23.3 | 38.0 | 10.41 ± 6.20 |
| `kcen/2022/05/solve input-aspidites` | 167.0 ± 17.2 | 146.4 | 198.5 | 68.41 ± 41.04 |
| `kcen/2022/05/solve input-kcen` | 169.6 ± 19.9 | 144.4 | 201.3 | 69.50 ± 41.87 |
| `kcen/2022/05/solve input-lanjian` | 151.7 ± 20.1 | 116.5 | 194.8 | 62.16 ± 37.64 |
| `kcen/2022/05/solve input-mattcl` | 165.2 ± 18.7 | 139.9 | 194.7 | 67.67 ± 40.72 |
| `kcen/2022/05/solve input-pting` | 155.5 ± 19.4 | 125.6 | 204.6 | 63.72 ± 38.48 |
| `lanjian/day_05 input-aspidites` | 2.8 ± 1.5 | 0.8 | 15.7 | 1.15 ± 0.92 |
| `lanjian/day_05 input-kcen` | 2.4 ± 1.4 | 0.6 | 15.2 | 1.00 |
| `lanjian/day_05 input-lanjian` | 2.7 ± 2.1 | 0.8 | 38.4 | 1.13 ± 1.08 |
| `lanjian/day_05 input-mattcl` | 2.7 ± 1.9 | 0.7 | 28.4 | 1.11 ± 1.03 |
| `lanjian/day_05 input-pting` | 2.9 ± 1.1 | 1.0 | 8.4 | 1.18 ± 0.84 |
| `mattcl-solver/aoc run 5 input-aspidites` | 14.1 ± 13.3 | 1.6 | 88.8 | 5.76 ± 6.43 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.9 ± 1.2 | 1.0 | 11.7 | 1.21 ± 0.87 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.1 ± 1.4 | 1.0 | 11.8 | 1.25 ± 0.94 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.8 ± 1.2 | 0.9 | 14.1 | 1.15 ± 0.83 |
| `mattcl-solver/aoc run 5 input-pting` | 3.3 ± 1.6 | 1.0 | 19.1 | 1.37 ± 1.04 |
| `python pting/day05.py input-aspidites` | 56.5 ± 7.1 | 43.7 | 76.7 | 23.16 ± 13.99 |
| `python pting/day05.py input-kcen` | 59.4 ± 10.1 | 42.5 | 91.8 | 24.33 ± 14.96 |
| `python pting/day05.py input-lanjian` | 61.3 ± 6.8 | 52.0 | 84.7 | 25.10 ± 15.09 |
| `python pting/day05.py input-mattcl` | 59.5 ± 7.9 | 47.1 | 77.4 | 24.40 ± 14.78 |
| `python pting/day05.py input-pting` | 58.2 ± 7.6 | 41.2 | 76.7 | 23.83 ± 14.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
