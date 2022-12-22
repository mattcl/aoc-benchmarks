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
| `lanjian/day_20 input-lanjian` | 137.3 ± 1.7 | 135.7 | 142.4 | 1.26 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 138.4 ± 1.6 | 136.1 | 141.5 | 1.27 ± 0.02 |
| `lanjian/day_20 input-pting` | 137.7 ± 2.2 | 135.4 | 144.7 | 1.26 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 109.4 ± 0.6 | 108.5 | 111.5 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 109.5 ± 0.9 | 108.6 | 112.2 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 109.3 ± 1.2 | 108.3 | 113.8 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8220.7 ± 386.8 | 7934.4 | 8660.7 | 75.24 ± 3.63 |
| `python pting/day20/day20.py input-mattcl` | 7956.6 ± 175.2 | 7842.2 | 8158.3 | 72.82 ± 1.78 |
| `python pting/day20/day20.py input-pting` | 8001.3 ± 71.2 | 7950.2 | 8082.5 | 73.23 ± 1.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
