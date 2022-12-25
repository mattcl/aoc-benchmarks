# Day 24 benchmarks

[link to problem](http://adventofcode.com/2022/day/24)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 24)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 24 input-mattcl` | 171.1 ± 1.6 | 169.0 | 174.6 | 1.00 ± 0.02 |
| `mattcl-solver/aoc run 24 input-pting` | 170.5 ± 2.0 | 166.9 | 175.5 | 1.00 |
| `python pting/day24/day24.py input-mattcl` | 5457.1 ± 88.9 | 5376.2 | 5552.2 | 32.02 ± 0.65 |
| `python pting/day24/day24.py input-pting` | 5487.0 ± 161.9 | 5354.2 | 5667.4 | 32.19 ± 1.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>343</pre>|<pre>960</pre>|
|input-pting|<pre>322</pre>|<pre>974</pre>|
