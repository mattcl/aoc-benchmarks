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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 30.2 ± 9.5 | 22.8 | 63.1 | 13.74 ± 12.88 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 27.3 ± 6.4 | 22.6 | 52.1 | 12.44 ± 11.36 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 28.6 ± 7.7 | 22.5 | 61.4 | 13.00 ± 12.01 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 28.1 ± 6.5 | 23.4 | 48.5 | 12.80 ± 11.68 |
| `aspidites-solver/aoc -i input-pting -d 5` | 31.9 ± 10.4 | 22.9 | 57.9 | 14.49 ± 13.64 |
| `kcen/2022/05/solve input-aspidites` | 189.0 ± 55.9 | 130.0 | 323.0 | 85.98 ± 80.06 |
| `kcen/2022/05/solve input-kcen` | 214.7 ± 91.9 | 131.5 | 436.3 | 97.65 ± 95.82 |
| `kcen/2022/05/solve input-lanjian` | 148.3 ± 19.0 | 123.2 | 194.7 | 67.47 ± 60.19 |
| `kcen/2022/05/solve input-mattcl` | 250.8 ± 77.9 | 145.2 | 399.0 | 114.08 ± 106.77 |
| `kcen/2022/05/solve input-pting` | 174.6 ± 39.4 | 142.0 | 282.3 | 79.41 ± 72.37 |
| `lanjian/day_05 input-aspidites` | 2.4 ± 1.8 | 0.0 | 9.2 | 1.10 ± 1.28 |
| `lanjian/day_05 input-kcen` | 2.2 ± 1.9 | 0.0 | 17.7 | 1.00 |
| `lanjian/day_05 input-lanjian` | 3.4 ± 2.0 | 0.2 | 11.8 | 1.56 ± 1.64 |
| `lanjian/day_05 input-mattcl` | 2.7 ± 1.7 | 0.0 | 15.6 | 1.21 ± 1.33 |
| `lanjian/day_05 input-pting` | 3.2 ± 2.2 | 0.5 | 18.4 | 1.47 ± 1.65 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.7 ± 2.0 | 0.1 | 23.7 | 1.24 ± 1.43 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.0 ± 1.9 | 0.2 | 13.9 | 1.37 ± 1.48 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.9 ± 1.9 | 0.2 | 14.4 | 1.33 ± 1.47 |
| `mattcl-solver/aoc run 5 input-mattcl` | 3.5 ± 2.3 | 0.2 | 18.0 | 1.59 ± 1.76 |
| `mattcl-solver/aoc run 5 input-pting` | 2.6 ± 1.8 | 0.0 | 10.3 | 1.18 ± 1.32 |
| `python pting/day05.py input-aspidites` | 65.2 ± 33.7 | 34.8 | 171.0 | 29.67 ± 30.35 |
| `python pting/day05.py input-kcen` | 58.0 ± 25.8 | 38.6 | 179.9 | 26.36 ± 26.06 |
| `python pting/day05.py input-lanjian` | 60.3 ± 24.5 | 44.2 | 181.4 | 27.43 ± 26.65 |
| `python pting/day05.py input-mattcl` | 60.9 ± 24.2 | 42.1 | 154.0 | 27.68 ± 26.80 |
| `python pting/day05.py input-pting` | 55.3 ± 16.7 | 44.1 | 151.0 | 25.17 ± 23.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
