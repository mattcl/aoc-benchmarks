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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 30.0 ± 8.2 | 22.9 | 53.0 | 13.77 ± 7.98 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.0 ± 4.5 | 22.7 | 45.8 | 11.97 ± 6.45 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 30.0 ± 7.9 | 23.1 | 61.6 | 13.78 ± 7.92 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.4 ± 4.5 | 22.8 | 48.6 | 12.14 ± 6.54 |
| `aspidites-solver/aoc -i input-pting -d 5` | 27.6 ± 6.8 | 23.1 | 54.4 | 12.67 ± 7.18 |
| `kcen/2022/05/solve input-aspidites` | 192.9 ± 45.3 | 153.6 | 295.2 | 88.63 ± 49.79 |
| `kcen/2022/05/solve input-kcen` | 146.3 ± 16.0 | 120.8 | 189.9 | 67.22 ± 35.07 |
| `kcen/2022/05/solve input-lanjian` | 184.6 ± 26.4 | 141.6 | 233.2 | 84.80 ± 44.94 |
| `kcen/2022/05/solve input-mattcl` | 176.2 ± 13.5 | 157.1 | 217.2 | 80.95 ± 41.77 |
| `kcen/2022/05/solve input-pting` | 199.3 ± 34.1 | 158.7 | 301.5 | 91.57 ± 49.28 |
| `lanjian/day_05 input-aspidites` | 2.6 ± 1.9 | 0.7 | 24.6 | 1.19 ± 1.06 |
| `lanjian/day_05 input-kcen` | 2.2 ± 1.1 | 0.5 | 10.5 | 1.00 |
| `lanjian/day_05 input-lanjian` | 3.1 ± 2.2 | 0.6 | 17.3 | 1.42 ± 1.26 |
| `lanjian/day_05 input-mattcl` | 2.8 ± 1.7 | 0.5 | 17.4 | 1.29 ± 1.01 |
| `lanjian/day_05 input-pting` | 3.0 ± 1.7 | 0.5 | 15.5 | 1.39 ± 1.05 |
| `mattcl-solver/aoc run 5 input-aspidites` | 5.7 ± 5.8 | 0.9 | 49.9 | 2.63 ± 2.98 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.3 ± 1.3 | 0.5 | 11.9 | 1.06 ± 0.80 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.2 ± 0.9 | 0.3 | 6.6 | 1.02 ± 0.67 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.9 ± 1.4 | 0.9 | 11.5 | 1.31 ± 0.94 |
| `mattcl-solver/aoc run 5 input-pting` | 2.8 ± 1.5 | 0.8 | 12.6 | 1.30 ± 0.96 |
| `python pting/day05.py input-aspidites` | 60.1 ± 8.3 | 47.5 | 78.8 | 27.62 ± 14.61 |
| `python pting/day05.py input-kcen` | 64.9 ± 24.5 | 47.3 | 157.2 | 29.81 ± 18.92 |
| `python pting/day05.py input-lanjian` | 65.7 ± 14.1 | 49.3 | 144.2 | 30.18 ± 16.70 |
| `python pting/day05.py input-mattcl` | 63.6 ± 20.1 | 45.8 | 138.9 | 29.20 ± 17.53 |
| `python pting/day05.py input-pting` | 67.9 ± 11.7 | 49.3 | 117.9 | 31.19 ± 16.80 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
