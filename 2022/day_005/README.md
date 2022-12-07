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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.4 ± 4.2 | 22.9 | 48.1 | 19.13 ± 24.57 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 39.3 ± 24.3 | 22.9 | 143.6 | 28.47 ± 40.31 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.1 ± 3.9 | 22.8 | 47.0 | 18.90 ± 24.24 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 33.6 ± 9.2 | 23.7 | 63.8 | 24.34 ± 31.71 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.3 ± 4.2 | 23.0 | 45.1 | 19.04 ± 24.45 |
| `kcen/2022/05/solve input-aspidites` | 184.2 ± 20.4 | 156.5 | 228.2 | 133.29 ± 170.46 |
| `kcen/2022/05/solve input-kcen` | 171.6 ± 22.5 | 140.4 | 226.0 | 124.18 ± 159.05 |
| `kcen/2022/05/solve input-lanjian` | 173.2 ± 20.4 | 137.9 | 207.4 | 125.38 ± 160.43 |
| `kcen/2022/05/solve input-mattcl` | 180.7 ± 23.0 | 144.1 | 229.8 | 130.80 ± 167.48 |
| `kcen/2022/05/solve input-pting` | 170.3 ± 21.7 | 138.4 | 210.7 | 123.28 ± 157.85 |
| `lanjian/day_05 input-aspidites` | 3.0 ± 2.2 | 0.0 | 19.1 | 2.18 ± 3.18 |
| `lanjian/day_05 input-kcen` | 1.7 ± 1.3 | 0.0 | 10.6 | 1.22 ± 1.81 |
| `lanjian/day_05 input-lanjian` | 1.8 ± 1.4 | 0.0 | 10.6 | 1.30 ± 1.94 |
| `lanjian/day_05 input-mattcl` | 1.4 ± 1.8 | 0.0 | 24.4 | 1.00 |
| `lanjian/day_05 input-pting` | 1.5 ± 1.3 | 0.0 | 14.4 | 1.10 ± 1.68 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.6 ± 1.9 | 0.0 | 14.6 | 1.86 ± 2.73 |
| `mattcl-solver/aoc run 5 input-kcen` | 1.8 ± 1.3 | 0.0 | 9.3 | 1.29 ± 1.90 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.9 ± 2.7 | 0.2 | 35.7 | 2.13 ± 3.37 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.5 ± 1.8 | 0.0 | 21.2 | 1.82 ± 2.66 |
| `mattcl-solver/aoc run 5 input-pting` | 1.9 ± 1.4 | 0.0 | 13.5 | 1.39 ± 2.04 |
| `python pting/day05.py input-aspidites` | 68.7 ± 10.0 | 52.7 | 91.8 | 49.70 ± 63.74 |
| `python pting/day05.py input-kcen` | 63.5 ± 7.1 | 52.6 | 85.8 | 45.96 ± 58.78 |
| `python pting/day05.py input-lanjian` | 58.3 ± 7.7 | 46.9 | 79.7 | 42.17 ± 54.01 |
| `python pting/day05.py input-mattcl` | 60.4 ± 9.1 | 46.1 | 86.6 | 43.72 ± 56.09 |
| `python pting/day05.py input-pting` | 58.6 ± 8.1 | 45.0 | 84.1 | 42.41 ± 54.35 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
