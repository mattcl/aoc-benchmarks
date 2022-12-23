# Day 22 benchmarks

[link to problem](http://adventofcode.com/2022/day/22)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 22)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 22 input-mattcl` | 1.2 ± 0.1 | 1.0 | 4.0 | 1.00 |
| `mattcl-solver/aoc run 22 input-pting` | 1.2 ± 0.1 | 1.0 | 3.7 | 1.02 ± 0.12 |
| `python pting/day22/day22.py input-mattcl` | 90.8 ± 2.5 | 88.8 | 99.6 | 78.94 ± 6.96 |
| `python pting/day22/day22.py input-pting` | 90.4 ± 2.4 | 87.9 | 97.3 | 78.60 ± 6.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>75254</pre>|<pre>108311</pre>|
|input-pting|<pre>123046</pre>|<pre>195032</pre>|
