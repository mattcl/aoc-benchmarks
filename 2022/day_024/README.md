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
| `mattcl-solver/aoc run 24 input-mattcl` | 173.3 ± 4.3 | 167.7 | 183.6 | 1.04 ± 0.03 |
| `mattcl-solver/aoc run 24 input-pting` | 166.9 ± 2.1 | 162.1 | 169.7 | 1.00 |
| `python pting/day24/day24.py input-mattcl` | 5427.7 ± 51.9 | 5392.4 | 5487.3 | 32.51 ± 0.51 |
| `python pting/day24/day24.py input-pting` | 5309.3 ± 30.2 | 5282.4 | 5342.0 | 31.81 ± 0.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>343</pre>|<pre>960</pre>|
|input-pting|<pre>322</pre>|<pre>974</pre>|
