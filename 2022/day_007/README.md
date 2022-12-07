# Day 7 benchmarks

[link to problem](http://adventofcode.com/2022/day/7)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 7)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_07 input-lanjian` | 3.2 ± 1.5 | 1.1 | 16.1 | 1.00 |
| `lanjian/day_07 input-mattcl` | 3.5 ± 1.2 | 1.4 | 11.0 | 1.09 ± 0.63 |
| `lanjian/day_07 input-pting` | 4.0 ± 1.8 | 1.2 | 14.1 | 1.24 ± 0.80 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.5 ± 1.2 | 1.1 | 13.4 | 1.09 ± 0.63 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.4 ± 1.4 | 1.0 | 14.5 | 1.07 ± 0.65 |
| `mattcl-solver/aoc run 7 input-pting` | 3.8 ± 1.3 | 1.2 | 10.9 | 1.18 ± 0.68 |
| `python pting/day07.py input-lanjian` | 57.1 ± 8.4 | 41.3 | 91.3 | 17.91 ± 8.61 |
| `python pting/day07.py input-mattcl` | 58.9 ± 9.0 | 46.6 | 79.6 | 18.46 ± 8.91 |
| `python pting/day07.py input-pting` | 62.0 ± 10.9 | 43.9 | 85.7 | 19.44 ± 9.54 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
