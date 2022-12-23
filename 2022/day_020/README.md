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
| `lanjian/day_20 input-lanjian` | 140.0 ± 1.3 | 138.2 | 142.6 | 1.34 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 139.9 ± 2.3 | 137.2 | 146.6 | 1.34 ± 0.03 |
| `lanjian/day_20 input-pting` | 139.6 ± 1.6 | 137.4 | 144.3 | 1.34 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 104.8 ± 1.6 | 103.3 | 110.0 | 1.00 ± 0.02 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.7 ± 1.1 | 103.2 | 107.3 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 104.5 ± 1.0 | 102.9 | 108.0 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8170.6 ± 50.8 | 8129.1 | 8227.3 | 78.18 ± 0.87 |
| `python pting/day20/day20.py input-mattcl` | 8077.0 ± 115.0 | 7970.7 | 8199.0 | 77.28 ± 1.31 |
| `python pting/day20/day20.py input-pting` | 8124.2 ± 93.2 | 8034.3 | 8220.4 | 77.73 ± 1.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
