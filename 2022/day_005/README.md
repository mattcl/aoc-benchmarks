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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.2 ± 3.1 | 22.6 | 45.4 | 12.60 ± 6.18 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 24.8 ± 3.0 | 22.4 | 43.2 | 12.42 ± 6.09 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.3 ± 1.9 | 22.5 | 37.7 | 12.19 ± 5.87 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 31.0 ± 13.4 | 23.0 | 77.7 | 15.54 ± 9.98 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.1 ± 3.1 | 22.7 | 38.4 | 12.58 ± 6.18 |
| `kcen/2022/05/solve input-aspidites` | 164.8 ± 18.9 | 138.1 | 205.4 | 82.52 ± 40.36 |
| `kcen/2022/05/solve input-kcen` | 161.8 ± 23.2 | 130.3 | 209.0 | 81.05 ± 40.25 |
| `kcen/2022/05/solve input-lanjian` | 149.6 ± 11.5 | 127.7 | 174.5 | 74.89 ± 36.07 |
| `kcen/2022/05/solve input-mattcl` | 257.9 ± 90.8 | 140.3 | 436.9 | 129.18 ± 76.42 |
| `kcen/2022/05/solve input-pting` | 169.4 ± 21.8 | 138.2 | 216.0 | 84.83 ± 41.78 |
| `lanjian/day_05 input-aspidites` | 2.3 ± 1.4 | 0.5 | 15.2 | 1.14 ± 0.90 |
| `lanjian/day_05 input-kcen` | 2.2 ± 1.4 | 0.3 | 14.2 | 1.09 ± 0.85 |
| `lanjian/day_05 input-lanjian` | 2.2 ± 1.5 | 0.2 | 17.2 | 1.11 ± 0.93 |
| `lanjian/day_05 input-mattcl` | 2.2 ± 1.3 | 0.2 | 13.2 | 1.10 ± 0.83 |
| `lanjian/day_05 input-pting` | 2.1 ± 2.2 | 0.2 | 31.6 | 1.05 ± 1.20 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.0 ± 0.9 | 0.5 | 8.8 | 1.00 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.1 ± 1.2 | 0.4 | 12.7 | 1.03 ± 0.79 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.5 ± 1.7 | 0.5 | 14.0 | 1.24 ± 1.02 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.2 ± 1.4 | 0.5 | 20.7 | 1.13 ± 0.87 |
| `mattcl-solver/aoc run 5 input-pting` | 2.2 ± 1.1 | 0.6 | 8.2 | 1.12 ± 0.77 |
| `python pting/day05.py input-aspidites` | 67.2 ± 30.1 | 41.9 | 167.0 | 33.63 ± 21.98 |
| `python pting/day05.py input-kcen` | 54.7 ± 10.7 | 40.1 | 113.3 | 27.39 ± 14.08 |
| `python pting/day05.py input-lanjian` | 55.4 ± 26.4 | 41.7 | 214.9 | 27.75 ± 18.67 |
| `python pting/day05.py input-mattcl` | 50.9 ± 15.4 | 38.5 | 131.2 | 25.50 ± 14.38 |
| `python pting/day05.py input-pting` | 58.8 ± 17.1 | 45.3 | 164.4 | 29.42 ± 16.41 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
