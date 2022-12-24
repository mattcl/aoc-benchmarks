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
| `lanjian/day_20 input-lanjian` | 137.3 ± 1.4 | 135.6 | 141.4 | 1.33 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 139.2 ± 3.1 | 136.4 | 150.0 | 1.35 ± 0.03 |
| `lanjian/day_20 input-pting` | 137.5 ± 1.1 | 136.1 | 140.0 | 1.33 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.3 ± 0.4 | 102.7 | 104.3 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.9 ± 1.0 | 102.6 | 106.7 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 104.3 ± 1.1 | 103.1 | 107.0 | 1.01 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 7998.3 ± 106.0 | 7895.8 | 8107.5 | 77.45 ± 1.06 |
| `python pting/day20/day20.py input-mattcl` | 7898.1 ± 43.8 | 7847.7 | 7927.2 | 76.48 ± 0.51 |
| `python pting/day20/day20.py input-pting` | 8041.3 ± 91.1 | 7979.0 | 8145.9 | 77.86 ± 0.93 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
