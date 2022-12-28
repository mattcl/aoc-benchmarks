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
| `lanjian/day_20 input-lanjian` | 146.3 ± 0.9 | 145.1 | 148.4 | 1.41 ± 0.01 |
| `lanjian/day_20 input-mattcl` | 146.2 ± 1.0 | 145.2 | 148.6 | 1.41 ± 0.01 |
| `lanjian/day_20 input-pting` | 146.6 ± 1.2 | 145.2 | 150.5 | 1.42 ± 0.01 |
| `mattcl-solver/aoc run 20 input-lanjian` | 103.7 ± 0.9 | 102.3 | 105.7 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-mattcl` | 103.6 ± 0.6 | 103.0 | 105.2 | 1.00 |
| `mattcl-solver/aoc run 20 input-pting` | 104.1 ± 0.5 | 103.2 | 105.1 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8424.7 ± 708.3 | 7996.2 | 9242.3 | 81.32 ± 6.85 |
| `python pting/day20/day20.py input-mattcl` | 8010.5 ± 72.6 | 7926.7 | 8054.3 | 77.32 ± 0.82 |
| `python pting/day20/day20.py input-pting` | 8062.0 ± 29.8 | 8029.1 | 8087.1 | 77.82 ± 0.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
