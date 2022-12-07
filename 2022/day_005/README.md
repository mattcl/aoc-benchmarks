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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.0 ± 7.2 | 13.4 | 57.8 | 9.57 ± 6.56 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 29.6 ± 9.8 | 23.1 | 62.2 | 10.49 ± 7.49 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.1 ± 1.4 | 22.5 | 34.1 | 8.53 ± 5.41 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.6 ± 5.7 | 22.1 | 48.0 | 9.43 ± 6.30 |
| `aspidites-solver/aoc -i input-pting -d 5` | 30.7 ± 9.8 | 23.2 | 62.2 | 10.88 ± 7.70 |
| `kcen/2022/05/solve input-aspidites` | 167.7 ± 42.5 | 121.9 | 260.5 | 59.40 ± 40.46 |
| `kcen/2022/05/solve input-kcen` | 174.6 ± 27.5 | 135.7 | 217.4 | 61.84 ± 40.29 |
| `kcen/2022/05/solve input-lanjian` | 168.9 ± 29.5 | 140.6 | 229.8 | 59.82 ± 39.24 |
| `kcen/2022/05/solve input-mattcl` | 154.2 ± 27.6 | 120.8 | 258.5 | 54.62 ± 35.89 |
| `kcen/2022/05/solve input-pting` | 175.9 ± 30.1 | 143.8 | 241.2 | 62.29 ± 40.80 |
| `lanjian/day_05 input-aspidites` | 3.0 ± 2.2 | 0.0 | 16.9 | 1.07 ± 1.04 |
| `lanjian/day_05 input-kcen` | 3.3 ± 3.0 | 0.0 | 23.6 | 1.17 ± 1.30 |
| `lanjian/day_05 input-lanjian` | 3.0 ± 2.0 | 0.4 | 12.1 | 1.06 ± 0.98 |
| `lanjian/day_05 input-mattcl` | 2.8 ± 1.8 | 0.1 | 8.9 | 1.00 |
| `lanjian/day_05 input-pting` | 3.5 ± 2.0 | 0.2 | 13.3 | 1.23 ± 1.06 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.8 ± 1.9 | 0.3 | 15.1 | 1.01 ± 0.92 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.0 ± 1.8 | 0.0 | 17.5 | 1.05 ± 0.93 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.0 ± 1.9 | 0.3 | 8.8 | 1.05 ± 0.94 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.1 ± 2.2 | 0.0 | 20.4 | 1.09 ± 1.05 |
| `mattcl-solver/aoc run 5 input-pting` | 3.4 ± 2.1 | 0.3 | 19.2 | 1.20 ± 1.07 |
| `python pting/day05.py input-aspidites` | 63.1 ± 34.5 | 43.6 | 184.9 | 22.36 ± 18.70 |
| `python pting/day05.py input-kcen` | 176.0 ± 62.6 | 85.3 | 290.5 | 62.35 ± 45.23 |
| `python pting/day05.py input-lanjian` | 65.0 ± 35.2 | 45.6 | 206.6 | 23.03 ± 19.17 |
| `python pting/day05.py input-mattcl` | 115.2 ± 75.4 | 45.0 | 329.5 | 40.79 ± 37.14 |
| `python pting/day05.py input-pting` | 73.8 ± 37.4 | 42.4 | 175.9 | 26.14 ± 21.19 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
