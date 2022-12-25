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
| `lanjian/day_23 input-lanjian` | 264.2 ± 2.3 | 260.6 | 268.2 | 1.57 ± 0.02 |
| `lanjian/day_23 input-mattcl` | 222.2 ± 1.8 | 220.1 | 227.1 | 1.32 ± 0.01 |
| `lanjian/day_23 input-pting` | 218.4 ± 1.2 | 216.5 | 220.9 | 1.30 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 196.8 ± 2.2 | 195.2 | 203.6 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 174.0 ± 0.9 | 172.5 | 175.8 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 168.5 ± 0.7 | 166.9 | 169.6 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5929.3 ± 69.7 | 5856.1 | 5994.8 | 35.20 ± 0.44 |
| `python pting/day23/day23.py input-mattcl` | 5302.8 ± 8.7 | 5293.1 | 5309.9 | 31.48 ± 0.14 |
| `python pting/day23/day23.py input-pting` | 5172.5 ± 43.8 | 5134.4 | 5220.4 | 30.70 ± 0.29 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
