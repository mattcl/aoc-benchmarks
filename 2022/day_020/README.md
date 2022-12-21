# Day 20 benchmarks

[link to problem](http://adventofcode.com/2022/day/20)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 20)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 20 input-lanjian` | 103.9 ± 0.4 | 103.3 | 104.9 | 1.00 |
| `mattcl-solver/aoc run 20 input-mattcl` | 104.4 ± 0.6 | 103.6 | 105.8 | 1.00 ± 0.01 |
| `mattcl-solver/aoc run 20 input-pting` | 104.0 ± 0.8 | 103.0 | 106.2 | 1.00 ± 0.01 |
| `python pting/day20/day20.py input-lanjian` | 8056.0 ± 56.7 | 8010.9 | 8119.6 | 77.52 ± 0.63 |
| `python pting/day20/day20.py input-mattcl` | 7929.6 ± 13.1 | 7914.8 | 7939.7 | 76.30 ± 0.34 |
| `python pting/day20/day20.py input-pting` | 8155.6 ± 187.8 | 8017.9 | 8369.5 | 78.48 ± 1.84 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>9866</pre>|<pre>12374299815791</pre>|
|input-mattcl|<pre>13967</pre>|<pre>1790365671518</pre>|
|input-pting|<pre>7278</pre>|<pre>14375678667089</pre>|
