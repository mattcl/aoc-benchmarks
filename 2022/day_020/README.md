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
| `lanjian/day_20 input-lanjian` | 146.5 ± 1.1 | 144.9 | 149.0 | 1.41 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 146.6 ± 0.8 | 145.1 | 148.6 | 1.42 ± 0.01 |
| `lanjian/day_20 input-pting` | 145.9 ± 0.7 | 145.0 | 147.8 | 1.41 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.6 ± 0.6 | 102.8 | 105.5 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.3 ± 1.8 | 103.0 | 111.5 | 1.01 ± 0.02 |
| `mattcl-solver/aoc run 20 input-pting` | 104.1 ± 0.9 | 103.1 | 106.3 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8177.2 ± 78.5 | 8095.1 | 8251.4 | 78.95 ± 0.88 |
| `python pting/day20/day20.py input-mattcl` | 7949.4 ± 62.2 | 7880.7 | 8002.1 | 76.75 ± 0.74 |
| `python pting/day20/day20.py input-pting` | 8108.7 ± 116.3 | 7977.2 | 8198.1 | 78.29 ± 1.21 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
