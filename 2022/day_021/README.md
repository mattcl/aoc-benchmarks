# Day 21 benchmarks

[link to problem](http://adventofcode.com/2022/day/21)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 21)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 21 input-lanjian` | 1.1 ± 0.1 | 1.0 | 2.1 | 1.00 |
| `mattcl-solver/aoc run 21 input-mattcl` | 1.2 ± 0.1 | 1.0 | 3.7 | 1.02 ± 0.12 |
| `mattcl-solver/aoc run 21 input-pting` | 1.1 ± 0.1 | 1.0 | 4.0 | 1.00 ± 0.11 |
| `python pting/day21/day21.py input-lanjian` | 434.9 ± 1.7 | 432.4 | 437.5 | 382.93 ± 26.39 |
| `python pting/day21/day21.py input-mattcl` | 441.3 ± 1.7 | 437.9 | 442.6 | 388.55 ± 26.78 |
| `python pting/day21/day21.py input-pting` | 433.7 ± 3.2 | 428.3 | 437.4 | 381.90 ± 26.43 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>43699799094202</pre>|<pre>3375719472770</pre>|
|input-mattcl|<pre>49288254556480</pre>|<pre>3558714869436</pre>|
|input-pting|<pre>85616733059734</pre>|<pre>3560324848168</pre>|
