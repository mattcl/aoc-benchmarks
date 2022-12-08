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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.1 ± 2.2 | 12.2 | 37.6 | 20.43 ± 19.03 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 24.2 ± 1.0 | 22.6 | 27.9 | 20.54 ± 19.07 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 24.3 ± 1.9 | 22.4 | 35.1 | 20.64 ± 19.22 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 27.0 ± 5.4 | 22.7 | 45.9 | 22.96 ± 21.78 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.5 ± 22.6 | 13.2 | 264.5 | 22.53 ± 28.38 |
| `kcen/2022/05/solve input-aspidites` | 179.9 ± 25.7 | 150.7 | 241.5 | 152.74 ± 143.33 |
| `kcen/2022/05/solve input-kcen` | 162.8 ± 17.7 | 135.9 | 212.5 | 138.19 ± 129.03 |
| `kcen/2022/05/solve input-lanjian` | 172.5 ± 18.4 | 137.9 | 213.3 | 146.44 ± 136.71 |
| `kcen/2022/05/solve input-mattcl` | 169.7 ± 17.1 | 136.5 | 190.8 | 144.07 ± 134.41 |
| `kcen/2022/05/solve input-pting` | 158.6 ± 16.0 | 129.9 | 190.6 | 134.67 ± 125.63 |
| `lanjian/day_05 input-aspidites` | 2.3 ± 2.2 | 0.1 | 25.5 | 1.94 ± 2.63 |
| `lanjian/day_05 input-kcen` | 1.5 ± 0.9 | 0.0 | 6.3 | 1.29 ± 1.44 |
| `lanjian/day_05 input-lanjian` | 1.6 ± 1.0 | 0.2 | 8.2 | 1.37 ± 1.54 |
| `lanjian/day_05 input-mattcl` | 1.2 ± 1.1 | 0.0 | 12.4 | 1.00 |
| `lanjian/day_05 input-pting` | 1.8 ± 1.0 | 0.1 | 6.4 | 1.57 ± 1.69 |
| `mattcl-solver/aoc run 5 input-aspidites` | 1.8 ± 1.2 | 0.1 | 10.3 | 1.54 ± 1.75 |
| `mattcl-solver/aoc run 5 input-kcen` | 1.5 ± 0.9 | 0.2 | 7.4 | 1.31 ± 1.43 |
| `mattcl-solver/aoc run 5 input-lanjian` | 1.8 ± 1.3 | 0.0 | 13.7 | 1.54 ± 1.83 |
| `mattcl-solver/aoc run 5 input-mattcl` | 1.5 ± 3.3 | 0.0 | 82.7 | 1.26 ± 3.03 |
| `mattcl-solver/aoc run 5 input-pting` | 1.6 ± 1.1 | 0.0 | 13.8 | 1.39 ± 1.56 |
| `python pting/day05.py input-aspidites` | 91.7 ± 34.9 | 52.3 | 181.9 | 77.84 ± 78.02 |
| `python pting/day05.py input-kcen` | 53.8 ± 6.6 | 44.4 | 70.5 | 45.66 ± 42.72 |
| `python pting/day05.py input-lanjian` | 51.6 ± 7.4 | 41.1 | 85.2 | 43.83 ± 41.13 |
| `python pting/day05.py input-mattcl` | 53.7 ± 5.8 | 43.7 | 69.1 | 45.61 ± 42.59 |
| `python pting/day05.py input-pting` | 55.1 ± 8.8 | 44.4 | 97.8 | 46.79 ± 44.04 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
