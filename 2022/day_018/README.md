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
| `lanjian/day_18 input-lanjian` | 2.0 ± 0.1 | 1.8 | 2.7 | 1.29 ± 0.11 |
| `lanjian/day_18 input-mattcl` | 1.9 ± 0.2 | 1.7 | 4.1 | 1.28 ± 0.13 |
| `lanjian/day_18 input-pting` | 1.5 ± 0.1 | 1.4 | 3.3 | 1.00 |
| `mattcl-solver/aoc run 18 input-lanjian` | 2.5 ± 0.1 | 2.3 | 3.4 | 1.66 ± 0.13 |
| `mattcl-solver/aoc run 18 input-mattcl` | 2.5 ± 0.2 | 2.3 | 5.0 | 1.67 ± 0.15 |
| `mattcl-solver/aoc run 18 input-pting` | 1.9 ± 0.1 | 1.7 | 3.2 | 1.26 ± 0.11 |
| `python pting/day18/day18.py input-lanjian` | 95.0 ± 1.3 | 93.0 | 98.0 | 62.58 ± 4.23 |
| `python pting/day18/day18.py input-mattcl` | 90.0 ± 3.2 | 87.2 | 100.8 | 59.30 ± 4.44 |
| `python pting/day18/day18.py input-pting` | 72.1 ± 1.3 | 70.4 | 75.0 | 47.51 ± 3.25 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4242</pre>|<pre>2428</pre>|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
