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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 34.4 ± 19.8 | 23.7 | 151.0 | 10.31 ± 8.09 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 29.2 ± 7.9 | 23.3 | 64.0 | 8.75 ± 5.23 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 29.6 ± 8.4 | 23.3 | 58.2 | 8.88 ± 5.35 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 33.4 ± 11.0 | 24.1 | 69.9 | 10.02 ± 6.28 |
| `aspidites-solver/aoc -i input-pting -d 5` | 28.7 ± 7.7 | 23.4 | 52.8 | 8.61 ± 5.13 |
| `kcen/2022/05/solve input-aspidites` | 174.9 ± 37.4 | 134.4 | 265.6 | 52.40 ± 30.10 |
| `kcen/2022/05/solve input-kcen` | 177.9 ± 49.4 | 136.7 | 304.1 | 53.28 ± 32.03 |
| `kcen/2022/05/solve input-lanjian` | 169.6 ± 19.0 | 147.9 | 214.0 | 50.81 ± 27.69 |
| `kcen/2022/05/solve input-mattcl` | 162.1 ± 29.8 | 128.4 | 247.8 | 48.57 ± 27.40 |
| `kcen/2022/05/solve input-pting` | 169.0 ± 22.1 | 145.7 | 219.5 | 50.62 ± 27.79 |
| `lanjian/day_05 input-aspidites` | 3.4 ± 2.1 | 0.8 | 20.6 | 1.01 ± 0.83 |
| `lanjian/day_05 input-kcen` | 4.2 ± 2.8 | 1.1 | 21.9 | 1.25 ± 1.07 |
| `lanjian/day_05 input-lanjian` | 3.5 ± 1.9 | 1.1 | 17.1 | 1.04 ± 0.79 |
| `lanjian/day_05 input-mattcl` | 3.7 ± 3.2 | 1.3 | 53.1 | 1.11 ± 1.14 |
| `lanjian/day_05 input-pting` | 6.0 ± 5.7 | 1.7 | 62.5 | 1.79 ± 1.95 |
| `mattcl-solver/aoc run 5 input-aspidites` | 3.3 ± 1.8 | 1.0 | 15.0 | 1.00 |
| `mattcl-solver/aoc run 5 input-kcen` | 4.0 ± 1.8 | 0.8 | 16.7 | 1.19 ± 0.83 |
| `mattcl-solver/aoc run 5 input-lanjian` | 3.9 ± 2.2 | 1.2 | 29.2 | 1.18 ± 0.91 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.9 ± 1.9 | 1.1 | 12.0 | 1.18 ± 0.84 |
| `mattcl-solver/aoc run 5 input-pting` | 12.7 ± 9.3 | 3.4 | 40.6 | 3.79 ± 3.45 |
| `python pting/day05.py input-aspidites` | 70.5 ± 36.3 | 46.7 | 185.2 | 21.11 ± 15.64 |
| `python pting/day05.py input-kcen` | 62.9 ± 27.8 | 41.0 | 162.3 | 18.86 ± 13.05 |
| `python pting/day05.py input-lanjian` | 65.4 ± 33.0 | 41.5 | 186.8 | 19.60 ± 14.38 |
| `python pting/day05.py input-mattcl` | 64.3 ± 27.6 | 42.8 | 198.6 | 19.27 ± 13.19 |
| `python pting/day05.py input-pting` | 57.2 ± 16.2 | 41.5 | 121.6 | 17.14 ± 10.35 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
