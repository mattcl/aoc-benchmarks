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
| `lanjian/day_20 input-lanjian` | 137.4 ± 1.3 | 135.9 | 140.6 | 1.32 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 137.4 ± 0.8 | 136.1 | 138.8 | 1.32 ± 0.01 |
| `lanjian/day_20 input-pting` | 137.1 ± 1.0 | 135.5 | 139.2 | 1.32 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.7 ± 0.6 | 102.9 | 105.6 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.9 ± 0.8 | 102.9 | 106.3 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 103.7 ± 0.9 | 102.7 | 106.5 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8099.9 ± 87.9 | 8030.4 | 8198.7 | 78.09 ± 0.98 |
| `python pting/day20/day20.py input-mattcl` | 7873.5 ± 43.4 | 7823.4 | 7900.5 | 75.90 ± 0.63 |
| `python pting/day20/day20.py input-pting` | 8002.9 ± 84.9 | 7932.0 | 8097.0 | 77.15 ± 0.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
