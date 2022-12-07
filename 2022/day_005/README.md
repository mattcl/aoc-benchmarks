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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 28.2 ± 4.5 | 23.9 | 49.4 | 9.14 ± 4.71 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.7 ± 4.3 | 24.1 | 46.6 | 8.97 ± 4.61 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.7 ± 3.3 | 23.8 | 44.8 | 8.66 ± 4.37 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.1 ± 3.5 | 24.0 | 40.3 | 8.77 ± 4.44 |
| `aspidites-solver/aoc -i input-pting -d 5` | 28.4 ± 6.3 | 24.1 | 66.6 | 9.21 ± 4.95 |
| `kcen/2022/05/solve input-aspidites` | 179.7 ± 15.2 | 151.5 | 221.2 | 58.21 ± 28.93 |
| `kcen/2022/05/solve input-kcen` | 197.4 ± 28.7 | 154.7 | 254.9 | 63.96 ± 32.67 |
| `kcen/2022/05/solve input-lanjian` | 181.1 ± 25.4 | 152.0 | 246.5 | 58.66 ± 29.89 |
| `kcen/2022/05/solve input-mattcl` | 170.5 ± 19.3 | 142.5 | 213.8 | 55.22 ± 27.76 |
| `kcen/2022/05/solve input-pting` | 174.6 ± 15.8 | 152.8 | 210.1 | 56.56 ± 28.17 |
| `lanjian/day_05 input-aspidites` | 3.1 ± 1.5 | 0.7 | 16.8 | 1.00 |
| `lanjian/day_05 input-kcen` | 6.1 ± 7.4 | 0.8 | 75.6 | 1.97 ± 2.59 |
| `lanjian/day_05 input-lanjian` | 3.8 ± 1.8 | 1.1 | 18.3 | 1.23 ± 0.85 |
| `lanjian/day_05 input-mattcl` | 3.7 ± 1.7 | 1.1 | 18.1 | 1.21 ± 0.82 |
| `lanjian/day_05 input-pting` | 3.6 ± 1.3 | 1.3 | 9.6 | 1.15 ± 0.71 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.6 ± 1.2 | 1.3 | 8.2 | 1.18 ± 0.70 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.1 ± 1.2 | 1.0 | 8.0 | 1.02 ± 0.63 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.2 ± 1.2 | 0.8 | 13.3 | 1.04 ± 0.64 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.4 ± 1.7 | 1.0 | 19.0 | 1.09 ± 0.76 |
| `mattcl-solver/aoc run 5 input-pting` | 3.3 ± 1.2 | 1.0 | 7.9 | 1.08 ± 0.65 |
| `python pting/day05.py input-aspidites` | 64.2 ± 11.2 | 51.6 | 97.1 | 20.79 ± 10.81 |
| `python pting/day05.py input-kcen` | 64.9 ± 9.9 | 50.0 | 92.0 | 21.04 ± 10.79 |
| `python pting/day05.py input-lanjian` | 66.0 ± 11.7 | 50.2 | 103.9 | 21.38 ± 11.14 |
| `python pting/day05.py input-mattcl` | 59.6 ± 8.0 | 46.9 | 88.7 | 19.32 ± 9.81 |
| `python pting/day05.py input-pting` | 65.7 ± 11.3 | 52.1 | 93.0 | 21.27 ± 11.04 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
