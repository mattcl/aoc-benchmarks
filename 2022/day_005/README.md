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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 28.7 ± 6.5 | 23.5 | 55.1 | 10.60 ± 4.86 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.6 ± 1.6 | 23.4 | 38.8 | 9.46 ± 3.80 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.8 ± 2.9 | 23.5 | 40.2 | 9.52 ± 3.93 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.0 ± 2.9 | 23.4 | 37.0 | 9.60 ± 3.96 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.9 ± 2.7 | 23.6 | 39.3 | 9.58 ± 3.94 |
| `kcen/2022/05/solve input-aspidites` | 168.4 ± 17.1 | 146.4 | 203.4 | 62.17 ± 25.50 |
| `kcen/2022/05/solve input-kcen` | 270.4 ± 163.5 | 128.0 | 702.2 | 99.80 ± 72.22 |
| `kcen/2022/05/solve input-lanjian` | 167.8 ± 17.9 | 139.7 | 190.4 | 61.92 ± 25.49 |
| `kcen/2022/05/solve input-mattcl` | 171.6 ± 17.3 | 146.9 | 201.2 | 63.35 ± 25.98 |
| `kcen/2022/05/solve input-pting` | 158.4 ± 22.0 | 136.0 | 206.1 | 58.47 ± 24.62 |
| `lanjian/day_05 input-aspidites` | 2.7 ± 1.1 | 1.0 | 8.8 | 1.00 |
| `lanjian/day_05 input-kcen` | 3.0 ± 1.1 | 0.9 | 11.8 | 1.10 ± 0.59 |
| `lanjian/day_05 input-lanjian` | 2.7 ± 1.0 | 0.9 | 6.6 | 1.01 ± 0.54 |
| `lanjian/day_05 input-mattcl` | 2.8 ± 1.7 | 1.0 | 20.8 | 1.03 ± 0.76 |
| `lanjian/day_05 input-pting` | 3.1 ± 1.1 | 1.0 | 9.7 | 1.13 ± 0.60 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.8 ± 1.2 | 1.3 | 9.8 | 1.05 ± 0.62 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.3 ± 1.3 | 1.2 | 15.9 | 1.23 ± 0.70 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.1 ± 1.3 | 0.9 | 9.7 | 1.15 ± 0.67 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.9 ± 1.0 | 1.2 | 11.6 | 1.09 ± 0.56 |
| `mattcl-solver/aoc run 5 input-pting` | 3.6 ± 1.5 | 0.9 | 12.7 | 1.34 ± 0.76 |
| `python pting/day05.py input-aspidites` | 58.9 ± 13.6 | 41.4 | 122.2 | 21.74 ± 10.00 |
| `python pting/day05.py input-kcen` | 58.1 ± 15.5 | 40.7 | 136.2 | 21.44 ± 10.26 |
| `python pting/day05.py input-lanjian` | 60.5 ± 11.7 | 44.6 | 111.2 | 22.34 ± 9.87 |
| `python pting/day05.py input-mattcl` | 161.9 ± 72.2 | 78.5 | 283.9 | 59.76 ± 35.70 |
| `python pting/day05.py input-pting` | 55.1 ± 13.2 | 42.5 | 123.1 | 20.35 ± 9.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
