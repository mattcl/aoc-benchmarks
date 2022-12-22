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
| `lanjian/day_20 input-lanjian` | 140.2 ± 4.3 | 136.9 | 153.0 | 1.27 ± 0.04 |
| `lanjian/day_20 input-mattcl` | 138.4 ± 1.3 | 136.6 | 141.7 | 1.26 ± 0.02 |
| `lanjian/day_20 input-pting` | 137.7 ± 0.9 | 136.0 | 139.9 | 1.25 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 111.0 ± 1.0 | 109.5 | 113.5 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 110.0 ± 0.9 | 108.8 | 111.8 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 109.9 ± 1.1 | 108.7 | 113.1 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8191.0 ± 232.6 | 7993.3 | 8447.2 | 74.50 ± 2.24 |
| `python pting/day20/day20.py input-mattcl` | 8049.6 ± 34.4 | 8022.3 | 8088.3 | 73.21 ± 0.78 |
| `python pting/day20/day20.py input-pting` | 8039.9 ± 103.6 | 7952.8 | 8154.6 | 73.13 ± 1.18 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
