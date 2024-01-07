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
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.5 | 1.00 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.3 | 1.01 ± 0.30 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.6 | 1.02 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.31 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.0 | 1.05 ± 0.29 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.4 | 1.6 | 1.06 ± 0.30 |
| mattcl-ts | input-kcen | 11.0 ± 0.4 | 9.9 | 12.1 | 13.02 ± 2.99 |
| mattcl-ts | input-lanjian | 11.1 ± 0.4 | 9.9 | 11.9 | 13.03 ± 2.99 |
| mattcl-ts | input-chancalan | 11.1 ± 0.4 | 9.7 | 12.1 | 13.04 ± 2.99 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 9.9 | 12.0 | 13.07 ± 2.99 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 10.0 | 11.8 | 13.10 ± 3.00 |
| mikofo | input-chancalan | 11.3 ± 0.3 | 10.4 | 12.0 | 13.27 ± 3.03 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.4 | 12.2 | 13.29 ± 3.04 |
| mikofo | input-lanjian | 11.3 ± 0.4 | 10.4 | 12.7 | 13.32 ± 3.05 |
| mikofo | input-kcen | 11.3 ± 0.3 | 10.4 | 12.5 | 13.34 ± 3.05 |
| mikofo | input-mattcl | 11.3 ± 0.3 | 10.6 | 12.0 | 13.37 ± 3.05 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.7 | 14.0 | 14.91 ± 3.43 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.7 | 14.4 | 15.01 ± 3.46 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.8 | 14.2 | 15.01 ± 3.45 |
| aspidites | input-kcen | 12.8 ± 4.2 | 11.4 | 71.2 | 15.06 ± 6.01 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.8 | 14.3 | 15.09 ± 3.47 |
| pting | input-lanjian | 14.4 ± 0.5 | 13.6 | 16.8 | 17.00 ± 3.90 |
| pting | input-chancalan | 14.4 ± 0.5 | 13.6 | 17.0 | 17.02 ± 3.90 |
| pting | input-aspidites | 14.5 ± 0.6 | 13.5 | 18.1 | 17.10 ± 3.95 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.3 | 18.1 | 17.17 ± 3.96 |
| pting | input-mattcl | 14.6 ± 0.7 | 13.3 | 18.1 | 17.19 ± 3.99 |
| mattcl-py | input-lanjian | 14.6 ± 0.7 | 13.4 | 18.2 | 17.19 ± 3.98 |
| mattcl-py | input-kcen | 14.6 ± 0.6 | 13.6 | 17.6 | 17.21 ± 3.96 |
| mattcl-py | input-mattcl | 14.6 ± 0.6 | 13.5 | 17.9 | 17.23 ± 3.97 |
| mattcl-py | input-aspidites | 14.6 ± 0.6 | 13.6 | 19.8 | 17.26 ± 3.98 |
| pting | input-kcen | 14.7 ± 0.8 | 13.6 | 18.1 | 17.27 ± 4.03 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 14.0 | 18.3 | 17.72 ± 4.08 |
| chancalan | input-chancalan | 15.1 ± 0.6 | 13.8 | 17.9 | 17.75 ± 4.08 |
| chancalan | input-aspidites | 15.1 ± 0.5 | 14.1 | 18.3 | 17.75 ± 4.08 |
| chancalan | input-mattcl | 15.1 ± 0.7 | 13.8 | 18.2 | 17.79 ± 4.11 |
| chancalan | input-kcen | 15.1 ± 0.7 | 13.8 | 18.3 | 17.81 ± 4.12 |
| kcen | input-chancalan | 15.3 ± 0.7 | 14.4 | 19.0 | 18.09 ± 4.19 |
| kcen | input-mattcl | 15.3 ± 0.5 | 14.3 | 18.1 | 18.09 ± 4.15 |
| kcen | input-aspidites | 15.4 ± 0.5 | 14.2 | 18.5 | 18.12 ± 4.15 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.5 | 18.4 | 18.16 ± 4.18 |
| kcen | input-lanjian | 15.4 ± 0.8 | 14.5 | 18.5 | 18.18 ± 4.22 |


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