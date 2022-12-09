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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 24.5 ± 1.3 | 23.0 | 35.3 | 14.73 ± 6.51 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 24.3 ± 1.4 | 22.4 | 33.3 | 14.60 ± 6.46 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 25.1 ± 1.9 | 23.1 | 36.8 | 15.07 ± 6.71 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 24.3 ± 2.3 | 13.0 | 39.4 | 14.63 ± 6.56 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.6 ± 4.8 | 12.4 | 47.6 | 15.39 ± 7.35 |
| `kcen/2022/05/solve input-aspidites` | 148.0 ± 13.4 | 129.1 | 178.0 | 88.96 ± 39.84 |
| `kcen/2022/05/solve input-kcen` | 155.4 ± 15.7 | 123.8 | 192.1 | 93.41 ± 42.04 |
| `kcen/2022/05/solve input-lanjian` | 143.0 ± 18.1 | 117.8 | 185.3 | 85.97 ± 39.24 |
| `kcen/2022/05/solve input-mattcl` | 152.5 ± 12.1 | 124.3 | 171.5 | 91.69 ± 40.87 |
| `kcen/2022/05/solve input-pting` | 143.6 ± 15.6 | 119.0 | 181.8 | 86.36 ± 39.02 |
| `lanjian/day_05 input-aspidites` | 1.7 ± 0.7 | 0.5 | 5.2 | 1.00 |
| `lanjian/day_05 input-kcen` | 2.2 ± 1.1 | 0.4 | 9.6 | 1.30 ± 0.86 |
| `lanjian/day_05 input-lanjian` | 1.9 ± 0.9 | 0.5 | 14.9 | 1.16 ± 0.76 |
| `lanjian/day_05 input-mattcl` | 2.3 ± 1.1 | 0.4 | 15.6 | 1.36 ± 0.90 |
| `lanjian/day_05 input-pting` | 3.4 ± 3.7 | 0.3 | 34.4 | 2.04 ± 2.40 |
| `mattcl-solver/aoc run 5 input-aspidites` | 1.9 ± 2.4 | 0.5 | 56.1 | 1.12 ± 1.50 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.1 ± 1.1 | 0.5 | 10.1 | 1.28 ± 0.88 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.3 ± 0.9 | 0.7 | 9.0 | 1.40 ± 0.82 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.2 ± 0.9 | 0.7 | 5.9 | 1.34 ± 0.78 |
| `mattcl-solver/aoc run 5 input-pting` | 3.4 ± 2.5 | 0.7 | 19.3 | 2.03 ± 1.72 |
| `python pting/day05.py input-aspidites` | 50.8 ± 5.6 | 43.4 | 64.3 | 30.52 ± 13.81 |
| `python pting/day05.py input-kcen` | 48.1 ± 6.0 | 38.9 | 63.3 | 28.91 ± 13.18 |
| `python pting/day05.py input-lanjian` | 52.1 ± 5.1 | 43.7 | 62.6 | 31.32 ± 14.08 |
| `python pting/day05.py input-mattcl` | 51.8 ± 6.2 | 42.8 | 67.5 | 31.13 ± 14.14 |
| `python pting/day05.py input-pting` | 50.7 ± 5.3 | 42.0 | 63.3 | 30.48 ± 13.74 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
