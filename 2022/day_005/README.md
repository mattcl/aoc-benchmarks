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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.0 ± 1.7 | 23.1 | 35.0 | 9.94 ± 4.13 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 25.1 ± 1.6 | 23.0 | 34.7 | 9.97 ± 4.13 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 41.2 ± 21.9 | 23.3 | 133.1 | 16.39 ± 10.98 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.3 ± 2.5 | 23.0 | 36.3 | 10.05 ± 4.23 |
| `aspidites-solver/aoc -i input-pting -d 5` | 24.7 ± 1.4 | 22.9 | 33.1 | 9.81 ± 4.06 |
| `kcen/2022/05/solve input-aspidites` | 158.7 ± 17.8 | 129.2 | 195.0 | 63.12 ± 26.81 |
| `kcen/2022/05/solve input-kcen` | 165.5 ± 14.6 | 142.4 | 191.9 | 65.82 ± 27.58 |
| `kcen/2022/05/solve input-lanjian` | 158.3 ± 14.4 | 140.5 | 194.1 | 62.97 ± 26.43 |
| `kcen/2022/05/solve input-mattcl` | 151.1 ± 16.4 | 126.0 | 182.7 | 60.11 ± 25.47 |
| `kcen/2022/05/solve input-pting` | 180.5 ± 20.1 | 158.3 | 218.5 | 71.78 ± 30.47 |
| `lanjian/day_05 input-aspidites` | 3.4 ± 1.5 | 1.1 | 21.7 | 1.35 ± 0.80 |
| `lanjian/day_05 input-kcen` | 6.1 ± 7.8 | 0.7 | 87.1 | 2.44 ± 3.25 |
| `lanjian/day_05 input-lanjian` | 2.5 ± 1.0 | 0.9 | 9.7 | 1.00 |
| `lanjian/day_05 input-mattcl` | 2.6 ± 1.2 | 0.8 | 12.4 | 1.02 ± 0.63 |
| `lanjian/day_05 input-pting` | 2.6 ± 1.0 | 1.1 | 12.5 | 1.03 ± 0.58 |
| `mattcl-solver/aoc run 5 input-aspidites` | 4.1 ± 2.7 | 0.9 | 18.7 | 1.63 ± 1.27 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.6 ± 1.0 | 1.1 | 16.3 | 1.03 ± 0.59 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.5 ± 1.1 | 0.8 | 10.8 | 1.01 ± 0.60 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.7 ± 0.8 | 1.2 | 7.3 | 1.06 ± 0.53 |
| `mattcl-solver/aoc run 5 input-pting` | 3.0 ± 1.0 | 1.4 | 10.7 | 1.20 ± 0.64 |
| `python pting/day05.py input-aspidites` | 57.7 ± 7.3 | 45.3 | 72.6 | 22.94 ± 9.84 |
| `python pting/day05.py input-kcen` | 70.2 ± 39.5 | 44.7 | 180.7 | 27.94 ± 19.43 |
| `python pting/day05.py input-lanjian` | 53.6 ± 7.0 | 43.0 | 77.1 | 21.33 ± 9.17 |
| `python pting/day05.py input-mattcl` | 55.5 ± 7.6 | 44.6 | 71.6 | 22.06 ± 9.53 |
| `python pting/day05.py input-pting` | 51.7 ± 6.4 | 42.4 | 77.3 | 20.55 ± 8.80 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
