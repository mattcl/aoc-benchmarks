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
| `lanjian/day_20 input-lanjian` | 138.9 ± 1.1 | 137.2 | 141.1 | 1.34 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 138.6 ± 1.3 | 136.4 | 141.6 | 1.34 ± 0.01 |
| `lanjian/day_20 input-pting` | 137.7 ± 1.1 | 136.1 | 140.0 | 1.33 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.9 ± 0.5 | 103.1 | 105.6 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.0 ± 1.1 | 102.7 | 107.4 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 103.8 ± 0.6 | 103.0 | 105.2 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8079.2 ± 107.0 | 8012.4 | 8202.7 | 77.85 ± 1.14 |
| `python pting/day20/day20.py input-mattcl` | 8012.3 ± 124.4 | 7898.6 | 8145.1 | 77.21 ± 1.29 |
| `python pting/day20/day20.py input-pting` | 8040.3 ± 54.6 | 8005.3 | 8103.2 | 77.48 ± 0.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
