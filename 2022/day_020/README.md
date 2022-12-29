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
| `lanjian/day_20 input-lanjian` | 146.4 ± 0.8 | 145.0 | 148.0 | 1.42 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 145.9 ± 0.7 | 144.5 | 147.1 | 1.41 ± 0.01 |
| `lanjian/day_20 input-pting` | 146.4 ± 1.3 | 144.2 | 149.5 | 1.42 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.8 ± 0.6 | 103.0 | 105.2 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.4 ± 0.7 | 102.6 | 105.5 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 103.5 ± 0.6 | 102.8 | 105.4 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8188.0 ± 160.6 | 8002.9 | 8291.5 | 79.16 ± 1.65 |
| `python pting/day20/day20.py input-mattcl` | 7898.4 ± 16.9 | 7886.3 | 7917.7 | 76.36 ± 0.57 |
| `python pting/day20/day20.py input-pting` | 8010.8 ± 43.1 | 7985.8 | 8060.5 | 77.44 ± 0.70 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
