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
| `lanjian/day_20 input-lanjian` | 139.5 ± 1.4 | 137.6 | 143.9 | 1.35 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 137.8 ± 2.1 | 135.5 | 146.0 | 1.34 ± 0.02 |
| `lanjian/day_20 input-pting` | 138.5 ± 1.1 | 136.8 | 140.6 | 1.34 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.2 ± 0.5 | 102.5 | 104.4 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.5 ± 1.0 | 102.4 | 107.2 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 103.7 ± 1.4 | 102.5 | 110.0 | 1.01 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8010.9 ± 58.4 | 7968.9 | 8077.5 | 77.62 ± 0.69 |
| `python pting/day20/day20.py input-mattcl` | 7795.1 ± 59.9 | 7727.5 | 7841.6 | 75.53 ± 0.70 |
| `python pting/day20/day20.py input-pting` | 8195.5 ± 361.4 | 7959.9 | 8611.6 | 79.41 ± 3.53 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
