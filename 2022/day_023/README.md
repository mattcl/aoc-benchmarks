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
| `lanjian/day_23 input-lanjian` | 264.0 ± 1.9 | 261.5 | 268.2 | 1.56 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 222.3 ± 2.2 | 220.2 | 227.2 | 1.31 ± 0.01 |
| `lanjian/day_23 input-pting` | 218.8 ± 1.4 | 216.8 | 221.1 | 1.29 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 198.1 ± 0.9 | 197.0 | 199.8 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 175.7 ± 0.7 | 174.9 | 177.4 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 169.6 ± 0.9 | 168.7 | 171.7 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5921.6 ± 18.0 | 5903.7 | 5939.7 | 34.91 ± 0.21 |
| `python pting/day23/day23.py input-mattcl` | 5299.6 ± 3.4 | 5296.8 | 5303.3 | 31.24 ± 0.16 |
| `python pting/day23/day23.py input-pting` | 5136.3 ± 5.8 | 5131.1 | 5142.6 | 30.28 ± 0.16 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
