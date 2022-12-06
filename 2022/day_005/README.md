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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 26.3 ± 3.5 | 23.2 | 39.2 | 12.44 ± 7.26 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 26.6 ± 4.2 | 22.9 | 39.7 | 12.56 ± 7.41 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 26.3 ± 3.8 | 23.2 | 44.8 | 12.40 ± 7.28 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 42.5 ± 16.7 | 23.3 | 89.8 | 20.07 ± 13.88 |
| `aspidites-solver/aoc -i input-pting -d 5` | 28.0 ± 5.4 | 22.7 | 47.3 | 13.21 ± 7.94 |
| `kcen/2022/05/solve input-aspidites` | 176.5 ± 16.7 | 148.2 | 208.2 | 83.38 ± 48.06 |
| `kcen/2022/05/solve input-kcen` | 173.9 ± 21.7 | 135.2 | 214.3 | 82.13 ± 47.80 |
| `kcen/2022/05/solve input-lanjian` | 167.3 ± 13.0 | 146.9 | 199.0 | 79.03 ± 45.35 |
| `kcen/2022/05/solve input-mattcl` | 181.9 ± 17.3 | 158.9 | 223.2 | 85.91 ± 49.52 |
| `kcen/2022/05/solve input-pting` | 186.7 ± 17.7 | 162.4 | 215.9 | 88.16 ± 50.81 |
| `lanjian/day_05 input-aspidites` | 2.5 ± 1.6 | 0.3 | 26.9 | 1.18 ± 1.03 |
| `lanjian/day_05 input-kcen` | 2.1 ± 1.4 | 0.2 | 14.3 | 1.01 ± 0.89 |
| `lanjian/day_05 input-lanjian` | 2.1 ± 1.2 | 0.3 | 10.2 | 1.00 |
| `lanjian/day_05 input-mattcl` | 2.6 ± 1.3 | 0.4 | 9.4 | 1.21 ± 0.91 |
| `lanjian/day_05 input-pting` | 2.5 ± 1.5 | 0.1 | 20.2 | 1.18 ± 0.96 |
| `mattcl-solver/aoc run 5 input-aspidites` | 2.5 ± 1.2 | 0.2 | 10.1 | 1.19 ± 0.88 |
| `mattcl-solver/aoc run 5 input-kcen` | 2.8 ± 1.3 | 0.5 | 10.7 | 1.33 ± 0.97 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.6 ± 1.1 | 0.4 | 12.7 | 1.21 ± 0.87 |
| `mattcl-solver/aoc run 5 input-mattcl` | 2.4 ± 1.4 | 0.5 | 19.0 | 1.12 ± 0.93 |
| `mattcl-solver/aoc run 5 input-pting` | 2.6 ± 1.5 | 0.5 | 17.0 | 1.22 ± 1.00 |
| `python pting/day05.py input-aspidites` | 63.2 ± 9.1 | 46.0 | 84.3 | 29.87 ± 17.52 |
| `python pting/day05.py input-kcen` | 59.3 ± 8.0 | 44.6 | 77.2 | 28.02 ± 16.38 |
| `python pting/day05.py input-lanjian` | 56.9 ± 6.3 | 44.2 | 76.2 | 26.88 ± 15.57 |
| `python pting/day05.py input-mattcl` | 65.2 ± 9.2 | 53.2 | 89.3 | 30.78 ± 18.03 |
| `python pting/day05.py input-pting` | 63.8 ± 9.6 | 49.1 | 90.4 | 30.11 ± 17.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
