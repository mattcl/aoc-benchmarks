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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 25.7 ± 2.1 | 23.1 | 36.8 | 11.05 ± 5.01 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.4 ± 4.5 | 23.0 | 52.8 | 11.34 ± 5.41 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.8 ± 2.3 | 23.7 | 40.7 | 11.09 ± 5.04 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.3 ± 2.2 | 23.2 | 37.3 | 10.88 ± 4.94 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.2 ± 2.1 | 23.2 | 37.7 | 10.83 ± 4.91 |
| `kcen/2022/05/solve input-aspidites` | 158.5 ± 17.0 | 132.0 | 194.5 | 68.14 ± 31.24 |
| `kcen/2022/05/solve input-kcen` | 162.9 ± 21.9 | 135.1 | 227.4 | 70.06 ± 32.62 |
| `kcen/2022/05/solve input-lanjian` | 244.1 ± 87.0 | 136.9 | 400.2 | 104.94 ± 59.90 |
| `kcen/2022/05/solve input-mattcl` | 157.6 ± 15.5 | 136.7 | 185.7 | 67.77 ± 30.93 |
| `kcen/2022/05/solve input-pting` | 174.5 ± 21.6 | 138.8 | 213.5 | 75.03 ± 34.71 |
| `lanjian/day_05 input-aspidites` | 2.8 ± 1.0 | 0.9 | 12.7 | 1.19 ± 0.69 |
| `lanjian/day_05 input-kcen` | 8.0 ± 6.5 | 1.4 | 48.4 | 3.45 ± 3.19 |
| `lanjian/day_05 input-lanjian` | 2.7 ± 1.1 | 1.1 | 10.8 | 1.15 ± 0.70 |
| `lanjian/day_05 input-mattcl` | 2.3 ± 1.0 | 0.8 | 13.3 | 1.00 |
| `lanjian/day_05 input-pting` | 2.4 ± 1.0 | 0.8 | 11.1 | 1.04 ± 0.62 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.6 ± 1.1 | 1.0 | 12.8 | 1.14 ± 0.70 |
| `mattcl-solver/aoc run 5 input-kcen` | 5.0 ± 5.2 | 1.1 | 38.0 | 2.15 ± 2.43 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.0 ± 1.0 | 1.2 | 8.8 | 1.29 ± 0.71 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.8 ± 1.3 | 0.9 | 14.5 | 1.22 ± 0.79 |
| `mattcl-solver/aoc run 5 input-pting` | 3.2 ± 0.9 | 1.5 | 8.1 | 1.37 ± 0.73 |
| `python pting/day05.py input-aspidites` | 55.1 ± 8.2 | 42.2 | 82.2 | 23.70 ± 11.14 |
| `python pting/day05.py input-kcen` | 60.6 ± 7.3 | 47.5 | 77.5 | 26.07 ± 12.04 |
| `python pting/day05.py input-lanjian` | 54.2 ± 6.0 | 43.9 | 65.1 | 23.31 ± 10.71 |
| `python pting/day05.py input-mattcl` | 64.0 ± 9.3 | 42.9 | 81.7 | 27.53 ± 12.90 |
| `python pting/day05.py input-pting` | 57.1 ± 7.1 | 45.9 | 72.5 | 24.54 ± 11.36 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
