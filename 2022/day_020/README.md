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
| `lanjian/day_20 input-lanjian` | 138.7 ± 1.7 | 136.2 | 142.4 | 1.34 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 138.9 ± 1.7 | 136.9 | 142.8 | 1.34 ± 0.02 |
| `lanjian/day_20 input-pting` | 137.5 ± 1.2 | 135.8 | 140.3 | 1.32 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.8 ± 0.9 | 102.7 | 105.7 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.6 ± 1.2 | 103.2 | 108.1 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 104.1 ± 0.5 | 103.1 | 105.1 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8073.9 ± 101.0 | 8004.7 | 8189.7 | 77.77 ± 1.17 |
| `python pting/day20/day20.py input-mattcl` | 8068.4 ± 190.0 | 7883.8 | 8263.4 | 77.72 ± 1.94 |
| `python pting/day20/day20.py input-pting` | 8048.2 ± 157.7 | 7930.9 | 8227.5 | 77.53 ± 1.65 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
