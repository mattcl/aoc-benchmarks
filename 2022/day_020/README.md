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
| `lanjian/day_20 input-lanjian` | 137.2 ± 0.9 | 136.2 | 139.3 | 1.25 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 138.1 ± 1.0 | 136.7 | 140.7 | 1.25 ± 0.01 |
| `lanjian/day_20 input-pting` | 137.0 ± 0.7 | 136.0 | 137.9 | 1.24 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 110.8 ± 1.0 | 109.7 | 113.5 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 110.4 ± 1.0 | 108.8 | 112.8 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 110.1 ± 1.1 | 109.0 | 112.8 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8139.9 ± 145.2 | 8020.0 | 8301.4 | 73.90 ± 1.50 |
| `python pting/day20/day20.py input-mattcl` | 7981.9 ± 42.8 | 7943.1 | 8027.8 | 72.47 ± 0.80 |
| `python pting/day20/day20.py input-pting` | 7976.4 ± 48.4 | 7928.3 | 8025.0 | 72.42 ± 0.82 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
