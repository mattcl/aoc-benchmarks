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
| `lanjian/day_23 input-lanjian` | 265.1 ± 1.8 | 262.3 | 267.9 | 1.57 ± 0.01 |
| `lanjian/day_23 input-mattcl` | 222.0 ± 2.3 | 219.8 | 226.6 | 1.32 ± 0.01 |
| `lanjian/day_23 input-pting` | 218.2 ± 2.2 | 215.0 | 223.1 | 1.30 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 197.5 ± 0.8 | 195.8 | 198.6 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 173.8 ± 0.6 | 172.7 | 175.2 | 1.03 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 168.4 ± 0.7 | 167.2 | 169.5 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5867.1 ± 37.6 | 5830.7 | 5905.8 | 34.85 ± 0.26 |
| `python pting/day23/day23.py input-mattcl` | 5313.0 ± 31.3 | 5287.8 | 5348.0 | 31.56 ± 0.22 |
| `python pting/day23/day23.py input-pting` | 5156.1 ± 13.9 | 5147.5 | 5172.2 | 30.62 ± 0.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
