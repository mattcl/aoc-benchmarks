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
| `lanjian/day_17 input-lanjian` | 1.3 ± 0.1 | 1.2 | 3.1 | 1.03 ± 0.10 |
| `lanjian/day_17 input-mattcl` | 1.3 ± 0.1 | 1.2 | 3.9 | 1.04 ± 0.10 |
| `lanjian/day_17 input-pting` | 1.3 ± 0.1 | 1.2 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 17 input-lanjian` | 1.7 ± 0.1 | 1.5 | 3.4 | 1.32 ± 0.12 |
| `mattcl-solver/aoc run 17 input-mattcl` | 1.7 ± 0.1 | 1.5 | 3.9 | 1.33 ± 0.13 |
| `mattcl-solver/aoc run 17 input-pting` | 1.7 ± 0.1 | 1.5 | 3.6 | 1.32 ± 0.13 |
| `python pting/day17/day17.py input-lanjian` | 52280.5 ± 27.1 | 52262.8 | 52311.6 | 40515.78 ± 2750.02 |
| `python pting/day17/day17.py input-mattcl` | 54533.0 ± 220.5 | 54315.3 | 54756.2 | 42261.42 ± 2873.51 |
| `python pting/day17/day17.py input-pting` | 52066.2 ± 66.7 | 52014.8 | 52141.6 | 40349.71 ± 2739.16 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3083</pre>|<pre>1532183908048</pre>|
|input-mattcl|<pre>3166</pre>|<pre>1577207977186</pre>|
|input-pting|<pre>3135</pre>|<pre>1569054441243</pre>|
