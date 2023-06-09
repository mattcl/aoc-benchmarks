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
| `lanjian/day_20 input-lanjian` | 136.4 ± 1.4 | 134.9 | 141.2 | 1.18 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 135.9 ± 1.1 | 134.5 | 139.6 | 1.18 ± 0.01 |
| `lanjian/day_20 input-pting` | 134.9 ± 1.0 | 133.6 | 137.9 | 1.17 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 115.3 ± 0.6 | 114.5 | 117.1 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 115.5 ± 0.7 | 114.6 | 117.3 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 115.2 ± 0.7 | 114.6 | 117.3 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 10286.3 ± 40.2 | 10252.0 | 10330.6 | 89.26 ± 0.63 |
| `python pting/day20/day20.py input-mattcl` | 10190.1 ± 40.4 | 10162.0 | 10236.4 | 88.42 ± 0.63 |
| `python pting/day20/day20.py input-pting` | 10275.3 ± 63.3 | 10212.0 | 10338.5 | 89.16 ± 0.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
