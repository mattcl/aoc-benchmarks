# Day 17 benchmarks

[link to problem](http://adventofcode.com/2022/day/17)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 17)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_17 input-lanjian` | 1.3 ± 0.1 | 1.2 | 3.2 | 1.03 ± 0.11 |
| `lanjian/day_17 input-mattcl` | 1.3 ± 0.1 | 1.2 | 2.1 | 1.05 ± 0.10 |
| `lanjian/day_17 input-pting` | 1.3 ± 0.1 | 1.2 | 3.7 | 1.00 |
| `mattcl-solver/aoc run 17 input-lanjian` | 1.7 ± 0.1 | 1.5 | 3.3 | 1.32 ± 0.13 |
| `mattcl-solver/aoc run 17 input-mattcl` | 1.7 ± 0.1 | 1.6 | 3.7 | 1.34 ± 0.13 |
| `mattcl-solver/aoc run 17 input-pting` | 1.7 ± 0.1 | 1.5 | 2.2 | 1.30 ± 0.12 |
| `python pting/day17/day17.py input-lanjian` | 52410.6 ± 99.0 | 52307.1 | 52504.5 | 40815.72 ± 3264.37 |
| `python pting/day17/day17.py input-mattcl` | 54356.2 ± 133.2 | 54230.3 | 54495.7 | 42330.87 ± 3386.19 |
| `python pting/day17/day17.py input-pting` | 52078.1 ± 385.9 | 51822.1 | 52522.0 | 40556.80 ± 3256.66 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3083</pre>|<pre>1532183908048</pre>|
|input-mattcl|<pre>3166</pre>|<pre>1577207977186</pre>|
|input-pting|<pre>3135</pre>|<pre>1569054441243</pre>|
