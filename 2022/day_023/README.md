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
| `lanjian/day_23 input-lanjian` | 268.1 ± 2.2 | 266.4 | 273.7 | 1.58 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 223.6 ± 1.1 | 221.7 | 225.4 | 1.32 ± 0.01 |
| `lanjian/day_23 input-pting` | 216.5 ± 1.2 | 214.7 | 219.4 | 1.28 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 199.3 ± 1.2 | 197.3 | 201.3 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 175.1 ± 0.8 | 174.0 | 176.4 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 169.7 ± 0.6 | 168.6 | 170.9 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5902.2 ± 18.3 | 5883.7 | 5920.3 | 34.79 ± 0.17 |
| `python pting/day23/day23.py input-mattcl` | 5298.8 ± 30.6 | 5275.7 | 5333.5 | 31.23 ± 0.22 |
| `python pting/day23/day23.py input-pting` | 5209.9 ± 58.3 | 5147.0 | 5262.1 | 30.71 ± 0.36 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
