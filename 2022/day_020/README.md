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
| `lanjian/day_20 input-lanjian` | 136.6 ± 0.7 | 135.6 | 138.1 | 1.32 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 137.0 ± 0.8 | 135.9 | 138.8 | 1.33 ± 0.01 |
| `lanjian/day_20 input-pting` | 136.5 ± 1.2 | 135.1 | 138.9 | 1.32 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.7 ± 0.9 | 102.7 | 106.7 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.7 ± 0.9 | 102.7 | 106.8 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 103.2 ± 0.6 | 102.3 | 104.3 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 7989.5 ± 44.7 | 7940.5 | 8028.0 | 77.38 ± 0.60 |
| `python pting/day20/day20.py input-mattcl` | 8027.5 ± 279.8 | 7812.6 | 8343.9 | 77.75 ± 2.74 |
| `python pting/day20/day20.py input-pting` | 7948.9 ± 17.4 | 7931.7 | 7966.6 | 76.99 ± 0.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
