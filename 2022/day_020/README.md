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
| `lanjian/day_20 input-lanjian` | 146.7 ± 1.3 | 144.8 | 148.5 | 1.41 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 147.2 ± 1.1 | 145.5 | 149.5 | 1.42 ± 0.01 |
| `lanjian/day_20 input-pting` | 147.2 ± 0.9 | 146.1 | 149.6 | 1.42 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 104.5 ± 0.7 | 103.5 | 106.7 | 1.01 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.8 ± 3.0 | 103.1 | 119.4 | 1.01 ± 0.03 |
| `mattcl-solver/aoc run 20 input-pting` | 103.9 ± 0.7 | 103.0 | 106.1 | 1.00 |
| `python pting/day20/day20.py input-lanjian` | 8128.9 ± 118.8 | 8049.3 | 8265.5 | 78.24 ± 1.26 |
| `python pting/day20/day20.py input-mattcl` | 7892.8 ± 11.0 | 7880.6 | 7902.0 | 75.97 ± 0.52 |
| `python pting/day20/day20.py input-pting` | 8012.2 ± 88.9 | 7911.3 | 8079.3 | 77.12 ± 1.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
