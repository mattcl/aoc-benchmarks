# Day 15 benchmarks

[link to problem](http://adventofcode.com/2022/day/15)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 15)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.7 | 1.4 | 1.09 ± 0.14 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 2.8 | 1.00 |
| `python pting/day15/day15.py input-mattcl` | 28752.6 ± 736.1 | 27849.3 | 29907.0 | 36753.61 ± 3833.96 |
| `python pting/day15/day15.py input-pting` | 28330.6 ± 1073.7 | 26362.7 | 30185.5 | 36214.21 ± 3910.89 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
