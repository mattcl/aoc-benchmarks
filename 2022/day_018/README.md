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
| `lanjian/day_18 input-lanjian` | 2.0 ± 0.1 | 1.8 | 3.9 | 1.31 ± 0.13 |
| `lanjian/day_18 input-mattcl` | 1.9 ± 0.1 | 1.7 | 4.4 | 1.24 ± 0.13 |
| `lanjian/day_18 input-pting` | 1.5 ± 0.1 | 1.4 | 4.3 | 1.00 |
| `mattcl-solver/aoc run 18 input-lanjian` | 2.6 ± 0.1 | 2.4 | 3.4 | 1.69 ± 0.15 |
| `mattcl-solver/aoc run 18 input-mattcl` | 2.5 ± 0.1 | 2.3 | 3.3 | 1.66 ± 0.14 |
| `mattcl-solver/aoc run 18 input-pting` | 1.9 ± 0.1 | 1.7 | 4.1 | 1.25 ± 0.12 |
| `python pting/day18/day18.py input-lanjian` | 93.9 ± 2.6 | 92.1 | 105.3 | 61.39 ± 4.86 |
| `python pting/day18/day18.py input-mattcl` | 90.6 ± 3.1 | 88.6 | 100.9 | 59.28 ± 4.85 |
| `python pting/day18/day18.py input-pting` | 71.0 ± 1.9 | 69.3 | 81.0 | 46.45 ± 3.67 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4242</pre>|<pre>2428</pre>|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
