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
| `lanjian/day_23 input-lanjian` | 261.3 ± 1.4 | 259.5 | 263.0 | 1.55 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 220.8 ± 2.3 | 218.0 | 224.5 | 1.31 ± 0.02 |
| `lanjian/day_23 input-pting` | 215.1 ± 1.0 | 212.9 | 216.2 | 1.27 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 196.4 ± 1.2 | 194.8 | 198.7 | 1.16 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 174.5 ± 1.0 | 172.9 | 176.1 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 169.0 ± 1.2 | 167.5 | 171.9 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5874.7 ± 47.8 | 5827.4 | 5922.9 | 34.76 ± 0.37 |
| `python pting/day23/day23.py input-mattcl` | 5296.0 ± 68.3 | 5233.5 | 5368.8 | 31.33 ± 0.46 |
| `python pting/day23/day23.py input-pting` | 5154.1 ± 31.8 | 5129.8 | 5190.1 | 30.49 ± 0.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
