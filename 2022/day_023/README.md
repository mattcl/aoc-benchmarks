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
| `lanjian/day_23 input-lanjian` | 264.5 ± 1.2 | 262.5 | 267.2 | 1.58 ± 0.02 |
| `lanjian/day_23 input-mattcl` | 222.1 ± 1.6 | 219.8 | 225.4 | 1.33 ± 0.02 |
| `lanjian/day_23 input-pting` | 220.3 ± 1.9 | 218.2 | 225.4 | 1.32 ± 0.02 |
| `mattcl-solver/aoc run 23 input-lanjian` | 196.4 ± 1.3 | 194.1 | 199.2 | 1.18 ± 0.02 |
| `mattcl-solver/aoc run 23 input-mattcl` | 173.1 ± 1.1 | 170.9 | 174.7 | 1.04 ± 0.02 |
| `mattcl-solver/aoc run 23 input-pting` | 166.9 ± 2.4 | 165.3 | 174.3 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5888.7 ± 33.2 | 5864.4 | 5926.5 | 35.28 ± 0.55 |
| `python pting/day23/day23.py input-mattcl` | 5284.7 ± 18.6 | 5270.3 | 5305.7 | 31.66 ± 0.47 |
| `python pting/day23/day23.py input-pting` | 5159.0 ± 11.7 | 5150.1 | 5172.2 | 30.91 ± 0.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
