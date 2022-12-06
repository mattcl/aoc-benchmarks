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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.2 ± 1.9 | 23.4 | 37.9 | 11.66 ± 4.57 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.1 ± 1.9 | 23.0 | 36.8 | 11.63 ± 4.56 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.3 ± 4.0 | 23.1 | 55.7 | 11.71 ± 4.87 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.0 ± 1.7 | 23.3 | 35.7 | 11.57 ± 4.52 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.7 ± 3.9 | 23.3 | 46.2 | 11.89 ± 4.92 |
| `kcen/2022/05/solve input-aspidites` | 169.4 ± 16.4 | 143.5 | 198.1 | 78.37 ± 31.08 |
| `kcen/2022/05/solve input-kcen` | 164.8 ± 10.8 | 144.5 | 183.7 | 76.24 ± 29.74 |
| `kcen/2022/05/solve input-lanjian` | 156.6 ± 10.0 | 135.9 | 172.3 | 72.45 ± 28.24 |
| `kcen/2022/05/solve input-mattcl` | 166.6 ± 13.5 | 147.8 | 188.8 | 77.07 ± 30.29 |
| `kcen/2022/05/solve input-pting` | 165.3 ± 16.4 | 136.6 | 199.6 | 76.47 ± 30.37 |
| `lanjian/day_05 input-aspidites` | 2.3 ± 1.0 | 0.9 | 7.2 | 1.09 ± 0.61 |
| `lanjian/day_05 input-kcen` | 2.4 ± 1.2 | 0.7 | 13.1 | 1.12 ± 0.68 |
| `lanjian/day_05 input-lanjian` | 2.7 ± 1.3 | 0.8 | 14.0 | 1.24 ± 0.76 |
| `lanjian/day_05 input-mattcl` | 5.6 ± 7.0 | 1.1 | 90.2 | 2.61 ± 3.38 |
| `lanjian/day_05 input-pting` | 2.4 ± 1.3 | 0.8 | 18.4 | 1.11 ± 0.73 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.9 ± 1.3 | 0.9 | 14.6 | 1.32 ± 0.80 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.5 ± 1.0 | 0.9 | 7.8 | 1.17 ± 0.65 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.2 ± 0.8 | 0.8 | 6.1 | 1.00 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.9 ± 1.8 | 1.0 | 23.1 | 1.33 ± 0.98 |
| `mattcl-solver/aoc run 5 input-pting` | 2.9 ± 1.6 | 0.8 | 15.8 | 1.35 ± 0.91 |
| `python pting/day05.py input-aspidites` | 55.3 ± 6.2 | 47.1 | 80.7 | 25.61 ± 10.25 |
| `python pting/day05.py input-kcen` | 54.1 ± 5.2 | 45.3 | 68.2 | 25.06 ± 9.93 |
| `python pting/day05.py input-lanjian` | 55.0 ± 5.8 | 45.3 | 80.4 | 25.46 ± 10.15 |
| `python pting/day05.py input-mattcl` | 65.5 ± 8.3 | 50.9 | 82.0 | 30.32 ± 12.27 |
| `python pting/day05.py input-pting` | 53.6 ± 6.0 | 45.0 | 75.1 | 24.82 ± 9.94 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
