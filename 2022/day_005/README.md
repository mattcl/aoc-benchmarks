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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.0 ± 3.3 | 23.9 | 50.7 | 9.93 ± 4.40 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 28.0 ± 6.0 | 23.7 | 53.7 | 10.70 ± 5.09 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 27.1 ± 5.3 | 23.4 | 48.8 | 10.33 ± 4.83 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 29.1 ± 5.7 | 24.2 | 46.5 | 11.08 ± 5.18 |
| `aspidites-solver/aoc -i input-pting -d 5` | 31.6 ± 14.5 | 24.1 | 136.3 | 12.05 ± 7.54 |
| `kcen/2022/05/solve input-aspidites` | 178.2 ± 26.6 | 144.5 | 236.8 | 67.99 ± 30.59 |
| `kcen/2022/05/solve input-kcen` | 180.8 ± 25.7 | 149.0 | 236.4 | 68.98 ± 30.88 |
| `kcen/2022/05/solve input-lanjian` | 187.1 ± 29.1 | 149.1 | 247.7 | 71.38 ± 32.26 |
| `kcen/2022/05/solve input-mattcl` | 188.1 ± 18.6 | 151.3 | 215.5 | 71.77 ± 31.27 |
| `kcen/2022/05/solve input-pting` | 166.1 ± 26.9 | 138.1 | 251.6 | 63.38 ± 28.78 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 1.1 | 1.0 | 7.8 | 1.00 |
| `lanjian/day_05 input-kcen` | 2.7 ± 1.6 | 0.7 | 14.9 | 1.04 ± 0.75 |
| `lanjian/day_05 input-lanjian` | 3.3 ± 1.6 | 0.8 | 12.4 | 1.26 ± 0.82 |
| `lanjian/day_05 input-mattcl` | 4.7 ± 5.0 | 0.7 | 40.5 | 1.78 ± 2.06 |
| `lanjian/day_05 input-pting` | 2.7 ± 1.5 | 0.5 | 15.9 | 1.01 ± 0.73 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.1 ± 1.4 | 1.1 | 14.5 | 1.18 ± 0.72 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.1 ± 3.8 | 0.9 | 80.3 | 1.17 ± 1.52 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.3 ± 1.6 | 0.6 | 15.0 | 1.28 ± 0.81 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.9 ± 1.3 | 0.6 | 8.4 | 1.11 ± 0.69 |
| `mattcl-solver/aoc run 5 input-pting` | 3.3 ± 1.5 | 0.7 | 15.8 | 1.26 ± 0.79 |
| `python pting/day05.py input-aspidites` | 60.2 ± 23.4 | 43.9 | 172.6 | 22.96 ± 13.23 |
| `python pting/day05.py input-kcen` | 62.5 ± 10.0 | 46.1 | 91.9 | 23.84 ± 10.82 |
| `python pting/day05.py input-lanjian` | 56.9 ± 9.1 | 45.5 | 83.8 | 21.72 ± 9.85 |
| `python pting/day05.py input-mattcl` | 74.2 ± 22.6 | 51.8 | 140.7 | 28.31 ± 14.79 |
| `python pting/day05.py input-pting` | 63.0 ± 9.5 | 48.0 | 83.7 | 24.02 ± 10.82 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
