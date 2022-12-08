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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.0 ± 1.6 | 24.0 | 36.7 | 9.99 ± 5.29 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.1 ± 2.4 | 24.0 | 41.7 | 10.04 ± 5.35 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 30.4 ± 9.0 | 24.1 | 72.7 | 11.68 ± 7.04 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.3 ± 1.9 | 23.7 | 36.0 | 9.73 ± 5.16 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.5 ± 3.5 | 24.0 | 44.2 | 10.19 ± 5.52 |
| `kcen/2022/05/solve input-aspidites` | 159.0 ± 14.1 | 137.2 | 202.7 | 61.06 ± 32.54 |
| `kcen/2022/05/solve input-kcen` | 157.3 ± 14.2 | 139.7 | 179.4 | 60.41 ± 32.21 |
| `kcen/2022/05/solve input-lanjian` | 154.8 ± 9.0 | 135.9 | 168.1 | 59.45 ± 31.43 |
| `kcen/2022/05/solve input-mattcl` | 172.2 ± 23.3 | 138.1 | 230.2 | 66.15 ± 35.89 |
| `kcen/2022/05/solve input-pting` | 158.7 ± 18.0 | 131.4 | 205.7 | 60.94 ± 32.76 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 1.4 | 1.0 | 23.3 | 1.00 |
| `lanjian/day_05 input-kcen` | 3.4 ± 1.2 | 1.6 | 12.7 | 1.32 ± 0.83 |
| `lanjian/day_05 input-lanjian` | 3.5 ± 6.7 | 1.3 | 134.4 | 1.36 ± 2.65 |
| `lanjian/day_05 input-mattcl` | 2.8 ± 1.5 | 1.0 | 14.6 | 1.08 ± 0.80 |
| `lanjian/day_05 input-pting` | 2.9 ± 0.9 | 1.2 | 6.9 | 1.12 ± 0.69 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.7 ± 0.9 | 1.1 | 9.0 | 1.04 ± 0.64 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.5 ± 1.2 | 1.6 | 14.3 | 1.33 ± 0.83 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.1 ± 1.6 | 1.2 | 21.4 | 1.19 ± 0.89 |
| `mattcl-solver/aoc run 5 input-mattcl` | 4.1 ± 2.9 | 1.5 | 43.6 | 1.58 ± 1.40 |
| `mattcl-solver/aoc run 5 input-pting` | 2.7 ± 1.4 | 1.0 | 14.0 | 1.04 ± 0.77 |
| `python pting/day05.py input-aspidites` | 54.8 ± 5.6 | 47.2 | 71.8 | 21.05 ± 11.26 |
| `python pting/day05.py input-kcen` | 55.8 ± 5.9 | 45.7 | 75.2 | 21.44 ± 11.49 |
| `python pting/day05.py input-lanjian` | 52.8 ± 7.0 | 43.8 | 72.3 | 20.29 ± 10.99 |
| `python pting/day05.py input-mattcl` | 56.9 ± 6.2 | 45.2 | 72.3 | 21.84 ± 11.72 |
| `python pting/day05.py input-pting` | 59.1 ± 6.6 | 47.4 | 75.4 | 22.72 ± 12.20 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
