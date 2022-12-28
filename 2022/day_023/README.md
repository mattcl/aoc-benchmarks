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
| `lanjian/day_23 input-lanjian` | 262.8 ± 2.1 | 261.0 | 268.8 | 1.55 ± 0.02 |
| `lanjian/day_23 input-mattcl` | 222.9 ± 2.3 | 220.3 | 227.7 | 1.32 ± 0.02 |
| `lanjian/day_23 input-pting` | 219.1 ± 2.4 | 215.8 | 225.2 | 1.29 ± 0.02 |
| `mattcl-solver/aoc run 23 input-lanjian` | 198.1 ± 1.9 | 195.9 | 201.7 | 1.17 ± 0.02 |
| `mattcl-solver/aoc run 23 input-mattcl` | 174.4 ± 0.6 | 173.7 | 175.7 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 169.2 ± 1.8 | 167.8 | 174.8 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5870.5 ± 8.9 | 5861.7 | 5879.5 | 34.69 ± 0.37 |
| `python pting/day23/day23.py input-mattcl` | 5355.8 ± 47.5 | 5304.1 | 5397.5 | 31.65 ± 0.43 |
| `python pting/day23/day23.py input-pting` | 5172.9 ± 34.2 | 5149.8 | 5212.2 | 30.57 ± 0.38 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
