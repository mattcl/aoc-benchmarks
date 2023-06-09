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
| `mattcl-solver/aoc run 24 input-mattcl` | 169.7 ± 0.6 | 168.6 | 171.5 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 24 input-pting` | 167.6 ± 0.6 | 166.7 | 169.0 | 1.00 |
| `python pting/day24/day24.py input-mattcl` | 6710.4 ± 27.3 | 6694.4 | 6741.9 | 40.04 ± 0.22 |
| `python pting/day24/day24.py input-pting` | 6615.0 ± 11.3 | 6602.0 | 6622.9 | 39.47 ± 0.16 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>343</pre>|<pre>960</pre>|
|input-pting|<pre>322</pre>|<pre>974</pre>|
