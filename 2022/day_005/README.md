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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.7 ± 3.9 | 24.2 | 39.7 | 9.09 ± 4.33 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 28.8 ± 5.4 | 24.2 | 50.9 | 9.44 ± 4.65 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 29.1 ± 5.2 | 24.5 | 51.4 | 9.55 ± 4.67 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.2 ± 3.4 | 24.3 | 38.6 | 8.92 ± 4.21 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.6 ± 3.1 | 23.7 | 38.9 | 8.74 ± 4.10 |
| `kcen/2022/05/solve input-aspidites` | 161.1 ± 18.7 | 139.3 | 220.2 | 52.79 ± 24.79 |
| `kcen/2022/05/solve input-kcen` | 166.3 ± 17.1 | 140.6 | 197.8 | 54.52 ± 25.43 |
| `kcen/2022/05/solve input-lanjian` | 199.2 ± 31.9 | 146.1 | 257.5 | 65.30 ± 31.49 |
| `kcen/2022/05/solve input-mattcl` | 238.2 ± 115.7 | 153.8 | 526.2 | 78.07 ± 51.97 |
| `kcen/2022/05/solve input-pting` | 172.7 ± 14.9 | 147.1 | 200.6 | 56.61 ± 26.21 |
| `lanjian/day_05 input-aspidites` | 4.1 ± 1.7 | 1.3 | 17.4 | 1.34 ± 0.83 |
| `lanjian/day_05 input-kcen` | 3.5 ± 1.3 | 1.1 | 13.7 | 1.13 ± 0.68 |
| `lanjian/day_05 input-lanjian` | 3.1 ± 1.3 | 1.4 | 13.9 | 1.03 ± 0.64 |
| `lanjian/day_05 input-mattcl` | 3.4 ± 1.2 | 1.3 | 10.7 | 1.11 ± 0.65 |
| `lanjian/day_05 input-pting` | 3.4 ± 1.3 | 1.2 | 18.5 | 1.13 ± 0.68 |
| `mattcl-solver/aoc run 5 input-aspidites` | 4.0 ± 1.4 | 1.5 | 15.5 | 1.30 ± 0.76 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.4 ± 1.4 | 1.1 | 15.8 | 1.11 ± 0.68 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.1 ± 1.4 | 1.1 | 18.0 | 1.00 |
| `mattcl-solver/aoc run 5 input-mattcl` | 4.2 ± 1.7 | 1.5 | 13.7 | 1.38 ± 0.83 |
| `mattcl-solver/aoc run 5 input-pting` | 3.4 ± 1.2 | 1.4 | 13.4 | 1.11 ± 0.64 |
| `python pting/day05.py input-aspidites` | 61.4 ± 8.8 | 47.8 | 88.8 | 20.13 ± 9.60 |
| `python pting/day05.py input-kcen` | 58.3 ± 10.2 | 42.7 | 87.6 | 19.10 ± 9.31 |
| `python pting/day05.py input-lanjian` | 52.6 ± 10.1 | 41.8 | 94.2 | 17.24 ± 8.52 |
| `python pting/day05.py input-mattcl` | 61.4 ± 11.9 | 45.2 | 111.4 | 20.14 ± 9.96 |
| `python pting/day05.py input-pting` | 59.6 ± 9.8 | 42.4 | 97.0 | 19.52 ± 9.44 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
