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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 23.9 ± 1.9 | 22.2 | 33.5 | 32.84 ± 35.70 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 24.3 ± 1.8 | 22.5 | 34.5 | 33.40 ± 36.30 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 23.8 ± 1.9 | 21.9 | 36.7 | 32.68 ± 35.54 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 24.7 ± 3.2 | 22.3 | 44.4 | 33.96 ± 37.09 |
| `aspidites-solver/aoc -i input-pting -d 5` | 24.8 ± 2.8 | 22.7 | 41.8 | 34.06 ± 37.12 |
| `kcen/2022/05/solve input-aspidites` | 157.8 ± 13.1 | 140.4 | 182.2 | 216.73 ± 235.71 |
| `kcen/2022/05/solve input-kcen` | 148.4 ± 12.1 | 132.0 | 181.3 | 203.87 ± 221.69 |
| `kcen/2022/05/solve input-lanjian` | 148.0 ± 10.0 | 116.7 | 174.9 | 203.35 ± 220.94 |
| `kcen/2022/05/solve input-mattcl` | 175.6 ± 28.8 | 129.1 | 223.3 | 241.26 ± 264.59 |
| `kcen/2022/05/solve input-pting` | 153.4 ± 23.1 | 124.1 | 225.6 | 210.72 ± 230.69 |
| `lanjian/day_05 input-aspidites` | 1.3 ± 1.2 | 0.0 | 9.2 | 1.72 ± 2.48 |
| `lanjian/day_05 input-kcen` | 1.5 ± 1.5 | 0.0 | 13.0 | 2.04 ± 3.06 |
| `lanjian/day_05 input-lanjian` | 1.1 ± 1.1 | 0.0 | 16.3 | 1.49 ± 2.22 |
| `lanjian/day_05 input-mattcl` | 1.0 ± 1.4 | 0.0 | 16.2 | 1.38 ± 2.39 |
| `lanjian/day_05 input-pting` | 1.3 ± 1.0 | 0.0 | 10.5 | 1.76 ± 2.38 |
| `mattcl-solver/aoc run 5 input-aspidites` | 1.5 ± 1.3 | 0.0 | 8.0 | 2.12 ± 2.91 |
| `mattcl-solver/aoc run 5 input-kcen` | 1.4 ± 1.2 | 0.0 | 9.1 | 1.98 ± 2.73 |
| `mattcl-solver/aoc run 5 input-lanjian` | 0.7 ± 0.8 | 0.0 | 5.2 | 1.00 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.7 ± 8.9 | 0.0 | 143.0 | 5.11 ± 13.37 |
| `mattcl-solver/aoc run 5 input-pting` | 1.8 ± 1.7 | 0.0 | 34.6 | 2.46 ± 3.59 |
| `python pting/day05.py input-aspidites` | 50.6 ± 6.1 | 41.9 | 69.0 | 69.53 ± 75.87 |
| `python pting/day05.py input-kcen` | 55.5 ± 8.7 | 42.9 | 83.6 | 76.24 ± 83.52 |
| `python pting/day05.py input-lanjian` | 52.2 ± 7.7 | 41.0 | 88.8 | 71.75 ± 78.53 |
| `python pting/day05.py input-mattcl` | 50.6 ± 7.2 | 40.0 | 73.5 | 69.56 ± 76.08 |
| `python pting/day05.py input-pting` | 54.4 ± 7.6 | 44.7 | 83.9 | 74.69 ± 81.66 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
