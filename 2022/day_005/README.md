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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 28.4 ± 5.0 | 24.2 | 49.1 | 9.75 ± 5.18 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 28.2 ± 4.5 | 24.0 | 45.8 | 9.67 ± 5.09 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 31.7 ± 7.7 | 23.4 | 66.2 | 10.87 ± 6.05 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.7 ± 2.9 | 23.8 | 38.1 | 9.15 ± 4.69 |
| `aspidites-solver/aoc -i input-pting -d 5` | 27.8 ± 4.6 | 24.1 | 49.4 | 9.56 ± 5.05 |
| `kcen/2022/05/solve input-aspidites` | 169.3 ± 20.7 | 140.4 | 210.6 | 58.10 ± 29.98 |
| `kcen/2022/05/solve input-kcen` | 176.5 ± 19.6 | 154.4 | 211.2 | 60.57 ± 31.10 |
| `kcen/2022/05/solve input-lanjian` | 192.0 ± 26.4 | 153.6 | 256.3 | 65.91 ± 34.26 |
| `kcen/2022/05/solve input-mattcl` | 170.4 ± 24.8 | 143.0 | 240.4 | 58.49 ± 30.53 |
| `kcen/2022/05/solve input-pting` | 197.1 ± 18.6 | 166.6 | 233.0 | 67.64 ± 34.50 |
| `lanjian/day_05 input-aspidites` | 3.5 ± 1.5 | 0.8 | 14.0 | 1.19 ± 0.78 |
| `lanjian/day_05 input-kcen` | 2.9 ± 1.5 | 0.7 | 19.8 | 1.00 |
| `lanjian/day_05 input-lanjian` | 3.3 ± 1.9 | 0.8 | 29.8 | 1.13 ± 0.87 |
| `lanjian/day_05 input-mattcl` | 2.9 ± 1.5 | 0.6 | 12.7 | 1.01 ± 0.73 |
| `lanjian/day_05 input-pting` | 3.2 ± 1.5 | 0.8 | 17.5 | 1.09 ± 0.75 |
| `mattcl-solver/aoc run 5 input-aspidites` | 5.8 ± 5.7 | 1.1 | 50.8 | 1.99 ± 2.20 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.5 ± 1.3 | 1.3 | 17.4 | 1.19 ± 0.75 |
| `mattcl-solver/aoc run 5 input-lanjian` | 4.6 ± 2.2 | 1.6 | 23.0 | 1.57 ± 1.08 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.9 ± 1.9 | 1.1 | 14.4 | 1.34 ± 0.94 |
| `mattcl-solver/aoc run 5 input-pting` | 3.6 ± 2.4 | 0.9 | 21.8 | 1.25 ± 1.05 |
| `python pting/day05.py input-aspidites` | 62.4 ± 8.1 | 50.2 | 88.4 | 21.40 ± 11.08 |
| `python pting/day05.py input-kcen` | 72.2 ± 10.3 | 53.3 | 97.2 | 24.77 ± 12.91 |
| `python pting/day05.py input-lanjian` | 68.8 ± 9.2 | 55.3 | 95.6 | 23.60 ± 12.25 |
| `python pting/day05.py input-mattcl` | 64.6 ± 11.6 | 50.2 | 95.9 | 22.19 ± 11.81 |
| `python pting/day05.py input-pting` | 63.5 ± 8.4 | 48.9 | 94.4 | 21.79 ± 11.30 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
