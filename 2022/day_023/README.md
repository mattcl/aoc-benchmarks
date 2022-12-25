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
| `lanjian/day_23 input-lanjian` | 261.8 ± 2.0 | 258.7 | 266.1 | 1.55 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 221.3 ± 1.9 | 218.3 | 225.2 | 1.31 ± 0.01 |
| `lanjian/day_23 input-pting` | 216.6 ± 1.6 | 214.6 | 219.8 | 1.29 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 196.5 ± 0.9 | 194.8 | 198.8 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 175.8 ± 1.1 | 174.3 | 177.8 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 168.4 ± 0.9 | 167.1 | 169.9 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5918.4 ± 59.3 | 5860.5 | 5979.1 | 35.14 ± 0.40 |
| `python pting/day23/day23.py input-mattcl` | 5336.0 ± 42.0 | 5297.6 | 5380.8 | 31.68 ± 0.30 |
| `python pting/day23/day23.py input-pting` | 5208.2 ± 77.5 | 5152.4 | 5296.7 | 30.92 ± 0.49 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
