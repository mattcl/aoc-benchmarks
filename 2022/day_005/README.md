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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.9 ± 2.3 | 22.6 | 37.4 | 13.14 ± 7.08 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 24.8 ± 2.4 | 22.7 | 45.0 | 13.10 ± 7.08 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.2 ± 5.2 | 12.1 | 46.4 | 13.30 ± 7.58 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 25.2 ± 3.2 | 20.6 | 41.2 | 13.33 ± 7.28 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.2 ± 2.6 | 23.0 | 40.3 | 13.33 ± 7.22 |
| `kcen/2022/05/solve input-aspidites` | 160.3 ± 14.4 | 138.0 | 192.3 | 84.73 ± 45.67 |
| `kcen/2022/05/solve input-kcen` | 152.9 ± 14.1 | 132.4 | 184.7 | 80.83 ± 43.60 |
| `kcen/2022/05/solve input-lanjian` | 149.3 ± 15.8 | 122.1 | 176.7 | 78.93 ± 42.77 |
| `kcen/2022/05/solve input-mattcl` | 159.1 ± 14.4 | 129.2 | 188.9 | 84.07 ± 45.32 |
| `kcen/2022/05/solve input-pting` | 157.8 ± 17.8 | 138.4 | 207.6 | 83.43 ± 45.32 |
| `lanjian/day_05 input-aspidites` | 2.1 ± 1.1 | 0.4 | 8.9 | 1.12 ± 0.85 |
| `lanjian/day_05 input-kcen` | 1.9 ± 1.3 | 0.2 | 15.9 | 1.01 ± 0.87 |
| `lanjian/day_05 input-lanjian` | 1.9 ± 1.0 | 0.3 | 7.0 | 1.00 |
| `lanjian/day_05 input-mattcl` | 2.0 ± 1.2 | 0.4 | 7.8 | 1.08 ± 0.84 |
| `lanjian/day_05 input-pting` | 3.2 ± 3.5 | 0.4 | 28.7 | 1.68 ± 2.03 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.0 ± 1.0 | 0.4 | 6.0 | 1.05 ± 0.78 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.7 ± 1.7 | 0.7 | 22.5 | 1.45 ± 1.20 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.1 ± 1.3 | 0.3 | 9.9 | 1.09 ± 0.91 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.4 ± 1.2 | 0.4 | 8.0 | 1.29 ± 0.94 |
| `mattcl-solver/aoc run 5 input-pting` | 2.2 ± 1.3 | 0.6 | 10.2 | 1.18 ± 0.93 |
| `python pting/day05.py input-aspidites` | 53.0 ± 5.2 | 44.0 | 66.8 | 28.00 ± 15.13 |
| `python pting/day05.py input-kcen` | 52.9 ± 5.6 | 42.2 | 65.6 | 27.98 ± 15.16 |
| `python pting/day05.py input-lanjian` | 50.5 ± 5.3 | 42.2 | 63.5 | 26.72 ± 14.47 |
| `python pting/day05.py input-mattcl` | 54.8 ± 6.8 | 43.6 | 76.0 | 28.97 ± 15.80 |
| `python pting/day05.py input-pting` | 53.2 ± 8.7 | 43.4 | 88.9 | 28.11 ± 15.63 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
