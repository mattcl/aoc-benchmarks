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
| `lanjian/day_20 input-lanjian` | 137.6 ± 1.5 | 135.7 | 141.3 | 1.33 ± 0.02 |
| `lanjian/day_20 input-mattcl` | 137.6 ± 1.1 | 135.6 | 139.8 | 1.33 ± 0.01 |
| `lanjian/day_20 input-pting` | 137.8 ± 1.0 | 136.3 | 139.8 | 1.33 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.7 ± 0.8 | 102.5 | 105.5 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.7 ± 0.8 | 102.7 | 106.0 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 103.8 ± 0.7 | 102.8 | 105.8 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8010.2 ± 152.1 | 7907.5 | 8184.9 | 77.25 ± 1.59 |
| `python pting/day20/day20.py input-mattcl` | 8064.0 ± 323.3 | 7818.0 | 8430.2 | 77.77 ± 3.18 |
| `python pting/day20/day20.py input-pting` | 8035.3 ± 112.1 | 7968.0 | 8164.7 | 77.49 ± 1.24 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
