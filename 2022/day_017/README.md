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
| `mattcl-solver/aoc run 17 input-mattcl` | 1.6 ± 0.1 | 1.5 | 3.0 | 1.02 ± 0.13 |
| `mattcl-solver/aoc run 17 input-pting` | 1.6 ± 0.2 | 1.5 | 5.6 | 1.00 |
| `python pting/day17/day17.py input-mattcl` | 54745.1 ± 194.6 | 54521.2 | 54873.5 | 33845.65 ± 3821.44 |
| `python pting/day17/day17.py input-pting` | 52137.2 ± 113.6 | 52032.0 | 52257.7 | 32233.34 ± 3638.27 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>3166</pre>|<pre>1577207977186</pre>|
|input-pting|<pre>3135</pre>|<pre>1569054441243</pre>|
