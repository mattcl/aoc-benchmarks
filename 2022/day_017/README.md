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
| `lanjian/day_17 input-lanjian` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.01 ± 0.08 |
| `lanjian/day_17 input-mattcl` | 1.3 ± 0.1 | 1.2 | 2.8 | 1.03 ± 0.08 |
| `lanjian/day_17 input-pting` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.00 |
| `mattcl-solver/aoc run 17 input-lanjian` | 1.7 ± 0.1 | 1.5 | 2.2 | 1.29 ± 0.10 |
| `mattcl-solver/aoc run 17 input-mattcl` | 1.7 ± 0.1 | 1.5 | 2.2 | 1.29 ± 0.10 |
| `mattcl-solver/aoc run 17 input-pting` | 1.6 ± 0.1 | 1.5 | 2.1 | 1.28 ± 0.10 |
| `python pting/day17/day17.py input-lanjian` | 52325.9 ± 53.0 | 52267.5 | 52371.0 | 40751.51 ± 2539.01 |
| `python pting/day17/day17.py input-mattcl` | 54249.1 ± 45.1 | 54208.5 | 54297.6 | 42249.27 ± 2632.21 |
| `python pting/day17/day17.py input-pting` | 52209.5 ± 132.7 | 52064.6 | 52325.0 | 40660.84 ± 2535.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3083</pre>|<pre>1532183908048</pre>|
|input-mattcl|<pre>3166</pre>|<pre>1577207977186</pre>|
|input-pting|<pre>3135</pre>|<pre>1569054441243</pre>|
