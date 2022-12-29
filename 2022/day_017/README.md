# Day 17 benchmarks

[link to problem](http://adventofcode.com/2022/day/17)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 17)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 17 input-lanjian` | 1.7 ± 0.1 | 1.6 | 4.9 | 1.02 ± 0.09 |
| `mattcl-solver/aoc run 17 input-mattcl` | 1.7 ± 0.1 | 1.6 | 2.3 | 1.04 ± 0.08 |
| `mattcl-solver/aoc run 17 input-pting` | 1.7 ± 0.1 | 1.5 | 2.2 | 1.00 |
| `python pting/day17/day17.py input-lanjian` | 52470.8 ± 138.3 | 52355.4 | 52624.1 | 31288.85 ± 1573.70 |
| `python pting/day17/day17.py input-mattcl` | 54229.8 ± 46.9 | 54175.7 | 54257.5 | 32337.78 ± 1624.46 |
| `python pting/day17/day17.py input-pting` | 52073.2 ± 75.1 | 51999.8 | 52149.9 | 31051.74 ± 1560.27 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>3083</pre>|<pre>1532183908048</pre>|
|input-mattcl|<pre>3166</pre>|<pre>1577207977186</pre>|
|input-pting|<pre>3135</pre>|<pre>1569054441243</pre>|
