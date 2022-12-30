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
| `mattcl-solver/aoc run 16 input-mattcl` | 23.3 ± 0.2 | 22.9 | 24.4 | 1.00 |
| `mattcl-solver/aoc run 16 input-pting` | 31.2 ± 0.5 | 30.7 | 33.4 | 1.34 ± 0.02 |
| `python pting/day16/day16.py input-mattcl` | 25387.5 ± 201.4 | 25174.2 | 25574.3 | 1088.56 ± 13.35 |
| `python pting/day16/day16.py input-pting` | 26416.5 ± 188.4 | 26201.2 | 26551.5 | 1132.68 ± 13.32 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>1376</pre>|<pre>1933</pre>|
|input-pting|<pre>1737</pre>|<pre>2216</pre>|
