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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.8 ± 4.6 | 23.2 | 39.9 | 12.68 ± 6.44 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.3 ± 3.4 | 23.3 | 38.3 | 12.03 ± 5.98 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.3 ± 2.8 | 23.1 | 38.6 | 11.54 ± 5.69 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.6 ± 4.7 | 23.7 | 42.3 | 12.61 ± 6.43 |
| `aspidites-solver/aoc -i input-pting -d 5` | 38.7 ± 24.5 | 23.5 | 158.8 | 17.68 ± 14.06 |
| `kcen/2022/05/solve input-aspidites` | 212.2 ± 29.8 | 171.8 | 264.7 | 96.90 ± 48.48 |
| `kcen/2022/05/solve input-kcen` | 166.1 ± 17.7 | 144.4 | 208.5 | 75.84 ± 37.30 |
| `kcen/2022/05/solve input-lanjian` | 196.4 ± 58.4 | 133.0 | 298.0 | 89.66 ± 50.65 |
| `kcen/2022/05/solve input-mattcl` | 160.0 ± 20.7 | 136.1 | 206.2 | 73.05 ± 36.33 |
| `kcen/2022/05/solve input-pting` | 162.2 ± 18.7 | 129.8 | 201.8 | 74.05 ± 36.57 |
| `lanjian/day_05 input-aspidites` | 2.5 ± 1.4 | 0.6 | 14.8 | 1.13 ± 0.84 |
| `lanjian/day_05 input-kcen` | 2.9 ± 1.2 | 0.8 | 11.1 | 1.31 ± 0.85 |
| `lanjian/day_05 input-lanjian` | 2.2 ± 0.9 | 0.6 | 7.9 | 1.02 ± 0.63 |
| `lanjian/day_05 input-mattcl` | 2.4 ± 1.4 | 0.7 | 23.1 | 1.08 ± 0.81 |
| `lanjian/day_05 input-pting` | 3.3 ± 1.9 | 0.8 | 38.2 | 1.49 ± 1.12 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.4 ± 1.1 | 0.4 | 7.6 | 1.10 ± 0.73 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.9 ± 1.4 | 0.7 | 14.7 | 1.33 ± 0.90 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.4 ± 1.2 | 0.5 | 13.5 | 1.08 ± 0.77 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.2 ± 1.1 | 0.6 | 5.7 | 1.00 |
| `mattcl-solver/aoc run 5 input-pting` | 2.8 ± 1.1 | 0.9 | 13.9 | 1.28 ± 0.78 |
| `python pting/day05.py input-aspidites` | 59.2 ± 9.7 | 46.7 | 91.4 | 27.05 ± 13.72 |
| `python pting/day05.py input-kcen` | 58.2 ± 10.6 | 42.3 | 89.9 | 26.59 ± 13.66 |
| `python pting/day05.py input-lanjian` | 60.6 ± 10.4 | 44.2 | 85.3 | 27.68 ± 14.12 |
| `python pting/day05.py input-mattcl` | 54.9 ± 9.4 | 42.6 | 92.3 | 25.05 ± 12.77 |
| `python pting/day05.py input-pting` | 62.1 ± 9.2 | 46.5 | 90.5 | 28.34 ± 14.24 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
