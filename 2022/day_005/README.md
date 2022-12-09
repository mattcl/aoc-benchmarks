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
| `aspidites-solver/aoc -i input-aspidites -d 5` | 23.1 ± 2.1 | 21.1 | 35.9 | 59.24 ± 101.11 |
| `aspidites-solver/aoc -i input-kcen -d 5` | 23.0 ± 1.8 | 21.3 | 34.6 | 58.98 ± 100.62 |
| `aspidites-solver/aoc -i input-lanjian -d 5` | 23.9 ± 4.0 | 21.1 | 44.4 | 61.11 ± 104.65 |
| `aspidites-solver/aoc -i input-mattcl -d 5` | 23.5 ± 3.0 | 19.8 | 40.9 | 60.22 ± 102.93 |
| `aspidites-solver/aoc -i input-pting -d 5` | 25.2 ± 6.0 | 21.3 | 66.3 | 64.54 ± 111.06 |
| `kcen/2022/05/solve input-aspidites` | 160.8 ± 13.9 | 140.2 | 183.1 | 411.84 ± 702.85 |
| `kcen/2022/05/solve input-kcen` | 172.1 ± 24.9 | 139.6 | 235.4 | 440.83 ± 754.07 |
| `kcen/2022/05/solve input-lanjian` | 165.9 ± 15.4 | 148.4 | 192.8 | 424.94 ± 725.35 |
| `kcen/2022/05/solve input-mattcl` | 165.6 ± 19.1 | 138.2 | 212.1 | 424.28 ± 724.81 |
| `kcen/2022/05/solve input-pting` | 178.4 ± 18.3 | 150.1 | 207.5 | 457.07 ± 780.46 |
| `lanjian/day_05 input-aspidites` | 0.6 ± 0.8 | 0.0 | 12.4 | 1.48 ± 3.30 |
| `lanjian/day_05 input-kcen` | 1.0 ± 1.3 | 0.0 | 18.8 | 2.45 ± 5.37 |
| `lanjian/day_05 input-lanjian` | 1.6 ± 2.1 | 0.0 | 16.0 | 4.17 ± 8.95 |
| `lanjian/day_05 input-mattcl` | 0.4 ± 0.7 | 0.0 | 4.3 | 1.00 |
| `lanjian/day_05 input-pting` | 0.7 ± 3.8 | 0.0 | 83.3 | 1.77 ± 10.31 |
| `mattcl-solver/aoc run 5 input-aspidites` | 0.7 ± 0.7 | 0.0 | 5.0 | 1.84 ± 3.62 |
| `mattcl-solver/aoc run 5 input-kcen` | 3.4 ± 4.7 | 0.0 | 30.2 | 8.60 ± 18.94 |
| `mattcl-solver/aoc run 5 input-lanjian` | 2.0 ± 2.0 | 0.0 | 15.3 | 5.07 ± 10.03 |
| `mattcl-solver/aoc run 5 input-mattcl` | 1.3 ± 1.0 | 0.0 | 7.9 | 3.33 ± 6.17 |
| `mattcl-solver/aoc run 5 input-pting` | 1.1 ± 1.4 | 0.0 | 9.2 | 2.75 ± 5.89 |
| `python pting/day05.py input-aspidites` | 54.1 ± 7.9 | 42.8 | 74.8 | 138.59 ± 237.09 |
| `python pting/day05.py input-kcen` | 55.3 ± 8.9 | 43.5 | 83.8 | 141.56 ± 242.34 |
| `python pting/day05.py input-lanjian` | 80.1 ± 20.9 | 47.2 | 153.8 | 205.24 ± 353.89 |
| `python pting/day05.py input-mattcl` | 62.6 ± 8.8 | 46.1 | 81.0 | 160.47 ± 274.44 |
| `python pting/day05.py input-pting` | 57.3 ± 8.5 | 43.7 | 78.8 | 146.90 ± 251.32 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>RFFFWBPNS</pre>|<pre>CQQBBJFCS</pre>|
|input-mattcl|<pre>VQZNJMWTR</pre>|<pre>NLCDCLVMQ</pre>|
|input-aspidites|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
|input-pting|<pre>VJSFHWGFT</pre>|<pre>LCTQFBVZV</pre>|
|input-kcen|<pre>ZBDRNPMVH</pre>|<pre>WDLPFNNNB</pre>|
