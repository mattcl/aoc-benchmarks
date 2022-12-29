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
| `lanjian/day_20 input-lanjian` | 136.6 ± 0.8 | 135.2 | 138.5 | 1.32 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 137.0 ± 0.8 | 135.7 | 139.2 | 1.32 ± 0.01 |
| `lanjian/day_20 input-pting` | 136.7 ± 1.0 | 135.4 | 139.5 | 1.32 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.4 ± 0.5 | 102.9 | 104.6 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.9 ± 1.7 | 102.9 | 112.3 | 1.00 ± 0.02 |
| `mattcl-solver/aoc run 20 input-pting` | 103.7 ± 0.9 | 102.7 | 105.9 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8111.0 ± 118.0 | 7999.4 | 8234.5 | 78.42 ± 1.21 |
| `python pting/day20/day20.py input-mattcl` | 7918.3 ± 51.2 | 7882.5 | 7977.0 | 76.56 ± 0.63 |
| `python pting/day20/day20.py input-pting` | 8092.1 ± 92.7 | 7987.9 | 8165.6 | 78.24 ± 0.98 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
