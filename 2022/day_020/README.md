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
| `lanjian/day_20 input-lanjian` | 140.3 ± 1.3 | 138.2 | 142.7 | 1.27 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 138.8 ± 1.0 | 137.3 | 140.6 | 1.25 ± 0.02 |
| `lanjian/day_20 input-pting` | 139.0 ± 1.2 | 137.1 | 141.9 | 1.25 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 111.3 ± 1.2 | 110.2 | 114.8 | 1.00 ± 0.02 |
| `mattcl-solver/aoc run 20 input-mattcl` | 111.5 ± 1.4 | 109.6 | 115.5 | 1.01 ± 0.02 |
| `mattcl-solver/aoc run 20 input-pting` | 110.9 ± 1.4 | 109.1 | 115.5 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8076.6 ± 38.8 | 8047.7 | 8120.6 | 72.85 ± 0.97 |
| `python pting/day20/day20.py input-mattcl` | 8279.9 ± 191.9 | 8083.9 | 8467.3 | 74.69 ± 1.96 |
| `python pting/day20/day20.py input-pting` | 8183.9 ± 149.3 | 8069.5 | 8352.8 | 73.82 ± 1.63 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
