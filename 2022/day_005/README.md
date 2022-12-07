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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.6 ± 14.9 | 23.8 | 182.8 | 10.55 ± 7.46 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.3 ± 1.4 | 23.6 | 34.1 | 9.66 ± 4.46 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 28.1 ± 5.9 | 23.6 | 65.1 | 10.74 ± 5.41 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.4 ± 4.1 | 23.8 | 50.1 | 10.45 ± 5.04 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.3 ± 3.1 | 23.8 | 39.1 | 10.05 ± 4.76 |
| `kcen/2022/05/solve input-aspidites` | 168.4 ± 19.9 | 146.1 | 218.7 | 64.34 ± 30.45 |
| `kcen/2022/05/solve input-kcen` | 168.0 ± 21.0 | 139.9 | 212.7 | 64.18 ± 30.49 |
| `kcen/2022/05/solve input-lanjian` | 192.5 ± 27.7 | 147.2 | 239.0 | 73.54 ± 35.33 |
| `kcen/2022/05/solve input-mattcl` | 179.8 ± 14.6 | 155.5 | 211.9 | 68.68 ± 31.97 |
| `kcen/2022/05/solve input-pting` | 164.0 ± 17.2 | 142.4 | 203.1 | 62.66 ± 29.46 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 1.2 | 0.8 | 10.7 | 1.00 |
| `lanjian/day_05 input-kcen` | 3.0 ± 1.3 | 1.0 | 18.7 | 1.14 ± 0.71 |
| `lanjian/day_05 input-lanjian` | 3.5 ± 3.4 | 0.8 | 80.4 | 1.33 ± 1.45 |
| `lanjian/day_05 input-mattcl` | 5.2 ± 7.8 | 0.8 | 148.5 | 2.00 ± 3.13 |
| `lanjian/day_05 input-pting` | 2.8 ± 1.3 | 0.9 | 9.4 | 1.09 ± 0.70 |
| `mattcl-solver/aoc run 5 input-aspidites` | 4.0 ± 1.6 | 1.4 | 14.1 | 1.53 ± 0.93 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.8 ± 1.3 | 0.9 | 15.1 | 1.08 ± 0.71 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.9 ± 1.1 | 0.9 | 9.8 | 1.09 ± 0.66 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.7 ± 2.2 | 1.2 | 18.7 | 1.41 ± 1.05 |
| `mattcl-solver/aoc run 5 input-pting` | 3.3 ± 1.1 | 1.1 | 10.8 | 1.24 ± 0.70 |
| `python pting/day05.py input-aspidites` | 58.3 ± 9.4 | 45.1 | 82.9 | 22.29 ± 10.83 |
| `python pting/day05.py input-kcen` | 76.7 ± 28.4 | 46.7 | 169.1 | 29.32 ± 17.26 |
| `python pting/day05.py input-lanjian` | 63.1 ± 9.0 | 50.5 | 94.9 | 24.12 ± 11.58 |
| `python pting/day05.py input-mattcl` | 67.8 ± 11.4 | 51.9 | 96.1 | 25.88 ± 12.64 |
| `python pting/day05.py input-pting` | 57.3 ± 8.7 | 43.4 | 85.6 | 21.89 ± 10.56 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
