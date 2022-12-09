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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 36.0 ± 17.2 | 23.9 | 112.1 | 13.18 ± 8.32 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.6 ± 1.6 | 23.7 | 38.1 | 9.35 ± 3.89 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.0 ± 2.6 | 24.1 | 44.0 | 9.53 ± 4.04 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.3 ± 1.6 | 23.2 | 35.5 | 9.27 ± 3.86 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.3 ± 3.4 | 23.7 | 45.2 | 9.64 ± 4.16 |
| `kcen/2022/05/solve input-aspidites` | 147.4 ± 14.4 | 131.5 | 179.3 | 53.94 ± 22.83 |
| `kcen/2022/05/solve input-kcen` | 159.5 ± 19.9 | 136.1 | 198.2 | 58.37 ± 25.11 |
| `kcen/2022/05/solve input-lanjian` | 156.7 ± 15.2 | 137.4 | 189.4 | 57.35 ± 24.26 |
| `kcen/2022/05/solve input-mattcl` | 152.1 ± 12.4 | 128.4 | 175.4 | 55.69 ± 23.38 |
| `kcen/2022/05/solve input-pting` | 171.7 ± 18.3 | 141.7 | 209.5 | 62.86 ± 26.74 |
| `lanjian/day_05 input-aspidites` | 3.0 ± 0.9 | 1.1 | 9.6 | 1.10 ± 0.56 |
| `lanjian/day_05 input-kcen` | 2.7 ± 0.9 | 1.2 | 8.4 | 1.00 ± 0.53 |
| `lanjian/day_05 input-lanjian` | 3.1 ± 1.0 | 1.2 | 14.6 | 1.14 ± 0.60 |
| `lanjian/day_05 input-mattcl` | 3.0 ± 1.0 | 1.1 | 10.9 | 1.10 ± 0.58 |
| `lanjian/day_05 input-pting` | 2.7 ± 1.1 | 0.9 | 13.6 | 1.00 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.0 ± 1.1 | 1.4 | 9.9 | 1.10 ± 0.59 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.0 ± 0.9 | 1.4 | 11.2 | 1.10 ± 0.57 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.1 ± 1.0 | 1.2 | 10.9 | 1.15 ± 0.60 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.9 ± 0.8 | 1.2 | 8.9 | 1.05 ± 0.53 |
| `mattcl-solver/aoc run 5 input-pting` | 3.2 ± 1.0 | 1.4 | 10.8 | 1.16 ± 0.60 |
| `python pting/day05.py input-aspidites` | 52.5 ± 8.1 | 39.6 | 74.5 | 19.21 ± 8.45 |
| `python pting/day05.py input-kcen` | 60.3 ± 7.2 | 46.9 | 76.6 | 22.06 ± 9.46 |
| `python pting/day05.py input-lanjian` | 54.3 ± 6.7 | 44.0 | 66.8 | 19.87 ± 8.54 |
| `python pting/day05.py input-mattcl` | 56.5 ± 6.5 | 46.1 | 73.7 | 20.67 ± 8.84 |
| `python pting/day05.py input-pting` | 55.7 ± 6.0 | 45.9 | 73.3 | 20.38 ± 8.68 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
