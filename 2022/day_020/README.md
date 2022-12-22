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
| `lanjian/day_20 input-lanjian` | 137.3 ± 0.9 | 136.1 | 139.8 | 1.33 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 137.8 ± 2.0 | 136.0 | 145.4 | 1.33 ± 0.02 |
| `lanjian/day_20 input-pting` | 137.8 ± 1.7 | 135.3 | 142.3 | 1.33 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.8 ± 0.6 | 103.2 | 106.1 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.4 ± 0.7 | 102.6 | 104.9 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 103.4 ± 0.6 | 102.6 | 106.0 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8058.6 ± 75.9 | 7981.7 | 8133.5 | 77.94 ± 0.86 |
| `python pting/day20/day20.py input-mattcl` | 7918.3 ± 47.0 | 7871.9 | 7965.9 | 76.59 ± 0.64 |
| `python pting/day20/day20.py input-pting` | 7999.0 ± 44.1 | 7949.6 | 8034.4 | 77.37 ± 0.62 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
