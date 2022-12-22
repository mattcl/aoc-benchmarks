# Day 20 benchmarks

[link to problem](http://adventofcode.com/2022/day/20)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 20)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_20 input-lanjian` | 137.7 ± 2.2 | 135.5 | 145.4 | 1.26 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 138.0 ± 1.8 | 136.0 | 144.1 | 1.26 ± 0.02 |
| `lanjian/day_20 input-pting` | 137.0 ± 0.9 | 135.2 | 139.4 | 1.26 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 109.8 ± 0.7 | 108.9 | 111.5 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 109.8 ± 0.8 | 109.1 | 112.7 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 109.1 ± 1.0 | 107.9 | 112.7 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8070.3 ± 123.9 | 7949.3 | 8196.9 | 73.94 ± 1.33 |
| `python pting/day20/day20.py input-mattcl` | 7964.6 ± 118.8 | 7855.0 | 8090.9 | 72.97 ± 1.28 |
| `python pting/day20/day20.py input-pting` | 7944.6 ± 39.0 | 7900.1 | 7972.4 | 72.79 ± 0.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
