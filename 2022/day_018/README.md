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
| `mattcl-solver/aoc run 18 input-lanjian` | 2.6 ± 0.2 | 2.3 | 5.6 | 1.32 ± 0.11 |
| `mattcl-solver/aoc run 18 input-mattcl` | 2.5 ± 0.1 | 2.3 | 4.5 | 1.31 ± 0.10 |
| `mattcl-solver/aoc run 18 input-pting` | 1.9 ± 0.1 | 1.8 | 3.9 | 1.00 |
| `python pting/day18/day18.py input-lanjian` | 94.1 ± 3.5 | 91.1 | 107.6 | 48.51 ± 3.16 |
| `python pting/day18/day18.py input-mattcl` | 88.8 ± 1.2 | 87.0 | 93.0 | 45.77 ± 2.52 |
| `python pting/day18/day18.py input-pting` | 71.4 ± 2.9 | 69.2 | 81.7 | 36.78 ± 2.47 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4242</pre>|<pre>2428</pre>|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
