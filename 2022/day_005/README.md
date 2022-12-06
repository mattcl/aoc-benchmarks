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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 28.6 ± 7.5 | 23.2 | 61.5 | 11.48 ± 5.92 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.8 ± 2.8 | 23.4 | 35.9 | 10.34 ± 4.73 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 29.2 ± 7.8 | 23.3 | 61.9 | 11.71 ± 6.06 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 28.1 ± 6.3 | 23.5 | 59.7 | 11.27 ± 5.60 |
| `aspidites-solver/aoc -i input-pting -d 5` | 27.3 ± 5.4 | 23.7 | 47.6 | 10.94 ± 5.32 |
| `kcen/2022/05/solve input-aspidites` | 230.0 ± 52.5 | 177.3 | 345.3 | 92.19 ± 46.05 |
| `kcen/2022/05/solve input-kcen` | 185.9 ± 22.7 | 150.9 | 243.7 | 74.51 ± 34.34 |
| `kcen/2022/05/solve input-lanjian` | 198.7 ± 20.1 | 156.0 | 225.2 | 79.64 ± 36.29 |
| `kcen/2022/05/solve input-mattcl` | 191.6 ± 14.3 | 172.3 | 227.0 | 76.81 ± 34.60 |
| `kcen/2022/05/solve input-pting` | 187.0 ± 8.9 | 178.0 | 207.6 | 74.98 ± 33.51 |
| `lanjian/day_05 input-aspidites` | 3.1 ± 1.6 | 1.1 | 13.3 | 1.25 ± 0.85 |
| `lanjian/day_05 input-kcen` | 2.6 ± 1.3 | 0.8 | 16.8 | 1.05 ± 0.69 |
| `lanjian/day_05 input-lanjian` | 4.7 ± 2.3 | 2.1 | 18.3 | 1.87 ± 1.25 |
| `lanjian/day_05 input-mattcl` | 3.3 ± 1.3 | 1.2 | 15.1 | 1.32 ± 0.79 |
| `lanjian/day_05 input-pting` | 2.7 ± 1.5 | 0.6 | 15.3 | 1.06 ± 0.78 |
| `mattcl-solver/aoc run 5 input-aspidites` | 4.2 ± 2.2 | 1.4 | 17.5 | 1.67 ± 1.16 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.5 ± 1.1 | 0.9 | 11.5 | 1.00 |
| `mattcl-solver/aoc run 5 input-lanjian` | 4.0 ± 2.0 | 1.6 | 17.9 | 1.62 ± 1.08 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.3 ± 1.5 | 1.2 | 11.9 | 1.34 ± 0.84 |
| `mattcl-solver/aoc run 5 input-pting` | 2.9 ± 1.1 | 0.9 | 7.6 | 1.18 ± 0.69 |
| `python pting/day05.py input-aspidites` | 74.2 ± 12.1 | 57.2 | 122.0 | 29.76 ± 14.08 |
| `python pting/day05.py input-kcen` | 62.0 ± 11.7 | 45.6 | 99.6 | 24.84 ± 12.00 |
| `python pting/day05.py input-lanjian` | 79.1 ± 17.7 | 61.5 | 129.9 | 31.71 ± 15.77 |
| `python pting/day05.py input-mattcl` | 69.3 ± 15.1 | 56.0 | 151.8 | 27.79 ± 13.76 |
| `python pting/day05.py input-pting` | 65.2 ± 10.9 | 53.5 | 124.9 | 26.15 ± 12.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
