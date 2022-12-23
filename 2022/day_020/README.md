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
| `lanjian/day_20 input-lanjian` | 137.1 ± 1.8 | 135.1 | 141.7 | 1.33 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 139.2 ± 1.7 | 136.3 | 143.2 | 1.35 ± 0.02 |
| `lanjian/day_20 input-pting` | 136.9 ± 1.7 | 134.5 | 140.2 | 1.32 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 104.7 ± 1.9 | 102.6 | 108.7 | 1.01 ± 0.02 |
| `mattcl-solver/aoc run 20 input-mattcl` | 105.4 ± 3.5 | 102.8 | 120.1 | 1.02 ± 0.04 |
| `mattcl-solver/aoc run 20 input-pting` | 103.4 ± 0.9 | 102.3 | 105.7 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8140.6 ± 121.7 | 8003.9 | 8237.4 | 78.70 ± 1.37 |
| `python pting/day20/day20.py input-mattcl` | 7970.8 ± 149.0 | 7829.1 | 8126.1 | 77.06 ± 1.60 |
| `python pting/day20/day20.py input-pting` | 7979.1 ± 132.3 | 7867.8 | 8125.4 | 77.14 ± 1.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
