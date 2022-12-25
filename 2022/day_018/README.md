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
| `lanjian/day_18 input-lanjian` | 2.0 ± 0.3 | 1.8 | 7.3 | 1.29 ± 0.19 |
| `lanjian/day_18 input-mattcl` | 1.9 ± 0.1 | 1.7 | 3.2 | 1.21 ± 0.11 |
| `lanjian/day_18 input-pting` | 1.5 ± 0.1 | 1.4 | 3.3 | 1.00 |
| `mattcl-solver/aoc run 18 input-lanjian` | 2.6 ± 0.2 | 2.4 | 4.5 | 1.66 ± 0.16 |
| `mattcl-solver/aoc run 18 input-mattcl` | 2.5 ± 0.1 | 2.3 | 3.9 | 1.62 ± 0.14 |
| `mattcl-solver/aoc run 18 input-pting` | 1.9 ± 0.1 | 1.8 | 3.9 | 1.25 ± 0.12 |
| `python pting/day18/day18.py input-lanjian` | 93.8 ± 1.0 | 92.4 | 96.0 | 60.84 ± 4.56 |
| `python pting/day18/day18.py input-mattcl` | 89.4 ± 0.9 | 88.0 | 91.2 | 57.96 ± 4.34 |
| `python pting/day18/day18.py input-pting` | 71.7 ± 1.0 | 70.0 | 73.7 | 46.49 ± 3.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4242</pre>|<pre>2428</pre>|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
