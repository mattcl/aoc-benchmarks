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
| `mattcl-solver/aoc run 24 input-mattcl` | 171.0 ± 1.6 | 168.6 | 174.4 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 24 input-pting` | 166.6 ± 1.1 | 165.3 | 169.1 | 1.00 |
| `python pting/day24/day24.py input-mattcl` | 5375.8 ± 68.0 | 5298.3 | 5425.5 | 32.26 ± 0.46 |
| `python pting/day24/day24.py input-pting` | 5205.6 ± 51.5 | 5148.5 | 5248.7 | 31.24 ± 0.37 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>343</pre>|<pre>960</pre>|
|input-pting|<pre>322</pre>|<pre>974</pre>|
