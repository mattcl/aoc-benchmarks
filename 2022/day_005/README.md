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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.8 ± 3.6 | 24.0 | 39.1 | 11.30 ± 4.98 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.8 ± 4.2 | 23.4 | 41.4 | 11.33 ± 5.07 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 27.1 ± 3.6 | 23.7 | 37.5 | 11.42 ± 5.02 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 28.1 ± 6.2 | 24.3 | 56.7 | 11.85 ± 5.61 |
| `aspidites-solver/aoc -i input-pting -d 5` | 27.6 ± 5.2 | 23.9 | 57.1 | 11.64 ± 5.36 |
| `kcen/2022/05/solve input-aspidites` | 183.7 ± 17.2 | 149.5 | 210.0 | 77.50 ± 33.32 |
| `kcen/2022/05/solve input-kcen` | 171.8 ± 17.6 | 145.8 | 211.2 | 72.48 ± 31.31 |
| `kcen/2022/05/solve input-lanjian` | 178.1 ± 12.1 | 156.9 | 197.8 | 75.14 ± 31.94 |
| `kcen/2022/05/solve input-mattcl` | 185.2 ± 11.9 | 168.9 | 206.9 | 78.13 ± 33.17 |
| `kcen/2022/05/solve input-pting` | 181.5 ± 11.2 | 162.6 | 199.4 | 76.55 ± 32.47 |
| `lanjian/day_05 input-aspidites` | 2.8 ± 1.2 | 1.0 | 12.6 | 1.18 ± 0.70 |
| `lanjian/day_05 input-kcen` | 3.2 ± 1.7 | 1.2 | 17.6 | 1.37 ± 0.92 |
| `lanjian/day_05 input-lanjian` | 2.6 ± 1.0 | 1.1 | 8.3 | 1.10 ± 0.62 |
| `lanjian/day_05 input-mattcl` | 2.4 ± 1.0 | 0.9 | 11.0 | 1.00 |
| `lanjian/day_05 input-pting` | 2.6 ± 1.4 | 0.9 | 13.3 | 1.10 ± 0.74 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.6 ± 1.8 | 1.4 | 19.1 | 1.51 ± 1.00 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.7 ± 1.5 | 1.6 | 15.6 | 1.55 ± 0.92 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.2 ± 1.3 | 1.4 | 14.2 | 1.35 ± 0.78 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.7 ± 1.1 | 1.1 | 9.6 | 1.12 ± 0.66 |
| `mattcl-solver/aoc run 5 input-pting` | 3.0 ± 1.1 | 1.0 | 9.6 | 1.27 ± 0.70 |
| `python pting/day05.py input-aspidites` | 65.0 ± 10.3 | 49.2 | 88.4 | 27.44 ± 12.31 |
| `python pting/day05.py input-kcen` | 64.6 ± 10.0 | 49.6 | 91.4 | 27.24 ± 12.19 |
| `python pting/day05.py input-lanjian` | 62.1 ± 9.8 | 49.5 | 96.6 | 26.18 ± 11.73 |
| `python pting/day05.py input-mattcl` | 64.2 ± 6.4 | 53.4 | 78.2 | 27.08 ± 11.68 |
| `python pting/day05.py input-pting` | 59.3 ± 7.4 | 43.3 | 77.4 | 25.01 ± 10.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
