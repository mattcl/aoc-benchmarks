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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.6 ± 2.8 | 22.9 | 35.9 | 14.42 ± 7.76 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 24.6 ± 1.9 | 22.8 | 35.1 | 13.85 ± 7.39 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 23.9 ± 1.0 | 22.6 | 27.5 | 13.47 ± 7.13 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 24.8 ± 2.5 | 22.9 | 46.2 | 13.98 ± 7.50 |
| `aspidites-solver/aoc -i input-pting -d 5` | 24.8 ± 2.7 | 22.6 | 36.9 | 13.95 ± 7.51 |
| `kcen/2022/05/solve input-aspidites` | 162.2 ± 12.8 | 142.6 | 182.6 | 91.24 ± 48.64 |
| `kcen/2022/05/solve input-kcen` | 163.0 ± 17.9 | 144.3 | 198.3 | 91.70 ± 49.39 |
| `kcen/2022/05/solve input-lanjian` | 159.4 ± 23.6 | 131.0 | 204.8 | 89.70 ± 49.13 |
| `kcen/2022/05/solve input-mattcl` | 211.0 ± 47.9 | 145.9 | 307.2 | 118.73 ± 68.15 |
| `kcen/2022/05/solve input-pting` | 157.1 ± 15.2 | 139.7 | 181.4 | 88.38 ± 47.39 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 2.0 | 0.7 | 19.2 | 1.48 ± 1.38 |
| `lanjian/day_05 input-kcen` | 2.5 ± 1.3 | 0.9 | 16.8 | 1.40 ± 1.05 |
| `lanjian/day_05 input-lanjian` | 2.2 ± 0.9 | 0.6 | 7.6 | 1.22 ± 0.82 |
| `lanjian/day_05 input-mattcl` | 1.8 ± 0.9 | 0.5 | 13.7 | 1.00 |
| `lanjian/day_05 input-pting` | 2.1 ± 1.2 | 0.7 | 16.5 | 1.19 ± 0.92 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.6 ± 1.2 | 0.9 | 13.4 | 1.44 ± 1.02 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.6 ± 1.6 | 0.7 | 15.3 | 1.49 ± 1.18 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.8 ± 0.9 | 1.1 | 13.0 | 1.56 ± 0.98 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.1 ± 0.7 | 0.9 | 6.6 | 1.18 ± 0.75 |
| `mattcl-solver/aoc run 5 input-pting` | 2.5 ± 1.0 | 0.7 | 8.4 | 1.42 ± 0.92 |
| `python pting/day05.py input-aspidites` | 57.3 ± 8.8 | 43.5 | 82.5 | 32.23 ± 17.70 |
| `python pting/day05.py input-kcen` | 55.0 ± 6.9 | 41.8 | 72.7 | 30.92 ± 16.76 |
| `python pting/day05.py input-lanjian` | 52.5 ± 6.3 | 44.8 | 70.4 | 29.53 ± 15.97 |
| `python pting/day05.py input-mattcl` | 55.9 ± 7.3 | 43.3 | 83.4 | 31.45 ± 17.09 |
| `python pting/day05.py input-pting` | 54.3 ± 5.9 | 45.3 | 68.4 | 30.52 ± 16.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
