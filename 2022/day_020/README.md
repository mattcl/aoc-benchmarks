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
| `lanjian/day_20 input-lanjian` | 138.8 ± 1.7 | 136.1 | 142.5 | 1.33 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 138.8 ± 1.3 | 136.8 | 141.4 | 1.33 ± 0.02 |
| `lanjian/day_20 input-pting` | 139.3 ± 1.3 | 137.7 | 142.6 | 1.34 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 104.4 ± 0.7 | 103.4 | 106.0 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.2 ± 0.7 | 103.2 | 106.9 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 104.7 ± 1.1 | 103.1 | 108.6 | 1.01 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8001.2 ± 27.8 | 7972.2 | 8027.5 | 76.82 ± 0.59 |
| `python pting/day20/day20.py input-mattcl` | 7986.7 ± 143.5 | 7851.1 | 8136.9 | 76.68 ± 1.48 |
| `python pting/day20/day20.py input-pting` | 8237.1 ± 400.4 | 7945.7 | 8693.7 | 79.08 ± 3.88 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
