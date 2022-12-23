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
| `lanjian/day_20 input-lanjian` | 137.2 ± 1.5 | 135.1 | 140.5 | 1.33 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 137.6 ± 1.6 | 135.3 | 141.1 | 1.34 ± 0.02 |
| `lanjian/day_20 input-pting` | 137.5 ± 1.7 | 135.4 | 141.8 | 1.33 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.1 ± 0.6 | 102.4 | 104.7 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.5 ± 1.2 | 102.7 | 109.0 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 103.3 ± 0.7 | 102.3 | 105.7 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8093.1 ± 237.9 | 7947.7 | 8367.7 | 78.52 ± 2.35 |
| `python pting/day20/day20.py input-mattcl` | 8056.8 ± 83.9 | 7969.6 | 8137.0 | 78.16 ± 0.92 |
| `python pting/day20/day20.py input-pting` | 8120.7 ± 201.5 | 7947.9 | 8342.1 | 78.78 ± 2.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
