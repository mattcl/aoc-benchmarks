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
| `lanjian/day_20 input-lanjian` | 137.4 ± 0.9 | 135.6 | 139.0 | 1.32 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 138.2 ± 1.0 | 136.8 | 140.4 | 1.33 ± 0.01 |
| `lanjian/day_20 input-pting` | 137.4 ± 0.8 | 135.7 | 139.1 | 1.32 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.7 ± 0.4 | 102.8 | 105.1 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.0 ± 0.6 | 103.1 | 105.5 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 104.8 ± 1.0 | 103.6 | 107.7 | 1.01 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8039.6 ± 157.7 | 7924.1 | 8219.2 | 77.52 ± 1.56 |
| `python pting/day20/day20.py input-mattcl` | 7914.0 ± 61.0 | 7877.9 | 7984.5 | 76.31 ± 0.67 |
| `python pting/day20/day20.py input-pting` | 8000.1 ± 161.9 | 7870.2 | 8181.4 | 77.14 ± 1.59 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
