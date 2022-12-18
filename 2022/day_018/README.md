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
| `mattcl-solver/aoc run 18 input-mattcl` | 42.3 ± 0.3 | 41.9 | 44.0 | 1.87 ± 0.03 |
| `mattcl-solver/aoc run 18 input-pting` | 22.6 ± 0.3 | 22.3 | 24.4 | 1.00 |
| `python pting/day18/day18.py input-mattcl` | 8984.2 ± 15.7 | 8969.2 | 9000.4 | 396.84 ± 5.53 |
| `python pting/day18/day18.py input-pting` | 7746.5 ± 41.2 | 7713.8 | 7792.8 | 342.17 ± 5.07 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
