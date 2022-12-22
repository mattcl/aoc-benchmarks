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
| `lanjian/day_20 input-lanjian` | 138.8 ± 1.0 | 137.2 | 141.3 | 1.27 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 137.8 ± 1.6 | 136.0 | 141.7 | 1.26 ± 0.02 |
| `lanjian/day_20 input-pting` | 138.5 ± 3.3 | 135.3 | 149.3 | 1.26 ± 0.03 |
| `mattcl-solver/aoc run 20 input-lanjian` | 109.9 ± 1.0 | 108.8 | 113.0 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 110.1 ± 1.1 | 108.5 | 113.1 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 109.7 ± 1.1 | 108.1 | 112.7 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 7974.2 ± 76.5 | 7904.8 | 8056.2 | 72.72 ± 1.03 |
| `python pting/day20/day20.py input-mattcl` | 8214.7 ± 242.1 | 7968.0 | 8452.0 | 74.91 ± 2.34 |
| `python pting/day20/day20.py input-pting` | 7997.8 ± 51.1 | 7960.0 | 8055.9 | 72.93 ± 0.89 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
