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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.0 ± 3.2 | 23.3 | 39.4 | 10.02 ± 5.43 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.8 ± 5.4 | 19.4 | 47.2 | 10.69 ± 6.01 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.9 ± 3.7 | 23.1 | 45.1 | 9.96 ± 5.44 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.8 ± 4.1 | 23.4 | 39.8 | 10.33 ± 5.67 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.2 ± 3.7 | 23.1 | 39.0 | 10.07 ± 5.50 |
| `kcen/2022/05/solve input-aspidites` | 166.5 ± 31.7 | 127.1 | 241.0 | 64.09 ± 35.93 |
| `kcen/2022/05/solve input-kcen` | 178.8 ± 37.4 | 138.9 | 285.9 | 68.82 ± 39.05 |
| `kcen/2022/05/solve input-lanjian` | 144.9 ± 34.4 | 115.3 | 275.2 | 55.80 ± 32.26 |
| `kcen/2022/05/solve input-mattcl` | 145.7 ± 17.7 | 116.8 | 178.2 | 56.08 ± 30.35 |
| `kcen/2022/05/solve input-pting` | 173.3 ± 34.1 | 130.3 | 271.4 | 66.73 ± 37.56 |
| `lanjian/day_05 input-aspidites` | 3.6 ± 1.6 | 1.2 | 15.6 | 1.39 ± 0.97 |
| `lanjian/day_05 input-kcen` | 3.4 ± 1.9 | 1.0 | 14.7 | 1.31 ± 1.00 |
| `lanjian/day_05 input-lanjian` | 3.1 ± 1.7 | 0.9 | 12.6 | 1.19 ± 0.92 |
| `lanjian/day_05 input-mattcl` | 4.1 ± 1.7 | 1.3 | 18.2 | 1.56 ± 1.05 |
| `lanjian/day_05 input-pting` | 3.3 ± 2.0 | 1.0 | 16.8 | 1.27 ± 1.03 |
| `mattcl-solver/aoc run 5 input-aspidites` | 6.7 ± 9.0 | 1.5 | 91.2 | 2.59 ± 3.73 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.6 ± 1.4 | 1.0 | 13.2 | 1.00 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.3 ± 1.8 | 0.9 | 23.6 | 1.26 ± 0.97 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.3 ± 1.2 | 1.2 | 11.7 | 1.26 ± 0.82 |
| `mattcl-solver/aoc run 5 input-pting` | 3.4 ± 1.5 | 1.2 | 13.5 | 1.29 ± 0.90 |
| `python pting/day05.py input-aspidites` | 64.2 ± 20.8 | 46.8 | 135.7 | 24.72 ± 15.30 |
| `python pting/day05.py input-kcen` | 55.8 ± 15.8 | 41.1 | 133.3 | 21.49 ± 12.86 |
| `python pting/day05.py input-lanjian` | 60.6 ± 22.5 | 39.7 | 153.0 | 23.31 ± 15.03 |
| `python pting/day05.py input-mattcl` | 58.9 ± 18.4 | 41.6 | 155.9 | 22.67 ± 13.89 |
| `python pting/day05.py input-pting` | 58.7 ± 15.7 | 41.0 | 114.0 | 22.62 ± 13.37 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
