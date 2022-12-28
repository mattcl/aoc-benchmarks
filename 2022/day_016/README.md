# Day 16 benchmarks

[link to problem](http://adventofcode.com/2022/day/16)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 16)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 16 input-mattcl` | 23.3 ± 0.2 | 22.8 | 23.9 | 1.00 |
| `mattcl-solver/aoc run 16 input-pting` | 31.8 ± 1.0 | 30.4 | 37.2 | 1.36 ± 0.05 |
| `python pting/day16/day16.py input-mattcl` | 25499.5 ± 384.7 | 25090.9 | 25854.8 | 1095.09 ± 19.37 |
| `python pting/day16/day16.py input-pting` | 26505.1 ± 123.3 | 26387.0 | 26633.1 | 1138.28 ± 11.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>1376</pre>|<pre>1933</pre>|
|input-pting|<pre>1737</pre>|<pre>2216</pre>|
