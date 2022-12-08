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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.5 ± 4.3 | 23.4 | 49.5 | 13.18 ± 8.16 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.4 ± 2.5 | 23.4 | 36.8 | 12.64 ± 7.64 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.3 ± 3.9 | 23.2 | 53.4 | 13.10 ± 8.06 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 41.5 ± 26.2 | 23.2 | 216.6 | 20.67 ± 17.94 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.1 ± 3.6 | 22.8 | 50.1 | 12.97 ± 7.95 |
| `kcen/2022/05/solve input-aspidites` | 178.4 ± 19.5 | 148.9 | 200.2 | 88.76 ± 53.87 |
| `kcen/2022/05/solve input-kcen` | 156.2 ± 19.3 | 135.4 | 198.0 | 77.74 ± 47.40 |
| `kcen/2022/05/solve input-lanjian` | 170.8 ± 25.6 | 136.6 | 220.7 | 84.98 ± 52.31 |
| `kcen/2022/05/solve input-mattcl` | 164.1 ± 23.6 | 136.3 | 206.3 | 81.67 ± 50.15 |
| `kcen/2022/05/solve input-pting` | 172.4 ± 28.8 | 134.8 | 228.4 | 85.77 ± 53.17 |
| `lanjian/day_05 input-aspidites` | 3.4 ± 1.6 | 0.9 | 11.6 | 1.70 ± 1.30 |
| `lanjian/day_05 input-kcen` | 2.3 ± 1.4 | 0.3 | 21.9 | 1.14 ± 0.96 |
| `lanjian/day_05 input-lanjian` | 2.0 ± 1.2 | 0.4 | 15.8 | 1.00 |
| `lanjian/day_05 input-mattcl` | 3.0 ± 1.5 | 0.6 | 13.9 | 1.50 ± 1.17 |
| `lanjian/day_05 input-pting` | 2.9 ± 2.0 | 0.5 | 15.2 | 1.45 ± 1.33 |
| `mattcl-solver/aoc run 5 input-aspidites` | 4.5 ± 2.0 | 1.8 | 18.1 | 2.23 ± 1.67 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.7 ± 1.3 | 0.6 | 18.0 | 1.32 ± 1.03 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.1 ± 1.4 | 0.9 | 16.1 | 1.56 ± 1.16 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.6 ± 1.4 | 1.2 | 12.0 | 1.79 ± 1.27 |
| `mattcl-solver/aoc run 5 input-pting` | 3.2 ± 1.2 | 1.0 | 8.0 | 1.60 ± 1.13 |
| `python pting/day05.py input-aspidites` | 66.6 ± 12.9 | 50.3 | 116.7 | 33.14 ± 20.80 |
| `python pting/day05.py input-kcen` | 61.6 ± 11.3 | 46.1 | 85.3 | 30.64 ± 19.13 |
| `python pting/day05.py input-lanjian` | 55.8 ± 8.4 | 44.6 | 79.6 | 27.74 ± 17.08 |
| `python pting/day05.py input-mattcl` | 56.2 ± 7.3 | 43.4 | 77.0 | 27.95 ± 17.08 |
| `python pting/day05.py input-pting` | 64.3 ± 10.2 | 49.7 | 93.7 | 32.00 ± 19.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
