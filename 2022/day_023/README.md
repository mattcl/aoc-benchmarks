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
| `lanjian/day_23 input-lanjian` | 265.5 ± 2.5 | 261.4 | 269.0 | 1.57 ± 0.02 |
| `lanjian/day_23 input-mattcl` | 221.8 ± 1.3 | 219.7 | 224.0 | 1.31 ± 0.01 |
| `lanjian/day_23 input-pting` | 216.0 ± 0.8 | 215.0 | 218.1 | 1.28 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 199.1 ± 0.8 | 197.8 | 200.7 | 1.18 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 176.1 ± 1.3 | 174.6 | 179.5 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 169.0 ± 0.5 | 168.1 | 169.7 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5873.4 ± 32.6 | 5839.8 | 5905.0 | 34.76 ± 0.22 |
| `python pting/day23/day23.py input-mattcl` | 5304.2 ± 29.0 | 5280.5 | 5336.5 | 31.39 ± 0.19 |
| `python pting/day23/day23.py input-pting` | 5139.6 ± 13.2 | 5125.9 | 5152.2 | 30.41 ± 0.12 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
