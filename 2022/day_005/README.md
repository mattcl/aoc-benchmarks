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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 27.0 ± 4.4 | 23.6 | 51.6 | 13.47 ± 8.76 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.8 ± 5.3 | 23.4 | 64.5 | 13.40 ± 8.84 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.2 ± 3.2 | 23.6 | 39.4 | 13.07 ± 8.38 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 29.3 ± 6.9 | 24.0 | 71.3 | 14.66 ± 9.85 |
| `aspidites-solver/aoc -i input-pting -d 5` | 27.4 ± 5.2 | 23.6 | 52.8 | 13.67 ± 8.99 |
| `kcen/2022/05/solve input-aspidites` | 184.0 ± 20.5 | 151.1 | 236.6 | 91.96 ± 58.79 |
| `kcen/2022/05/solve input-kcen` | 177.0 ± 15.4 | 150.2 | 207.4 | 88.48 ± 56.23 |
| `kcen/2022/05/solve input-lanjian` | 179.5 ± 18.4 | 152.5 | 215.6 | 89.70 ± 57.20 |
| `kcen/2022/05/solve input-mattcl` | 272.5 ± 103.6 | 152.3 | 455.4 | 136.18 ± 100.15 |
| `kcen/2022/05/solve input-pting` | 194.2 ± 25.1 | 159.3 | 250.7 | 97.04 ± 62.37 |
| `lanjian/day_05 input-aspidites` | 2.7 ± 2.4 | 0.5 | 28.2 | 1.36 ± 1.48 |
| `lanjian/day_05 input-kcen` | 2.6 ± 2.1 | 0.3 | 33.0 | 1.28 ± 1.34 |
| `lanjian/day_05 input-lanjian` | 2.9 ± 1.8 | 0.6 | 15.4 | 1.43 ± 1.28 |
| `lanjian/day_05 input-mattcl` | 3.0 ± 2.1 | 0.5 | 26.1 | 1.52 ± 1.42 |
| `lanjian/day_05 input-pting` | 2.0 ± 1.3 | 0.2 | 9.5 | 1.00 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.1 ± 1.8 | 1.0 | 19.6 | 1.54 ± 1.32 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.9 ± 1.9 | 0.6 | 19.3 | 1.47 ± 1.32 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.3 ± 4.7 | 0.5 | 66.1 | 1.65 ± 2.55 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.4 ± 2.8 | 0.9 | 46.6 | 1.70 ± 1.76 |
| `mattcl-solver/aoc run 5 input-pting` | 2.9 ± 2.2 | 1.0 | 17.9 | 1.46 ± 1.43 |
| `python pting/day05.py input-aspidites` | 59.5 ± 8.0 | 46.8 | 79.3 | 29.76 ± 19.16 |
| `python pting/day05.py input-kcen` | 60.4 ± 8.9 | 45.6 | 84.6 | 30.19 ± 19.52 |
| `python pting/day05.py input-lanjian` | 62.6 ± 9.7 | 47.9 | 86.2 | 31.29 ± 20.29 |
| `python pting/day05.py input-mattcl` | 63.3 ± 8.6 | 48.9 | 78.1 | 31.62 ± 20.36 |
| `python pting/day05.py input-pting` | 66.1 ± 9.5 | 52.1 | 95.2 | 33.04 ± 21.34 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
