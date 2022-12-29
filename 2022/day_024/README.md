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
| `mattcl-solver/aoc run 24 input-mattcl` | 169.2 ± 1.5 | 166.3 | 172.2 | 1.00 ± 0.02 |
| `mattcl-solver/aoc run 24 input-pting` | 168.5 ± 2.4 | 165.7 | 174.9 | 1.00 |
| `python pting/day24/day24.py input-mattcl` | 5308.2 ± 85.5 | 5258.7 | 5406.9 | 31.50 ± 0.68 |
| `python pting/day24/day24.py input-pting` | 5275.6 ± 30.4 | 5244.5 | 5305.4 | 31.31 ± 0.49 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>343</pre>|<pre>960</pre>|
|input-pting|<pre>322</pre>|<pre>974</pre>|
