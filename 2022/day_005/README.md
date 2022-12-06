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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.3 ± 0.7 | 22.9 | 26.2 | 17.63 ± 9.47 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 30.0 ± 6.2 | 23.8 | 55.2 | 21.78 ± 12.52 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.1 ± 2.4 | 23.0 | 36.8 | 18.25 ± 9.94 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 24.2 ± 1.9 | 22.9 | 38.2 | 17.55 ± 9.52 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.3 ± 2.9 | 23.0 | 37.1 | 18.37 ± 10.07 |
| `kcen/2022/05/solve input-aspidites` | 152.0 ± 19.0 | 121.5 | 193.7 | 110.41 ± 60.84 |
| `kcen/2022/05/solve input-kcen` | 199.0 ± 18.9 | 171.2 | 231.9 | 144.54 ± 78.78 |
| `kcen/2022/05/solve input-lanjian` | 141.4 ± 14.9 | 123.3 | 195.7 | 102.71 ± 56.18 |
| `kcen/2022/05/solve input-mattcl` | 146.7 ± 15.0 | 120.2 | 176.1 | 106.58 ± 58.23 |
| `kcen/2022/05/solve input-pting` | 153.0 ± 12.7 | 131.4 | 177.7 | 111.17 ± 60.38 |
| `lanjian/day_05 input-aspidites` | 1.4 ± 0.7 | 0.4 | 6.0 | 1.00 |
| `lanjian/day_05 input-kcen` | 1.8 ± 0.9 | 0.4 | 5.2 | 1.31 ± 0.94 |
| `lanjian/day_05 input-lanjian` | 1.9 ± 0.9 | 0.4 | 7.8 | 1.35 ± 0.96 |
| `lanjian/day_05 input-mattcl` | 2.1 ± 1.4 | 0.4 | 15.1 | 1.55 ± 1.34 |
| `lanjian/day_05 input-pting` | 1.9 ± 1.0 | 0.5 | 8.1 | 1.37 ± 1.04 |
| `mattcl-solver/aoc run 5 input-aspidites` | 1.8 ± 0.9 | 0.4 | 9.2 | 1.31 ± 0.95 |
| `mattcl-solver/aoc run 5 input-kcen` | 1.9 ± 1.2 | 0.4 | 12.2 | 1.36 ± 1.14 |
| `mattcl-solver/aoc run 5 input-lanjian` | 1.9 ± 0.8 | 0.5 | 9.3 | 1.36 ± 0.96 |
| `mattcl-solver/aoc run 5 input-mattcl` | 1.9 ± 1.1 | 0.5 | 13.1 | 1.41 ± 1.11 |
| `mattcl-solver/aoc run 5 input-pting` | 1.5 ± 0.8 | 0.4 | 6.4 | 1.07 ± 0.84 |
| `python pting/day05.py input-aspidites` | 49.6 ± 4.7 | 39.8 | 65.3 | 35.99 ± 19.62 |
| `python pting/day05.py input-kcen` | 52.4 ± 7.2 | 41.4 | 79.6 | 38.05 ± 21.07 |
| `python pting/day05.py input-lanjian` | 51.7 ± 5.9 | 40.6 | 74.6 | 37.59 ± 20.63 |
| `python pting/day05.py input-mattcl` | 50.7 ± 8.2 | 40.3 | 69.1 | 36.82 ± 20.64 |
| `python pting/day05.py input-pting` | 53.7 ± 7.1 | 43.0 | 76.2 | 38.97 ± 21.54 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
