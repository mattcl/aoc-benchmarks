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
| `lanjian/day_20 input-lanjian` | 147.8 ± 1.2 | 146.0 | 150.6 | 1.42 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 147.1 ± 1.3 | 145.2 | 150.1 | 1.42 ± 0.02 |
| `lanjian/day_20 input-pting` | 147.3 ± 1.1 | 145.2 | 149.7 | 1.42 ± 0.02 |
| `mattcl-solver/aoc run 20 input-lanjian` | 104.2 ± 0.7 | 103.0 | 106.5 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.9 ± 0.9 | 103.0 | 106.0 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 104.5 ± 0.8 | 103.4 | 106.4 | 1.01 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8043.1 ± 96.6 | 7931.9 | 8106.7 | 77.41 ± 1.13 |
| `python pting/day20/day20.py input-mattcl` | 8295.7 ± 46.4 | 8259.1 | 8347.9 | 79.84 ± 0.80 |
| `python pting/day20/day20.py input-pting` | 7997.3 ± 107.4 | 7924.0 | 8120.6 | 76.97 ± 1.21 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
