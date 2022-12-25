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
| `lanjian/day_20 input-lanjian` | 139.9 ± 1.9 | 137.4 | 145.3 | 1.35 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 139.2 ± 1.7 | 136.8 | 143.2 | 1.35 ± 0.02 |
| `lanjian/day_20 input-pting` | 137.9 ± 1.6 | 135.3 | 143.0 | 1.34 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 104.3 ± 1.4 | 103.2 | 111.0 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.1 ± 0.8 | 102.9 | 106.1 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 103.3 ± 0.5 | 102.5 | 104.5 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8011.1 ± 79.8 | 7939.1 | 8096.9 | 77.57 ± 0.87 |
| `python pting/day20/day20.py input-mattcl` | 7912.1 ± 60.0 | 7870.9 | 7981.0 | 76.61 ± 0.71 |
| `python pting/day20/day20.py input-pting` | 8053.2 ± 127.4 | 7910.0 | 8154.2 | 77.98 ± 1.30 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
