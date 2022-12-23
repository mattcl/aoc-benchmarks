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
| `lanjian/day_23 input-lanjian` | 301.0 ± 1.9 | 297.5 | 304.9 | 1.19 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 254.3 ± 1.9 | 251.2 | 258.5 | 1.01 ± 0.01 |
| `lanjian/day_23 input-pting` | 253.0 ± 1.3 | 251.4 | 255.5 | 1.00 |
| `mattcl-solver/aoc run 23 input-lanjian` | 299.5 ± 1.1 | 298.2 | 301.4 | 1.18 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 253.3 ± 0.9 | 252.4 | 255.5 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 260.1 ± 1.4 | 257.6 | 262.0 | 1.03 ± 0.01 |
| `python pting/day23/day23.py input-lanjian` | 5903.0 ± 19.5 | 5883.8 | 5922.7 | 23.33 ± 0.14 |
| `python pting/day23/day23.py input-mattcl` | 5308.5 ± 32.3 | 5286.9 | 5345.7 | 20.98 ± 0.17 |
| `python pting/day23/day23.py input-pting` | 5188.5 ± 24.6 | 5160.4 | 5206.6 | 20.51 ± 0.14 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
