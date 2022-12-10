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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.2 ± 3.0 | 22.6 | 43.8 | 13.64 ± 6.75 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.3 ± 3.9 | 22.6 | 45.2 | 13.71 ± 6.91 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.7 ± 4.1 | 22.4 | 48.2 | 13.93 ± 7.05 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.0 ± 2.6 | 22.6 | 34.4 | 13.57 ± 6.66 |
| `aspidites-solver/aoc -i input-pting -d 5` | 48.8 ± 51.7 | 22.9 | 306.0 | 26.45 ± 30.78 |
| `kcen/2022/05/solve input-aspidites` | 173.4 ± 16.8 | 143.1 | 205.0 | 94.02 ± 46.06 |
| `kcen/2022/05/solve input-kcen` | 167.7 ± 17.1 | 142.0 | 199.2 | 90.96 ± 44.66 |
| `kcen/2022/05/solve input-lanjian` | 184.9 ± 25.3 | 154.1 | 228.2 | 100.28 ± 50.07 |
| `kcen/2022/05/solve input-mattcl` | 159.6 ± 18.9 | 137.3 | 197.2 | 86.57 ± 42.82 |
| `kcen/2022/05/solve input-pting` | 163.9 ± 15.8 | 142.4 | 193.0 | 88.86 ± 43.52 |
| `lanjian/day_05 input-aspidites` | 1.8 ± 0.9 | 0.5 | 11.7 | 1.00 |
| `lanjian/day_05 input-kcen` | 2.4 ± 2.0 | 0.7 | 28.3 | 1.28 ± 1.22 |
| `lanjian/day_05 input-lanjian` | 2.8 ± 3.5 | 0.3 | 64.3 | 1.53 ± 2.02 |
| `lanjian/day_05 input-mattcl` | 2.3 ± 1.4 | 0.4 | 14.5 | 1.24 ± 0.95 |
| `lanjian/day_05 input-pting` | 2.5 ± 1.1 | 0.4 | 8.7 | 1.33 ± 0.86 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.1 ± 1.0 | 0.6 | 12.1 | 1.14 ± 0.77 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.7 ± 1.1 | 1.0 | 14.3 | 1.47 ± 0.94 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.3 ± 0.8 | 0.9 | 6.3 | 1.26 ± 0.75 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.3 ± 1.0 | 0.8 | 10.2 | 1.23 ± 0.79 |
| `mattcl-solver/aoc run 5 input-pting` | 2.5 ± 1.0 | 0.7 | 11.7 | 1.34 ± 0.85 |
| `python pting/day05.py input-aspidites` | 56.7 ± 8.3 | 43.1 | 74.1 | 30.77 ± 15.44 |
| `python pting/day05.py input-kcen` | 62.6 ± 15.6 | 39.5 | 126.8 | 33.95 ± 18.37 |
| `python pting/day05.py input-lanjian` | 111.7 ± 58.0 | 49.7 | 282.0 | 60.58 ± 42.84 |
| `python pting/day05.py input-mattcl` | 54.7 ± 4.7 | 45.8 | 66.2 | 29.67 ± 14.47 |
| `python pting/day05.py input-pting` | 60.6 ± 7.9 | 47.7 | 80.9 | 32.87 ± 16.36 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
