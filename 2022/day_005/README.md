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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.7 ± 2.9 | 12.3 | 35.5 | 13.50 ± 10.54 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.1 ± 5.0 | 23.2 | 48.4 | 14.85 ± 11.78 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 22.9 ± 3.9 | 12.0 | 37.2 | 12.51 ± 9.89 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.0 ± 5.7 | 11.9 | 51.5 | 13.66 ± 10.99 |
| `aspidites-solver/aoc -i input-pting -d 5` | 53.5 ± 47.6 | 23.5 | 190.5 | 29.29 ± 34.50 |
| `kcen/2022/05/solve input-aspidites` | 180.2 ± 28.0 | 131.2 | 249.7 | 98.62 ± 77.62 |
| `kcen/2022/05/solve input-kcen` | 186.0 ± 21.8 | 159.8 | 234.4 | 101.84 ± 79.48 |
| `kcen/2022/05/solve input-lanjian` | 168.7 ± 28.3 | 129.2 | 213.1 | 92.35 ± 72.91 |
| `kcen/2022/05/solve input-mattcl` | 143.7 ± 13.3 | 126.4 | 178.7 | 78.69 ± 61.15 |
| `kcen/2022/05/solve input-pting` | 253.0 ± 145.2 | 139.8 | 595.8 | 138.51 ± 133.19 |
| `lanjian/day_05 input-aspidites` | 2.2 ± 1.2 | 0.4 | 11.1 | 1.23 ± 1.16 |
| `lanjian/day_05 input-kcen` | 1.8 ± 1.4 | 0.2 | 20.9 | 1.00 |
| `lanjian/day_05 input-lanjian` | 2.3 ± 1.3 | 0.4 | 11.9 | 1.27 ± 1.22 |
| `lanjian/day_05 input-mattcl` | 2.5 ± 1.3 | 0.5 | 10.1 | 1.36 ± 1.25 |
| `lanjian/day_05 input-pting` | 1.9 ± 0.9 | 0.4 | 6.0 | 1.04 ± 0.94 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.9 ± 1.3 | 0.8 | 8.9 | 1.58 ± 1.40 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.1 ± 1.2 | 0.4 | 9.7 | 1.18 ± 1.13 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.8 ± 1.5 | 0.5 | 16.5 | 1.53 ± 1.44 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.2 ± 1.2 | 0.3 | 15.2 | 1.20 ± 1.15 |
| `mattcl-solver/aoc run 5 input-pting` | 2.5 ± 1.3 | 0.7 | 16.1 | 1.37 ± 1.28 |
| `python pting/day05.py input-aspidites` | 55.4 ± 13.7 | 40.3 | 137.1 | 30.32 ± 24.57 |
| `python pting/day05.py input-kcen` | 55.6 ± 18.4 | 44.3 | 138.4 | 30.43 ± 25.55 |
| `python pting/day05.py input-lanjian` | 54.6 ± 8.4 | 41.9 | 89.0 | 29.87 ± 23.50 |
| `python pting/day05.py input-mattcl` | 55.3 ± 14.6 | 39.4 | 152.0 | 30.29 ± 24.70 |
| `python pting/day05.py input-pting` | 55.3 ± 10.1 | 44.3 | 101.8 | 30.29 ± 24.01 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
