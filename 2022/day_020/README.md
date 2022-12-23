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
| `lanjian/day_20 input-lanjian` | 137.6 ± 1.5 | 136.0 | 142.7 | 1.34 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 137.0 ± 1.4 | 135.2 | 139.7 | 1.33 ± 0.02 |
| `lanjian/day_20 input-pting` | 136.5 ± 1.3 | 134.4 | 140.1 | 1.33 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.1 ± 0.7 | 102.3 | 104.6 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 102.9 ± 0.5 | 102.4 | 105.0 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 103.3 ± 0.8 | 102.2 | 105.7 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 7981.9 ± 83.2 | 7888.6 | 8048.5 | 77.54 ± 0.91 |
| `python pting/day20/day20.py input-mattcl` | 7910.3 ± 167.1 | 7804.4 | 8103.0 | 76.85 ± 1.67 |
| `python pting/day20/day20.py input-pting` | 7962.2 ± 36.5 | 7940.0 | 8004.4 | 77.35 ± 0.54 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
