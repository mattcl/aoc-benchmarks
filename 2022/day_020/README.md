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
| `lanjian/day_20 input-lanjian` | 137.3 ± 1.2 | 135.4 | 140.8 | 1.26 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 137.6 ± 1.0 | 136.3 | 140.4 | 1.26 ± 0.01 |
| `lanjian/day_20 input-pting` | 137.7 ± 1.4 | 135.4 | 140.4 | 1.26 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 109.1 ± 0.6 | 108.3 | 111.2 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 110.5 ± 2.0 | 108.9 | 119.2 | 1.01 ± 0.02 |
| `mattcl-solver/aoc run 20 input-pting` | 109.4 ± 1.0 | 108.0 | 111.7 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 7961.0 ± 82.6 | 7889.6 | 8051.5 | 72.98 ± 0.87 |
| `python pting/day20/day20.py input-mattcl` | 7983.2 ± 126.5 | 7837.6 | 8066.1 | 73.18 ± 1.23 |
| `python pting/day20/day20.py input-pting` | 7969.6 ± 68.2 | 7908.7 | 8043.3 | 73.06 ± 0.75 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
