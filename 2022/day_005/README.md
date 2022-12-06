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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.5 ± 5.0 | 22.7 | 50.1 | 16.52 ± 11.70 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 28.0 ± 5.8 | 22.7 | 47.9 | 17.43 ± 12.45 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 28.3 ± 7.4 | 22.8 | 59.7 | 17.66 ± 12.92 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 26.0 ± 3.9 | 22.9 | 37.4 | 16.20 ± 11.33 |
| `aspidites-solver/aoc -i input-pting -d 5` | 27.8 ± 6.3 | 22.6 | 55.5 | 17.34 ± 12.47 |
| `kcen/2022/05/solve input-aspidites` | 211.9 ± 21.0 | 178.7 | 261.3 | 132.06 ± 91.12 |
| `kcen/2022/05/solve input-kcen` | 206.8 ± 20.3 | 185.2 | 245.2 | 128.88 ± 88.91 |
| `kcen/2022/05/solve input-lanjian` | 213.6 ± 39.6 | 157.3 | 330.3 | 133.10 ± 94.18 |
| `kcen/2022/05/solve input-mattcl` | 192.5 ± 15.8 | 172.4 | 223.6 | 119.98 ± 82.51 |
| `kcen/2022/05/solve input-pting` | 191.6 ± 21.3 | 156.9 | 223.3 | 119.40 ± 82.61 |
| `lanjian/day_05 input-aspidites` | 1.9 ± 1.1 | 0.0 | 10.4 | 1.20 ± 1.09 |
| `lanjian/day_05 input-kcen` | 2.3 ± 1.4 | 0.0 | 19.6 | 1.40 ± 1.28 |
| `lanjian/day_05 input-lanjian` | 2.5 ± 1.9 | 0.0 | 15.5 | 1.55 ± 1.60 |
| `lanjian/day_05 input-mattcl` | 1.6 ± 1.1 | 0.0 | 8.7 | 1.00 |
| `lanjian/day_05 input-pting` | 2.9 ± 2.1 | 0.0 | 14.1 | 1.80 ± 1.79 |
| `mattcl-solver/aoc run 5 input-aspidites` | 1.8 ± 1.3 | 0.0 | 13.3 | 1.15 ± 1.13 |
| `mattcl-solver/aoc run 5 input-kcen` | 1.8 ± 1.2 | 0.0 | 15.9 | 1.12 ± 1.09 |
| `mattcl-solver/aoc run 5 input-lanjian` | 4.1 ± 6.0 | 0.4 | 67.9 | 2.56 ± 4.12 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.7 ± 4.3 | 0.1 | 38.6 | 2.32 ± 3.10 |
| `mattcl-solver/aoc run 5 input-pting` | 2.9 ± 1.6 | 0.3 | 17.2 | 1.81 ± 1.58 |
| `python pting/day05.py input-aspidites` | 67.7 ± 9.3 | 54.2 | 96.8 | 42.18 ± 29.37 |
| `python pting/day05.py input-kcen` | 68.1 ± 9.9 | 53.6 | 96.1 | 42.47 ± 29.65 |
| `python pting/day05.py input-lanjian` | 75.3 ± 12.0 | 57.9 | 119.8 | 46.92 ± 32.89 |
| `python pting/day05.py input-mattcl` | 61.9 ± 7.9 | 50.3 | 97.0 | 38.55 ± 26.78 |
| `python pting/day05.py input-pting` | 68.2 ± 12.8 | 51.7 | 110.9 | 42.52 ± 30.10 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
