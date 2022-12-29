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
| `lanjian/day_23 input-lanjian` | 263.4 ± 0.9 | 261.6 | 264.3 | 1.54 ± 0.03 |
| `lanjian/day_23 input-mattcl` | 221.8 ± 2.0 | 219.8 | 226.1 | 1.30 ± 0.02 |
| `lanjian/day_23 input-pting` | 220.5 ± 3.5 | 217.4 | 228.1 | 1.29 ± 0.03 |
| `mattcl-solver/aoc run 23 input-lanjian` | 198.2 ± 1.0 | 196.5 | 200.5 | 1.16 ± 0.02 |
| `mattcl-solver/aoc run 23 input-mattcl` | 176.1 ± 3.3 | 173.5 | 187.8 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 23 input-pting` | 170.9 ± 2.7 | 167.8 | 175.4 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5922.7 ± 42.5 | 5882.7 | 5967.4 | 34.67 ± 0.61 |
| `python pting/day23/day23.py input-mattcl` | 5304.1 ± 11.8 | 5291.5 | 5314.8 | 31.04 ± 0.50 |
| `python pting/day23/day23.py input-pting` | 5149.0 ± 1.9 | 5147.3 | 5151.0 | 30.14 ± 0.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
