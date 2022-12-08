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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.6 ± 3.2 | 23.9 | 40.1 | 8.68 ± 3.28 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.0 ± 3.9 | 23.9 | 47.2 | 8.81 ± 3.41 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.7 ± 2.2 | 23.7 | 41.9 | 8.41 ± 3.10 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.0 ± 2.6 | 13.3 | 39.4 | 8.16 ± 3.04 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.5 ± 1.7 | 23.6 | 36.0 | 8.35 ± 3.04 |
| `kcen/2022/05/solve input-aspidites` | 169.7 ± 21.5 | 139.0 | 215.8 | 55.47 ± 21.08 |
| `kcen/2022/05/solve input-kcen` | 165.0 ± 16.5 | 138.2 | 202.7 | 53.94 ± 20.07 |
| `kcen/2022/05/solve input-lanjian` | 164.3 ± 21.0 | 136.1 | 204.1 | 53.68 ± 20.43 |
| `kcen/2022/05/solve input-mattcl` | 165.8 ± 18.2 | 143.7 | 201.8 | 54.19 ± 20.32 |
| `kcen/2022/05/solve input-pting` | 170.9 ± 17.6 | 143.0 | 208.9 | 55.87 ± 20.84 |
| `lanjian/day_05 input-aspidites` | 3.2 ± 1.2 | 1.2 | 10.3 | 1.03 ± 0.54 |
| `lanjian/day_05 input-kcen` | 3.1 ± 3.0 | 0.9 | 65.2 | 1.03 ± 1.03 |
| `lanjian/day_05 input-lanjian` | 3.1 ± 1.1 | 1.1 | 11.0 | 1.00 |
| `lanjian/day_05 input-mattcl` | 3.2 ± 1.3 | 1.2 | 15.4 | 1.04 ± 0.55 |
| `lanjian/day_05 input-pting` | 5.7 ± 9.1 | 1.3 | 76.8 | 1.86 ± 3.04 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.6 ± 1.2 | 1.5 | 15.7 | 1.17 ± 0.58 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.1 ± 1.2 | 1.1 | 12.7 | 1.01 ± 0.53 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.2 ± 1.3 | 1.1 | 14.1 | 1.04 ± 0.56 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.5 ± 1.4 | 1.3 | 15.8 | 1.15 ± 0.62 |
| `mattcl-solver/aoc run 5 input-pting` | 3.5 ± 1.1 | 1.5 | 11.2 | 1.14 ± 0.55 |
| `python pting/day05.py input-aspidites` | 56.0 ± 8.2 | 41.9 | 74.6 | 18.32 ± 7.09 |
| `python pting/day05.py input-kcen` | 62.9 ± 9.7 | 44.1 | 85.1 | 20.55 ± 8.02 |
| `python pting/day05.py input-lanjian` | 61.2 ± 8.9 | 50.6 | 81.5 | 20.00 ± 7.74 |
| `python pting/day05.py input-mattcl` | 60.5 ± 8.1 | 46.5 | 77.7 | 19.77 ± 7.56 |
| `python pting/day05.py input-pting` | 74.8 ± 22.3 | 48.0 | 152.5 | 24.43 ± 11.39 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
