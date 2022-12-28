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
| `lanjian/day_23 input-lanjian` | 264.9 ± 2.2 | 262.4 | 268.3 | 1.57 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 222.1 ± 0.8 | 220.5 | 223.5 | 1.31 ± 0.01 |
| `lanjian/day_23 input-pting` | 216.8 ± 0.7 | 216.0 | 218.4 | 1.28 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 197.8 ± 1.2 | 196.2 | 200.1 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 175.2 ± 1.6 | 173.9 | 179.9 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 169.1 ± 0.7 | 168.1 | 170.6 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5893.8 ± 20.5 | 5870.3 | 5908.5 | 34.85 ± 0.19 |
| `python pting/day23/day23.py input-mattcl` | 5310.8 ± 16.4 | 5295.2 | 5327.9 | 31.40 ± 0.17 |
| `python pting/day23/day23.py input-pting` | 5181.3 ± 19.2 | 5169.0 | 5203.5 | 30.63 ± 0.17 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
