# Day 18 benchmarks

[link to problem](http://adventofcode.com/2022/day/18)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 18)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 18 input-lanjian` | 2.6 ± 0.2 | 2.3 | 5.1 | 1.36 ± 0.15 |
| `mattcl-solver/aoc run 18 input-mattcl` | 2.5 ± 0.1 | 2.3 | 3.6 | 1.33 ± 0.10 |
| `mattcl-solver/aoc run 18 input-pting` | 1.9 ± 0.1 | 1.7 | 4.0 | 1.00 |
| `python pting/day18/day18.py input-lanjian` | 93.6 ± 0.9 | 91.7 | 95.4 | 49.27 ± 2.98 |
| `python pting/day18/day18.py input-mattcl` | 91.1 ± 2.3 | 89.0 | 101.3 | 47.95 ± 3.10 |
| `python pting/day18/day18.py input-pting` | 71.3 ± 1.5 | 69.4 | 77.7 | 37.56 ± 2.39 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4242</pre>|<pre>2428</pre>|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
