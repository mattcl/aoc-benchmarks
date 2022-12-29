# Day 18 benchmarks

[link to problem](http://adventofcode.com/2022/day/18)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 18)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_18 input-lanjian` | 2.0 ± 0.1 | 1.8 | 3.7 | 1.30 ± 0.13 |
| `lanjian/day_18 input-mattcl` | 1.9 ± 0.1 | 1.7 | 2.6 | 1.21 ± 0.11 |
| `lanjian/day_18 input-pting` | 1.5 ± 0.1 | 1.4 | 3.7 | 1.00 |
| `mattcl-solver/aoc run 18 input-lanjian` | 2.6 ± 0.1 | 2.3 | 4.7 | 1.65 ± 0.15 |
| `mattcl-solver/aoc run 18 input-mattcl` | 2.5 ± 0.1 | 2.3 | 3.4 | 1.64 ± 0.14 |
| `mattcl-solver/aoc run 18 input-pting` | 1.9 ± 0.1 | 1.7 | 3.9 | 1.24 ± 0.11 |
| `python pting/day18/day18.py input-lanjian` | 94.2 ± 3.2 | 92.0 | 106.0 | 61.02 ± 4.90 |
| `python pting/day18/day18.py input-mattcl` | 89.7 ± 2.5 | 88.1 | 101.1 | 58.11 ± 4.52 |
| `python pting/day18/day18.py input-pting` | 71.2 ± 1.7 | 70.1 | 80.1 | 46.14 ± 3.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4242</pre>|<pre>2428</pre>|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
