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
| `lanjian/day_20 input-lanjian` | 136.8 ± 0.8 | 135.2 | 138.3 | 1.32 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 137.6 ± 1.1 | 136.3 | 140.0 | 1.33 ± 0.01 |
| `lanjian/day_20 input-pting` | 136.7 ± 0.9 | 135.3 | 139.4 | 1.32 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.6 ± 0.5 | 102.9 | 105.5 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.0 ± 0.9 | 102.9 | 106.9 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 104.2 ± 0.8 | 103.1 | 107.4 | 1.01 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8164.0 ± 246.1 | 8011.9 | 8447.8 | 78.82 ± 2.41 |
| `python pting/day20/day20.py input-mattcl` | 7937.9 ± 82.0 | 7881.2 | 8031.9 | 76.64 ± 0.89 |
| `python pting/day20/day20.py input-pting` | 7951.5 ± 93.3 | 7843.9 | 8011.2 | 76.77 ± 0.98 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
