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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 22.3 ± 4.2 | 12.6 | 33.5 | 21.44 ± 12.27 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 21.7 ± 4.9 | 12.2 | 34.1 | 20.89 ± 12.21 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 18.7 ± 5.7 | 11.9 | 30.2 | 18.01 ± 11.18 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 17.9 ± 5.3 | 12.1 | 24.8 | 17.24 ± 10.61 |
| `aspidites-solver/aoc -i input-pting -d 5` | 22.8 ± 3.6 | 12.6 | 27.4 | 21.93 ± 12.35 |
| `kcen/2022/05/solve input-aspidites` | 115.4 ± 10.7 | 102.2 | 140.8 | 111.04 ± 60.83 |
| `kcen/2022/05/solve input-kcen` | 113.3 ± 15.0 | 96.1 | 136.1 | 109.06 ± 60.62 |
| `kcen/2022/05/solve input-lanjian` | 132.2 ± 18.0 | 102.2 | 173.5 | 127.19 ± 70.82 |
| `kcen/2022/05/solve input-mattcl` | 116.9 ± 9.6 | 102.9 | 142.8 | 112.45 ± 61.42 |
| `kcen/2022/05/solve input-pting` | 113.9 ± 6.5 | 103.5 | 127.1 | 109.60 ± 59.50 |
| `lanjian/day_05 input-aspidites` | 1.8 ± 0.6 | 0.4 | 4.6 | 1.70 ± 1.09 |
| `lanjian/day_05 input-kcen` | 1.6 ± 0.8 | 0.3 | 7.6 | 1.56 ± 1.17 |
| `lanjian/day_05 input-lanjian` | 1.6 ± 0.9 | 0.3 | 10.1 | 1.56 ± 1.20 |
| `lanjian/day_05 input-mattcl` | 1.4 ± 0.7 | 0.4 | 7.5 | 1.33 ± 0.96 |
| `lanjian/day_05 input-pting` | 1.0 ± 0.6 | 0.3 | 4.4 | 1.00 |
| `mattcl-solver/aoc run 5 input-aspidites` | 1.8 ± 0.6 | 0.6 | 5.5 | 1.77 ± 1.12 |
| `mattcl-solver/aoc run 5 input-kcen` | 1.9 ± 0.7 | 0.5 | 9.8 | 1.81 ± 1.20 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.0 ± 1.2 | 0.5 | 22.8 | 1.88 ± 1.52 |
| `mattcl-solver/aoc run 5 input-mattcl` | 1.7 ± 2.7 | 0.4 | 74.3 | 1.64 ± 2.79 |
| `mattcl-solver/aoc run 5 input-pting` | 1.4 ± 0.7 | 0.5 | 6.9 | 1.37 ± 0.97 |
| `python pting/day05.py input-aspidites` | 41.4 ± 3.5 | 35.7 | 50.9 | 39.85 ± 21.78 |
| `python pting/day05.py input-kcen` | 42.0 ± 6.8 | 31.9 | 67.8 | 40.40 ± 22.76 |
| `python pting/day05.py input-lanjian` | 40.0 ± 4.8 | 34.9 | 64.6 | 38.52 ± 21.30 |
| `python pting/day05.py input-mattcl` | 42.3 ± 4.0 | 35.4 | 53.9 | 40.72 ± 22.32 |
| `python pting/day05.py input-pting` | 40.9 ± 4.5 | 33.5 | 52.6 | 39.36 ± 21.69 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
