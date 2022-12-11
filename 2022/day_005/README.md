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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.2 ± 2.9 | 12.4 | 35.8 | 15.34 ± 6.98 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 21.1 ± 5.0 | 12.3 | 30.8 | 13.42 ± 6.68 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 19.8 ± 5.3 | 12.3 | 26.6 | 12.60 ± 6.48 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 21.4 ± 5.3 | 12.3 | 30.5 | 13.59 ± 6.85 |
| `aspidites-solver/aoc -i input-pting -d 5` | 20.8 ± 5.2 | 12.2 | 33.3 | 13.21 ± 6.66 |
| `kcen/2022/05/solve input-aspidites` | 120.7 ± 11.5 | 106.6 | 154.2 | 76.67 ± 34.44 |
| `kcen/2022/05/solve input-kcen` | 125.4 ± 13.2 | 113.0 | 162.7 | 79.62 ± 35.94 |
| `kcen/2022/05/solve input-lanjian` | 124.0 ± 9.8 | 105.6 | 151.0 | 78.74 ± 35.12 |
| `kcen/2022/05/solve input-mattcl` | 115.8 ± 11.3 | 96.0 | 136.4 | 73.52 ± 33.06 |
| `kcen/2022/05/solve input-pting` | 124.2 ± 9.7 | 105.7 | 140.4 | 78.90 ± 35.18 |
| `lanjian/day_05 input-aspidites` | 2.0 ± 1.0 | 0.7 | 10.5 | 1.26 ± 0.83 |
| `lanjian/day_05 input-kcen` | 1.6 ± 0.7 | 0.4 | 4.4 | 1.00 |
| `lanjian/day_05 input-lanjian` | 2.1 ± 1.0 | 0.6 | 23.1 | 1.32 ± 0.88 |
| `lanjian/day_05 input-mattcl` | 1.7 ± 0.7 | 0.4 | 8.3 | 1.08 ± 0.66 |
| `lanjian/day_05 input-pting` | 1.7 ± 0.8 | 0.5 | 6.8 | 1.09 ± 0.72 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.6 ± 1.2 | 0.7 | 10.4 | 1.65 ± 1.04 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.1 ± 0.8 | 0.7 | 9.1 | 1.32 ± 0.77 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.3 ± 1.6 | 0.7 | 27.6 | 1.47 ± 1.20 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.1 ± 0.8 | 0.5 | 6.0 | 1.31 ± 0.76 |
| `mattcl-solver/aoc run 5 input-pting` | 2.0 ± 1.2 | 0.5 | 28.1 | 1.25 ± 0.92 |
| `python pting/day05.py input-aspidites` | 45.9 ± 6.5 | 38.2 | 77.9 | 29.13 ± 13.44 |
| `python pting/day05.py input-kcen` | 43.8 ± 4.8 | 36.8 | 55.8 | 27.83 ± 12.60 |
| `python pting/day05.py input-lanjian` | 46.9 ± 5.6 | 36.7 | 63.1 | 29.78 ± 13.54 |
| `python pting/day05.py input-mattcl` | 44.2 ± 5.5 | 34.6 | 63.7 | 28.04 ± 12.80 |
| `python pting/day05.py input-pting` | 49.2 ± 11.2 | 37.0 | 100.1 | 31.22 ± 15.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
