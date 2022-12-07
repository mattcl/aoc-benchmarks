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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.6 ± 3.1 | 20.1 | 39.7 | 9.84 ± 4.52 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.7 ± 3.8 | 23.9 | 47.4 | 9.87 ± 4.61 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 27.4 ± 4.6 | 23.7 | 46.1 | 10.11 ± 4.81 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 28.8 ± 5.5 | 23.9 | 51.1 | 10.63 ± 5.14 |
| `aspidites-solver/aoc -i input-pting -d 5` | 28.0 ± 4.7 | 23.1 | 45.3 | 10.34 ± 4.91 |
| `kcen/2022/05/solve input-aspidites` | 195.9 ± 26.0 | 151.6 | 255.0 | 72.37 ± 33.56 |
| `kcen/2022/05/solve input-kcen` | 179.9 ± 27.5 | 143.4 | 229.8 | 66.45 ± 31.22 |
| `kcen/2022/05/solve input-lanjian` | 187.0 ± 24.5 | 155.6 | 234.2 | 69.06 ± 32.00 |
| `kcen/2022/05/solve input-mattcl` | 184.3 ± 23.6 | 158.8 | 229.9 | 68.08 ± 31.48 |
| `kcen/2022/05/solve input-pting` | 166.0 ± 17.9 | 144.6 | 199.3 | 61.33 ± 28.04 |
| `lanjian/day_05 input-aspidites` | 3.4 ± 1.6 | 0.8 | 21.0 | 1.27 ± 0.82 |
| `lanjian/day_05 input-kcen` | 3.1 ± 1.2 | 0.7 | 10.6 | 1.14 ± 0.67 |
| `lanjian/day_05 input-lanjian` | 2.7 ± 1.7 | 0.6 | 16.1 | 1.01 ± 0.77 |
| `lanjian/day_05 input-mattcl` | 2.9 ± 0.9 | 0.9 | 6.3 | 1.08 ± 0.59 |
| `lanjian/day_05 input-pting` | 2.7 ± 1.2 | 0.7 | 14.0 | 1.00 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.7 ± 1.7 | 1.1 | 14.7 | 1.36 ± 0.87 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.0 ± 1.6 | 0.7 | 11.5 | 1.09 ± 0.75 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.0 ± 1.5 | 0.8 | 15.6 | 1.11 ± 0.73 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.7 ± 2.1 | 1.0 | 32.5 | 1.35 ± 0.98 |
| `mattcl-solver/aoc run 5 input-pting` | 3.7 ± 1.6 | 0.3 | 10.6 | 1.35 ± 0.83 |
| `python pting/day05.py input-aspidites` | 58.9 ± 10.0 | 45.8 | 89.2 | 21.77 ± 10.36 |
| `python pting/day05.py input-kcen` | 66.2 ± 12.0 | 42.3 | 107.5 | 24.43 ± 11.73 |
| `python pting/day05.py input-lanjian` | 69.6 ± 10.5 | 56.3 | 100.8 | 25.72 ± 12.07 |
| `python pting/day05.py input-mattcl` | 86.3 ± 27.2 | 50.4 | 147.5 | 31.86 ± 17.37 |
| `python pting/day05.py input-pting` | 62.1 ± 9.6 | 49.2 | 88.0 | 22.92 ± 10.78 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
