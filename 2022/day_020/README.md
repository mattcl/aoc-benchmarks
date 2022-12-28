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
| `lanjian/day_20 input-lanjian` | 146.4 ± 1.0 | 144.7 | 148.5 | 1.42 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 145.7 ± 1.0 | 144.4 | 148.2 | 1.41 ± 0.01 |
| `lanjian/day_20 input-pting` | 146.3 ± 1.3 | 145.0 | 149.1 | 1.42 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.4 ± 0.5 | 102.6 | 104.9 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.2 ± 0.5 | 102.2 | 104.6 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 103.7 ± 0.7 | 102.4 | 105.4 | 1.01 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8062.3 ± 119.9 | 7951.7 | 8189.8 | 78.15 ± 1.22 |
| `python pting/day20/day20.py input-mattcl` | 7926.2 ± 118.5 | 7857.5 | 8063.0 | 76.83 ± 1.20 |
| `python pting/day20/day20.py input-pting` | 8158.7 ± 256.6 | 7957.7 | 8447.7 | 79.09 ± 2.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
