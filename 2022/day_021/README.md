# Day 21 benchmarks

[link to problem](http://adventofcode.com/2022/day/21)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 21)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_21 input-lanjian` | 1.3 ± 0.1 | 1.2 | 1.8 | 1.18 ± 0.12 |
| `lanjian/day_21 input-mattcl` | 1.4 ± 0.1 | 1.2 | 3.8 | 1.22 ± 0.13 |
| `lanjian/day_21 input-pting` | 1.3 ± 0.1 | 1.2 | 4.4 | 1.18 ± 0.14 |
| `mattcl-solver/aoc run 21 input-lanjian` | 1.1 ± 0.1 | 1.0 | 1.5 | 1.00 ± 0.10 |
| `mattcl-solver/aoc run 21 input-mattcl` | 1.2 ± 0.1 | 1.0 | 4.0 | 1.03 ± 0.12 |
| `mattcl-solver/aoc run 21 input-pting` | 1.1 ± 0.1 | 1.0 | 3.7 | 1.00 |
| `python pting/day21/day21.py input-lanjian` | 429.4 ± 1.5 | 427.9 | 431.9 | 375.39 ± 30.84 |
| `python pting/day21/day21.py input-mattcl` | 434.2 ± 3.0 | 431.3 | 439.4 | 379.58 ± 31.26 |
| `python pting/day21/day21.py input-pting` | 429.7 ± 5.6 | 422.4 | 437.1 | 375.65 ± 31.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>43699799094202</pre>|<pre>3375719472770</pre>|
|input-mattcl|<pre>49288254556480</pre>|<pre>3558714869436</pre>|
|input-pting|<pre>85616733059734</pre>|<pre>3560324848168</pre>|
