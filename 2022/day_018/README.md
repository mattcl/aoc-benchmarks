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
| `lanjian/day_18 input-lanjian` | 2.3 ± 0.2 | 2.0 | 3.3 | 1.28 ± 0.14 |
| `lanjian/day_18 input-mattcl` | 2.2 ± 0.2 | 1.9 | 3.2 | 1.23 ± 0.13 |
| `lanjian/day_18 input-pting` | 1.8 ± 0.1 | 1.6 | 2.6 | 1.00 |
| `mattcl-solver/aoc run 18 input-lanjian` | 2.8 ± 0.1 | 2.6 | 4.0 | 1.61 ± 0.14 |
| `mattcl-solver/aoc run 18 input-mattcl` | 2.8 ± 0.1 | 2.6 | 3.8 | 1.57 ± 0.14 |
| `mattcl-solver/aoc run 18 input-pting` | 2.1 ± 0.1 | 2.0 | 4.5 | 1.21 ± 0.12 |
| `python pting/day18/day18.py input-lanjian` | 115.6 ± 3.6 | 114.3 | 132.7 | 65.60 ± 5.38 |
| `python pting/day18/day18.py input-mattcl` | 108.9 ± 0.5 | 108.2 | 110.1 | 61.75 ± 4.69 |
| `python pting/day18/day18.py input-pting` | 86.4 ± 0.5 | 85.6 | 87.9 | 49.03 ± 3.73 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4242</pre>|<pre>2428</pre>|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
