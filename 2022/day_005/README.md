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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.9 ± 3.3 | 23.1 | 38.3 | 13.45 ± 9.73 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.2 ± 3.6 | 23.0 | 44.7 | 13.61 ± 9.87 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.7 ± 3.3 | 22.9 | 36.8 | 13.38 ± 9.68 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.0 ± 4.8 | 23.1 | 47.8 | 14.01 ± 10.28 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.8 ± 4.0 | 23.4 | 56.4 | 13.43 ± 9.78 |
| `kcen/2022/05/solve input-aspidites` | 168.3 ± 15.8 | 145.5 | 199.8 | 87.48 ± 62.81 |
| `kcen/2022/05/solve input-kcen` | 164.9 ± 16.5 | 141.6 | 199.7 | 85.74 ± 61.63 |
| `kcen/2022/05/solve input-lanjian` | 164.3 ± 18.6 | 131.8 | 202.8 | 85.39 ± 61.54 |
| `kcen/2022/05/solve input-mattcl` | 161.7 ± 13.7 | 137.4 | 193.8 | 84.05 ± 60.25 |
| `kcen/2022/05/solve input-pting` | 160.5 ± 20.6 | 131.0 | 206.7 | 83.43 ± 60.34 |
| `lanjian/day_05 input-aspidites` | 2.2 ± 1.3 | 0.2 | 17.1 | 1.16 ± 1.08 |
| `lanjian/day_05 input-kcen` | 2.3 ± 1.4 | 0.3 | 15.4 | 1.21 ± 1.11 |
| `lanjian/day_05 input-lanjian` | 1.9 ± 1.4 | 0.1 | 12.3 | 1.00 |
| `lanjian/day_05 input-mattcl` | 3.0 ± 1.8 | 0.5 | 17.5 | 1.53 ± 1.45 |
| `lanjian/day_05 input-pting` | 5.6 ± 7.6 | 0.2 | 48.1 | 2.89 ± 4.45 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.6 ± 1.3 | 0.5 | 12.6 | 1.34 ± 1.18 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.0 ± 3.5 | 0.5 | 81.2 | 1.56 ± 2.11 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.3 ± 1.1 | 0.3 | 6.5 | 1.19 ± 1.02 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.2 ± 1.5 | 0.0 | 17.2 | 1.12 ± 1.10 |
| `mattcl-solver/aoc run 5 input-pting` | 7.4 ± 8.1 | 0.3 | 61.4 | 3.85 ± 5.04 |
| `python pting/day05.py input-aspidites` | 54.8 ± 6.8 | 44.3 | 72.4 | 28.48 ± 20.57 |
| `python pting/day05.py input-kcen` | 55.8 ± 7.5 | 44.6 | 73.1 | 29.02 ± 21.03 |
| `python pting/day05.py input-lanjian` | 57.1 ± 7.9 | 44.5 | 79.2 | 29.67 ± 21.51 |
| `python pting/day05.py input-mattcl` | 63.5 ± 12.9 | 45.9 | 92.8 | 33.00 ± 24.43 |
| `python pting/day05.py input-pting` | 61.1 ± 8.8 | 47.9 | 87.9 | 31.76 ± 23.06 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
