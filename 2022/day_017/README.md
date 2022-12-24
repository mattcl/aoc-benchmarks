# Day 17 benchmarks

[link to problem](http://adventofcode.com/2022/day/17)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 17)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 17 input-mattcl` | 1.7 ± 0.1 | 1.6 | 2.8 | 1.04 ± 0.09 |
| `mattcl-solver/aoc run 17 input-pting` | 1.7 ± 0.1 | 1.5 | 3.5 | 1.00 |
| `python pting/day17/day17.py input-mattcl` | 54378.1 ± 165.1 | 54198.1 | 54522.4 | 32716.84 ± 2023.36 |
| `python pting/day17/day17.py input-pting` | 52142.4 ± 116.3 | 52064.2 | 52276.1 | 31371.72 ± 1939.10 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>3166</pre>|<pre>1577207977186</pre>|
|input-pting|<pre>3135</pre>|<pre>1569054441243</pre>|
