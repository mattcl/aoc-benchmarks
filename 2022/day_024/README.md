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
| `mattcl-solver/aoc run 24 input-mattcl` | 174.2 ± 2.0 | 170.2 | 177.1 | 1.03 ± 0.02 |
| `mattcl-solver/aoc run 24 input-pting` | 169.6 ± 1.8 | 166.4 | 172.1 | 1.00 |
| `python pting/day24/day24.py input-mattcl` | 5510.4 ± 96.4 | 5430.6 | 5617.5 | 32.49 ± 0.67 |
| `python pting/day24/day24.py input-pting` | 5386.3 ± 87.5 | 5295.4 | 5469.8 | 31.76 ± 0.62 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>343</pre>|<pre>960</pre>|
|input-pting|<pre>322</pre>|<pre>974</pre>|
