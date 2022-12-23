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
| `lanjian/day_20 input-lanjian` | 137.5 ± 1.3 | 135.6 | 139.7 | 1.34 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 136.7 ± 1.1 | 135.1 | 139.6 | 1.33 ± 0.01 |
| `lanjian/day_20 input-pting` | 136.9 ± 1.9 | 135.1 | 143.5 | 1.33 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.0 ± 0.5 | 102.2 | 104.3 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 102.7 ± 0.4 | 102.2 | 103.8 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 103.2 ± 0.6 | 102.2 | 105.2 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 7936.6 ± 31.1 | 7906.5 | 7968.6 | 77.26 ± 0.45 |
| `python pting/day20/day20.py input-mattcl` | 7960.0 ± 35.2 | 7932.2 | 7999.7 | 77.49 ± 0.48 |
| `python pting/day20/day20.py input-pting` | 7939.7 ± 27.9 | 7911.2 | 7966.9 | 77.29 ± 0.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
