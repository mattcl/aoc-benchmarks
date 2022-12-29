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
| `lanjian/day_23 input-lanjian` | 265.1 ± 1.3 | 263.3 | 266.5 | 1.57 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 221.1 ± 1.4 | 219.6 | 224.0 | 1.31 ± 0.01 |
| `lanjian/day_23 input-pting` | 217.1 ± 1.5 | 215.5 | 219.5 | 1.29 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 197.9 ± 1.5 | 195.8 | 201.3 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 174.8 ± 1.4 | 173.4 | 178.2 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 168.8 ± 1.0 | 167.8 | 170.9 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5889.1 ± 47.1 | 5839.1 | 5932.7 | 34.88 ± 0.34 |
| `python pting/day23/day23.py input-mattcl` | 5329.7 ± 15.0 | 5316.6 | 5346.0 | 31.57 ± 0.20 |
| `python pting/day23/day23.py input-pting` | 5155.6 ± 35.9 | 5130.4 | 5196.8 | 30.54 ± 0.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
