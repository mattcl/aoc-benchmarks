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
| `lanjian/day_23 input-lanjian` | 259.7 ± 2.4 | 257.5 | 265.3 | 1.55 ± 0.02 |
| `lanjian/day_23 input-mattcl` | 218.7 ± 1.2 | 217.0 | 221.2 | 1.31 ± 0.01 |
| `lanjian/day_23 input-pting` | 214.5 ± 1.4 | 211.5 | 217.0 | 1.28 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 195.7 ± 0.8 | 194.7 | 197.3 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 175.1 ± 1.0 | 173.7 | 177.2 | 1.05 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 167.5 ± 0.8 | 166.5 | 169.7 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5834.9 ± 20.3 | 5818.2 | 5857.5 | 34.84 ± 0.21 |
| `python pting/day23/day23.py input-mattcl` | 5299.9 ± 47.3 | 5272.1 | 5354.5 | 31.65 ± 0.32 |
| `python pting/day23/day23.py input-pting` | 5131.3 ± 7.3 | 5123.1 | 5137.1 | 30.64 ± 0.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
