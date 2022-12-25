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
| `lanjian/day_23 input-lanjian` | 263.1 ± 1.2 | 261.6 | 265.5 | 1.56 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 221.2 ± 1.1 | 219.1 | 223.1 | 1.31 ± 0.01 |
| `lanjian/day_23 input-pting` | 217.4 ± 0.8 | 216.0 | 219.2 | 1.29 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 195.7 ± 0.8 | 194.5 | 197.8 | 1.16 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 174.5 ± 1.0 | 173.1 | 176.5 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 168.2 ± 0.9 | 166.8 | 169.7 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5885.3 ± 27.0 | 5858.3 | 5912.3 | 34.99 ± 0.24 |
| `python pting/day23/day23.py input-mattcl` | 5282.3 ± 21.9 | 5260.8 | 5304.5 | 31.41 ± 0.21 |
| `python pting/day23/day23.py input-pting` | 5121.3 ± 12.3 | 5113.6 | 5135.5 | 30.45 ± 0.18 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
