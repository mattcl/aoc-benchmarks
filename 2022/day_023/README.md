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
| `lanjian/day_23 input-lanjian` | 260.6 ± 1.2 | 259.3 | 263.2 | 1.55 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 223.2 ± 2.7 | 218.7 | 227.6 | 1.33 ± 0.02 |
| `lanjian/day_23 input-pting` | 215.2 ± 0.9 | 214.1 | 217.4 | 1.28 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 196.0 ± 0.9 | 194.0 | 197.2 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 174.8 ± 1.4 | 172.2 | 177.3 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 167.6 ± 0.9 | 166.1 | 169.8 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5891.5 ± 17.7 | 5872.7 | 5907.8 | 35.14 ± 0.22 |
| `python pting/day23/day23.py input-mattcl` | 5316.3 ± 8.0 | 5308.0 | 5324.0 | 31.71 ± 0.18 |
| `python pting/day23/day23.py input-pting` | 5137.1 ± 15.1 | 5122.6 | 5152.8 | 30.64 ± 0.19 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
