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
| `lanjian/day_17 input-lanjian` | 1.4 ± 0.1 | 1.3 | 1.9 | 1.00 |
| `lanjian/day_17 input-mattcl` | 1.5 ± 0.1 | 1.3 | 2.0 | 1.01 ± 0.10 |
| `lanjian/day_17 input-pting` | 1.4 ± 0.1 | 1.3 | 2.0 | 1.01 ± 0.12 |
| `mattcl-solver/aoc run 17 input-lanjian` | 1.8 ± 0.1 | 1.6 | 2.5 | 1.26 ± 0.11 |
| `mattcl-solver/aoc run 17 input-mattcl` | 1.8 ± 0.1 | 1.7 | 3.9 | 1.29 ± 0.13 |
| `mattcl-solver/aoc run 17 input-pting` | 1.8 ± 0.1 | 1.6 | 2.4 | 1.26 ± 0.12 |
| `python pting/day17/day17.py input-lanjian` | 70516.1 ± 22.0 | 70491.2 | 70532.8 | 49174.36 ± 3383.85 |
| `python pting/day17/day17.py input-mattcl` | 73234.9 ± 202.0 | 73075.7 | 73462.2 | 51070.33 ± 3517.11 |
| `python pting/day17/day17.py input-pting` | 70271.1 ± 238.2 | 70066.3 | 70532.5 | 49003.49 ± 3376.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3083</pre>|<pre>1532183908048</pre>|
|input-mattcl|<pre>3166</pre>|<pre>1577207977186</pre>|
|input-pting|<pre>3135</pre>|<pre>1569054441243</pre>|
