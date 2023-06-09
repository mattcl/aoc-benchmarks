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
| `lanjian/day_23 input-lanjian` | 259.0 ± 0.6 | 258.4 | 260.0 | 1.54 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 218.2 ± 3.1 | 217.1 | 228.5 | 1.30 ± 0.02 |
| `lanjian/day_23 input-pting` | 213.7 ± 0.4 | 213.1 | 214.5 | 1.27 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 195.1 ± 0.2 | 194.8 | 195.6 | 1.16 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 173.3 ± 0.9 | 172.4 | 175.2 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 167.9 ± 1.2 | 167.1 | 171.9 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 7337.9 ± 18.2 | 7321.4 | 7357.5 | 43.70 ± 0.34 |
| `python pting/day23/day23.py input-mattcl` | 6599.1 ± 9.3 | 6588.3 | 6604.7 | 39.30 ± 0.29 |
| `python pting/day23/day23.py input-pting` | 6440.1 ± 21.8 | 6421.2 | 6463.9 | 38.35 ± 0.31 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
