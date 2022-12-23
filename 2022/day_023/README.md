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
| `lanjian/day_23 input-lanjian` | 301.4 ± 1.8 | 298.5 | 304.3 | 1.79 ± 0.02 |
| `lanjian/day_23 input-mattcl` | 251.4 ± 1.0 | 250.0 | 253.3 | 1.49 ± 0.01 |
| `lanjian/day_23 input-pting` | 247.3 ± 1.5 | 245.6 | 249.7 | 1.47 ± 0.01 |
| `mattcl-solver/aoc run 23 input-lanjian` | 196.9 ± 0.8 | 196.0 | 198.7 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 23 input-mattcl` | 174.8 ± 1.1 | 173.1 | 177.5 | 1.04 ± 0.01 |
| `mattcl-solver/aoc run 23 input-pting` | 168.7 ± 1.2 | 167.2 | 171.7 | 1.00 |
| `python pting/day23/day23.py input-lanjian` | 5870.1 ± 23.9 | 5842.9 | 5887.6 | 34.80 ± 0.28 |
| `python pting/day23/day23.py input-mattcl` | 5271.4 ± 18.6 | 5256.4 | 5292.2 | 31.25 ± 0.24 |
| `python pting/day23/day23.py input-pting` | 5128.3 ± 11.0 | 5117.2 | 5139.3 | 30.41 ± 0.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3849</pre>|<pre>995</pre>|
|input-mattcl|<pre>3788</pre>|<pre>921</pre>|
|input-pting|<pre>4070</pre>|<pre>881</pre>|
