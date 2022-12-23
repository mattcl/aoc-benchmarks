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
| `lanjian/day_20 input-lanjian` | 139.8 ± 2.0 | 137.0 | 144.0 | 1.27 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 138.5 ± 1.1 | 137.2 | 141.1 | 1.26 ± 0.01 |
| `lanjian/day_20 input-pting` | 138.6 ± 1.2 | 136.6 | 141.0 | 1.26 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 111.1 ± 1.0 | 109.7 | 113.5 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 109.8 ± 0.6 | 109.1 | 112.0 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 110.5 ± 1.0 | 109.3 | 112.8 | 1.01 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8052.7 ± 20.6 | 8039.5 | 8076.5 | 73.35 ± 0.44 |
| `python pting/day20/day20.py input-mattcl` | 7981.1 ± 69.2 | 7901.4 | 8025.6 | 72.70 ± 0.74 |
| `python pting/day20/day20.py input-pting` | 8086.7 ± 135.4 | 8007.4 | 8243.1 | 73.66 ± 1.30 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
