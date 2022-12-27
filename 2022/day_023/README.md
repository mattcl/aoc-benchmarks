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
| `lanjian/day_23 input-lanjian` | 264.4 ± 1.5 | 262.0 | 266.5 | 1.56 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 222.4 ± 1.4 | 220.6 | 225.9 | 1.32 ± 0.01 |
| `lanjian/day_23 input-pting` | 221.6 ± 1.6 | 218.4 | 225.0 | 1.31 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 198.1 ± 0.8 | 196.6 | 199.4 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 174.6 ± 0.6 | 173.5 | 175.8 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 169.0 ± 0.8 | 167.9 | 170.6 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5872.1 ± 48.5 | 5819.0 | 5913.9 | 34.75 ± 0.33 |
| `python pting/day23/day23.py input-mattcl` | 5295.9 ± 31.6 | 5261.2 | 5322.8 | 31.34 ± 0.24 |
| `python pting/day23/day23.py input-pting` | 5151.4 ± 43.2 | 5109.2 | 5195.6 | 30.48 ± 0.29 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
