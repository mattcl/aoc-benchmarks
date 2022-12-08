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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 38.3 ± 17.8 | 23.8 | 104.8 | 19.94 ± 18.21 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.1 ± 5.1 | 23.5 | 50.6 | 14.13 ± 11.41 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 30.1 ± 7.9 | 23.6 | 52.2 | 15.65 ± 12.97 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 29.2 ± 7.3 | 23.9 | 61.0 | 15.21 ± 12.55 |
| `aspidites-solver/aoc -i input-pting -d 5` | 26.5 ± 3.9 | 23.2 | 44.7 | 13.81 ± 11.05 |
| `kcen/2022/05/solve input-aspidites` | 187.5 ± 37.0 | 142.3 | 276.0 | 97.58 ± 79.10 |
| `kcen/2022/05/solve input-kcen` | 170.4 ± 12.5 | 147.7 | 197.0 | 88.72 ± 70.06 |
| `kcen/2022/05/solve input-lanjian` | 204.2 ± 49.1 | 141.8 | 286.7 | 106.32 ± 87.41 |
| `kcen/2022/05/solve input-mattcl` | 210.5 ± 50.6 | 159.7 | 340.5 | 109.60 ± 90.10 |
| `kcen/2022/05/solve input-pting` | 165.0 ± 39.4 | 131.8 | 300.1 | 85.91 ± 70.59 |
| `lanjian/day_05 input-aspidites` | 1.9 ± 1.5 | 0.1 | 13.0 | 1.00 |
| `lanjian/day_05 input-kcen` | 3.1 ± 1.9 | 0.3 | 19.4 | 1.63 ± 1.61 |
| `lanjian/day_05 input-lanjian` | 3.2 ± 1.5 | 0.7 | 14.7 | 1.64 ± 1.50 |
| `lanjian/day_05 input-mattcl` | 2.6 ± 1.5 | 0.4 | 12.7 | 1.38 ± 1.34 |
| `lanjian/day_05 input-pting` | 2.5 ± 1.5 | 0.4 | 20.4 | 1.28 ± 1.26 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.7 ± 1.3 | 0.5 | 12.2 | 1.38 ± 1.28 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.4 ± 1.5 | 0.3 | 21.5 | 1.23 ± 1.26 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.3 ± 1.8 | 1.1 | 13.3 | 1.73 ± 1.66 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.4 ± 3.9 | 0.4 | 70.6 | 1.79 ± 2.47 |
| `mattcl-solver/aoc run 5 input-pting` | 2.8 ± 1.4 | 0.8 | 11.0 | 1.46 ± 1.36 |
| `python pting/day05.py input-aspidites` | 52.2 ± 8.7 | 40.7 | 96.2 | 27.17 ± 21.83 |
| `python pting/day05.py input-kcen` | 63.5 ± 11.2 | 48.5 | 103.9 | 33.05 ± 26.63 |
| `python pting/day05.py input-lanjian` | 62.2 ± 12.3 | 43.9 | 99.9 | 32.36 ± 26.23 |
| `python pting/day05.py input-mattcl` | 72.3 ± 26.3 | 51.4 | 157.3 | 37.62 ± 32.60 |
| `python pting/day05.py input-pting` | 64.8 ± 10.3 | 50.3 | 93.7 | 33.75 ± 27.07 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
