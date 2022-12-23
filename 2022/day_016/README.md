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
| `mattcl-solver/aoc run 16 input-mattcl` | 23.4 ± 0.3 | 22.8 | 25.3 | 1.00 |
| `mattcl-solver/aoc run 16 input-pting` | 31.1 ± 0.3 | 30.7 | 32.4 | 1.33 ± 0.02 |
| `python pting/day16/day16.py input-mattcl` | 25444.7 ± 136.8 | 25298.0 | 25568.9 | 1087.04 ± 16.57 |
| `python pting/day16/day16.py input-pting` | 26478.6 ± 271.9 | 26173.1 | 26694.0 | 1131.21 ± 19.88 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>1376</pre>|<pre>1933</pre>|
|input-pting|<pre>1737</pre>|<pre>2216</pre>|
