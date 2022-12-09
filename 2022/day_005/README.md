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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 37.3 ± 18.0 | 24.1 | 105.8 | 14.88 ± 10.16 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.3 ± 3.5 | 23.4 | 40.0 | 10.48 ± 5.25 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.2 ± 2.9 | 23.5 | 40.4 | 10.45 ± 5.18 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.5 ± 3.9 | 23.5 | 47.0 | 10.58 ± 5.35 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.6 ± 2.6 | 23.1 | 40.4 | 10.20 ± 5.04 |
| `kcen/2022/05/solve input-aspidites` | 169.9 ± 21.6 | 137.6 | 219.0 | 67.74 ± 33.87 |
| `kcen/2022/05/solve input-kcen` | 149.7 ± 24.1 | 123.7 | 239.4 | 59.67 ± 30.41 |
| `kcen/2022/05/solve input-lanjian` | 150.6 ± 16.7 | 127.6 | 193.1 | 60.04 ± 29.78 |
| `kcen/2022/05/solve input-mattcl` | 160.7 ± 20.7 | 136.1 | 194.3 | 64.07 ± 32.06 |
| `kcen/2022/05/solve input-pting` | 150.0 ± 22.7 | 125.0 | 230.3 | 59.78 ± 30.29 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 1.2 | 1.0 | 11.8 | 1.03 ± 0.68 |
| `lanjian/day_05 input-kcen` | 2.5 ± 1.2 | 0.7 | 10.9 | 1.00 |
| `lanjian/day_05 input-lanjian` | 2.8 ± 1.0 | 1.1 | 11.2 | 1.12 ± 0.67 |
| `lanjian/day_05 input-mattcl` | 2.6 ± 1.1 | 0.9 | 9.6 | 1.05 ± 0.66 |
| `lanjian/day_05 input-pting` | 2.7 ± 1.0 | 1.1 | 8.1 | 1.07 ± 0.64 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.1 ± 1.1 | 1.3 | 13.8 | 1.22 ± 0.72 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.0 ± 1.0 | 1.2 | 8.3 | 1.21 ± 0.71 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.9 ± 1.1 | 0.9 | 8.5 | 1.15 ± 0.71 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.8 ± 1.1 | 1.0 | 10.0 | 1.12 ± 0.71 |
| `mattcl-solver/aoc run 5 input-pting` | 3.8 ± 4.4 | 1.2 | 67.7 | 1.51 ± 1.88 |
| `python pting/day05.py input-aspidites` | 58.3 ± 7.4 | 47.8 | 74.9 | 23.23 ± 11.61 |
| `python pting/day05.py input-kcen` | 49.8 ± 6.5 | 40.0 | 77.2 | 19.86 ± 9.95 |
| `python pting/day05.py input-lanjian` | 60.9 ± 15.9 | 45.7 | 129.6 | 24.26 ± 13.34 |
| `python pting/day05.py input-mattcl` | 55.6 ± 15.3 | 40.4 | 128.9 | 22.18 ± 12.33 |
| `python pting/day05.py input-pting` | 54.7 ± 20.7 | 40.9 | 175.6 | 21.80 ± 13.39 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
