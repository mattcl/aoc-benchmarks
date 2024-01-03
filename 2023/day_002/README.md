# Day 2 benchmarks

[link to problem](https://adventofcode.com/2023/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [aspidites](https://github.com/aspidites/aoc2023) (haskell)
- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.00 ± 0.33 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.6 | 1.01 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.31 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.1 | 1.05 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.05 ± 0.30 |
| lanjian | input-aspidites | 0.9 ± 0.1 | 0.1 | 1.3 | 1.05 ± 0.29 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.4 | 1.08 ± 0.28 |
| mattcl | input-aspidites | 0.9 ± 0.1 | 0.5 | 1.0 | 1.08 ± 0.28 |
| mattcl-ts | input-lanjian | 11.0 ± 0.4 | 9.6 | 12.1 | 13.11 ± 2.94 |
| mattcl-ts | input-mattcl | 11.0 ± 0.4 | 10.0 | 11.8 | 13.18 ± 2.95 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 9.7 | 11.8 | 13.20 ± 2.96 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 10.1 | 12.2 | 13.25 ± 2.96 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 10.1 | 11.9 | 13.27 ± 2.96 |
| mikofo | input-lanjian | 11.3 ± 0.4 | 10.3 | 12.2 | 13.45 ± 3.00 |
| mikofo | input-mattcl | 11.3 ± 0.3 | 10.2 | 12.6 | 13.48 ± 3.01 |
| mikofo | input-aspidites | 11.3 ± 0.4 | 10.2 | 12.4 | 13.50 ± 3.01 |
| mikofo | input-chancalan | 11.3 ± 0.3 | 10.5 | 12.2 | 13.50 ± 3.00 |
| mikofo | input-kcen | 11.3 ± 0.3 | 10.2 | 12.0 | 13.53 ± 3.01 |
| aspidites | input-kcen | 12.6 ± 0.4 | 11.6 | 14.1 | 15.11 ± 3.38 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.4 | 13.8 | 15.16 ± 3.40 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.5 | 14.5 | 15.22 ± 3.41 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.4 | 14.8 | 15.25 ± 3.43 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.5 | 14.3 | 15.27 ± 3.42 |
| pting | input-lanjian | 14.5 ± 0.7 | 13.2 | 17.7 | 17.30 ± 3.91 |
| mattcl-py | input-lanjian | 14.5 ± 0.5 | 13.5 | 17.8 | 17.33 ± 3.87 |
| mattcl-py | input-aspidites | 14.5 ± 0.5 | 13.7 | 17.2 | 17.34 ± 3.88 |
| pting | input-kcen | 14.5 ± 0.6 | 13.3 | 17.2 | 17.34 ± 3.90 |
| mattcl-py | input-chancalan | 14.5 ± 0.5 | 13.5 | 18.0 | 17.35 ± 3.89 |
| pting | input-aspidites | 14.5 ± 0.8 | 13.4 | 18.2 | 17.38 ± 3.95 |
| pting | input-mattcl | 14.6 ± 0.8 | 13.6 | 17.9 | 17.41 ± 3.95 |
| mattcl-py | input-kcen | 14.6 ± 0.7 | 13.3 | 18.2 | 17.41 ± 3.94 |
| mattcl-py | input-mattcl | 14.6 ± 0.6 | 13.3 | 17.6 | 17.42 ± 3.93 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 14.1 | 18.3 | 17.97 ± 4.03 |
| chancalan | input-aspidites | 15.1 ± 0.7 | 13.9 | 18.9 | 18.01 ± 4.06 |
| chancalan | input-kcen | 15.1 ± 0.5 | 14.1 | 17.5 | 18.01 ± 4.02 |
| chancalan | input-mattcl | 15.2 ± 0.8 | 14.0 | 18.7 | 18.12 ± 4.12 |
| chancalan | input-lanjian | 15.2 ± 0.7 | 14.0 | 18.5 | 18.15 ± 4.09 |
| pting | input-chancalan | 15.2 ± 6.8 | 13.1 | 87.8 | 18.21 ± 9.08 |
| kcen | input-aspidites | 15.3 ± 0.5 | 14.0 | 18.1 | 18.25 ± 4.07 |
| kcen | input-lanjian | 15.3 ± 0.6 | 14.4 | 18.4 | 18.28 ± 4.10 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.1 | 18.5 | 18.37 ± 4.13 |
| kcen | input-mattcl | 15.4 ± 0.7 | 14.1 | 19.0 | 18.39 ± 4.15 |
| kcen | input-chancalan | 15.8 ± 2.8 | 14.4 | 46.4 | 18.82 ± 5.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-mikofo|<pre>2162</pre>|<pre>72513</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|