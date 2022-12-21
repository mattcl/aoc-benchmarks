# Day 20 benchmarks

[link to problem](http://adventofcode.com/2022/day/20)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 20)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 20 input-mattcl` | 103.9 ± 0.7 | 102.9 | 105.8 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 103.5 ± 0.6 | 102.7 | 105.1 | 1.00 |
| `python pting/day20/day20.py input-mattcl` | 8014.9 ± 202.3 | 7888.2 | 8248.1 | 77.47 ± 2.01 |
| `python pting/day20/day20.py input-pting` | 7989.9 ± 79.8 | 7941.4 | 8081.9 | 77.23 ± 0.89 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
