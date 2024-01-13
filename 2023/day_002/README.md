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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.5 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.28 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.28 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.31 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.27 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.28 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.1 | 1.03 ± 0.27 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.26 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.28 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 9.8 | 12.1 | 12.06 ± 2.46 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 10.2 | 11.9 | 12.10 ± 2.47 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 10.0 | 11.8 | 12.10 ± 2.47 |
| mattcl-ts | input-chancalan | 11.1 ± 0.4 | 10.0 | 12.0 | 12.12 ± 2.47 |
| mattcl-ts | input-lanjian | 11.2 ± 0.4 | 10.0 | 11.9 | 12.18 ± 2.47 |
| mikofo | input-kcen | 11.3 ± 0.3 | 10.3 | 12.6 | 12.29 ± 2.49 |
| mikofo | input-lanjian | 11.3 ± 0.3 | 10.2 | 12.7 | 12.32 ± 2.50 |
| mikofo | input-mattcl | 11.4 ± 0.3 | 10.4 | 12.2 | 12.39 ± 2.51 |
| mikofo | input-aspidites | 11.4 ± 0.3 | 10.6 | 12.2 | 12.39 ± 2.51 |
| mikofo | input-chancalan | 11.8 ± 5.8 | 10.3 | 93.5 | 12.82 ± 6.83 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.7 | 14.2 | 13.80 ± 2.82 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.7 | 14.1 | 13.91 ± 2.84 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.9 | 14.3 | 13.98 ± 2.85 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 11.4 | 14.6 | 13.99 ± 2.87 |
| aspidites | input-mattcl | 13.0 ± 3.6 | 11.1 | 59.6 | 14.13 ± 4.85 |
| pting | input-kcen | 14.5 ± 0.6 | 13.2 | 17.9 | 15.80 ± 3.24 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.6 | 18.3 | 15.82 ± 3.24 |
| pting | input-chancalan | 14.5 ± 0.7 | 13.3 | 17.7 | 15.84 ± 3.27 |
| pting | input-aspidites | 14.6 ± 0.7 | 13.3 | 17.7 | 15.84 ± 3.27 |
| mattcl-py | input-kcen | 14.6 ± 0.5 | 13.4 | 17.8 | 15.86 ± 3.24 |
| mattcl-py | input-aspidites | 14.6 ± 0.6 | 13.3 | 17.8 | 15.90 ± 3.27 |
| pting | input-lanjian | 14.6 ± 0.7 | 13.7 | 17.6 | 15.93 ± 3.29 |
| mattcl-py | input-chancalan | 14.6 ± 0.7 | 13.5 | 17.9 | 15.94 ± 3.29 |
| mattcl-py | input-mattcl | 14.7 ± 0.6 | 13.8 | 17.3 | 15.96 ± 3.26 |
| pting | input-mattcl | 14.7 ± 0.8 | 13.5 | 17.9 | 16.02 ± 3.33 |
| chancalan | input-lanjian | 15.1 ± 0.5 | 13.9 | 17.9 | 16.43 ± 3.35 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 13.8 | 17.9 | 16.46 ± 3.36 |
| chancalan | input-chancalan | 15.1 ± 0.6 | 13.8 | 17.9 | 16.46 ± 3.36 |
| chancalan | input-kcen | 15.2 ± 0.7 | 14.1 | 18.5 | 16.51 ± 3.40 |
| chancalan | input-aspidites | 15.2 ± 0.7 | 14.2 | 18.3 | 16.54 ± 3.40 |
| kcen | input-lanjian | 15.3 ± 0.7 | 14.1 | 18.9 | 16.69 ± 3.43 |
| kcen | input-chancalan | 15.4 ± 0.7 | 14.1 | 18.3 | 16.73 ± 3.43 |
| kcen | input-aspidites | 15.4 ± 0.7 | 14.1 | 19.2 | 16.74 ± 3.44 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.3 | 18.9 | 16.78 ± 3.43 |
| kcen | input-mattcl | 15.5 ± 0.7 | 14.2 | 19.0 | 16.82 ± 3.46 |


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