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
| `lanjian/day_23 input-lanjian` | 261.4 ± 1.3 | 259.8 | 263.6 | 1.56 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 220.4 ± 1.6 | 218.0 | 224.1 | 1.31 ± 0.01 |
| `lanjian/day_23 input-pting` | 214.7 ± 1.0 | 213.4 | 216.5 | 1.28 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 196.7 ± 1.4 | 195.3 | 201.0 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 173.5 ± 0.8 | 172.4 | 175.4 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 168.1 ± 1.1 | 166.4 | 170.2 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5882.9 ± 84.5 | 5830.9 | 5980.4 | 34.99 ± 0.55 |
| `python pting/day23/day23.py input-mattcl` | 5295.1 ± 21.9 | 5273.0 | 5316.8 | 31.50 ± 0.25 |
| `python pting/day23/day23.py input-pting` | 5142.6 ± 17.1 | 5128.6 | 5161.6 | 30.59 ± 0.23 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
