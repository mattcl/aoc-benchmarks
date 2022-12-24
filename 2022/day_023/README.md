# Day 23 benchmarks

[link to problem](http://adventofcode.com/2022/day/23)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 23)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_23 input-lanjian` | 263.5 ± 2.7 | 260.2 | 267.9 | 1.56 ± 0.02 |
| `lanjian/day_23 input-mattcl` | 223.6 ± 1.2 | 222.4 | 226.2 | 1.32 ± 0.01 |
| `lanjian/day_23 input-pting` | 216.5 ± 2.4 | 213.4 | 222.7 | 1.28 ± 0.02 |
| `mattcl-solver/aoc run 23 input-lanjian` | 197.5 ± 1.5 | 195.0 | 200.5 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 176.0 ± 1.1 | 173.8 | 177.5 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 168.8 ± 1.4 | 166.0 | 171.8 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5882.4 ± 8.8 | 5875.0 | 5892.2 | 34.85 ± 0.30 |
| `python pting/day23/day23.py input-mattcl` | 5291.4 ± 10.0 | 5283.9 | 5302.8 | 31.35 ± 0.27 |
| `python pting/day23/day23.py input-pting` | 5148.6 ± 49.3 | 5114.3 | 5205.1 | 30.50 ± 0.39 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
