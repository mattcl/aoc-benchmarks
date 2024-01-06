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
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.5 | 1.00 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.01 ± 0.26 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.26 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.26 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.4 | 1.2 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.2 | 1.03 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.7 | 1.05 ± 0.25 |
| mattcl | input-aspidites | 1.0 ± 0.1 | 0.3 | 1.2 | 1.06 ± 0.24 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.2 | 1.06 ± 0.24 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 9.8 | 12.1 | 11.37 ± 2.17 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.3 | 12.0 | 11.43 ± 2.17 |
| mattcl-ts | input-aspidites | 11.3 ± 0.3 | 10.4 | 12.1 | 11.44 ± 2.16 |
| mattcl-ts | input-lanjian | 11.3 ± 0.4 | 10.3 | 12.0 | 11.44 ± 2.17 |
| mikofo | input-mattcl | 11.4 ± 0.3 | 10.5 | 12.1 | 11.55 ± 2.19 |
| mikofo | input-lanjian | 11.4 ± 0.3 | 10.4 | 12.6 | 11.60 ± 2.20 |
| mikofo | input-kcen | 11.5 ± 0.3 | 10.5 | 12.7 | 11.65 ± 2.20 |
| mikofo | input-chancalan | 11.5 ± 0.3 | 10.5 | 13.3 | 11.65 ± 2.20 |
| mattcl-ts | input-kcen | 11.5 ± 2.6 | 10.2 | 47.9 | 11.65 ± 3.44 |
| mikofo | input-aspidites | 11.5 ± 0.3 | 10.5 | 12.5 | 11.67 ± 2.21 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.7 | 14.7 | 12.91 ± 2.47 |
| aspidites | input-lanjian | 12.8 ± 0.4 | 11.9 | 13.9 | 13.02 ± 2.48 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.7 | 14.8 | 13.04 ± 2.49 |
| aspidites | input-mattcl | 12.8 ± 0.6 | 11.3 | 15.2 | 13.05 ± 2.51 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.8 | 13.9 | 13.06 ± 2.49 |
| mattcl-py | input-mattcl | 14.6 ± 0.5 | 13.5 | 17.1 | 14.79 ± 2.81 |
| pting | input-aspidites | 14.6 ± 0.6 | 13.4 | 17.5 | 14.83 ± 2.83 |
| pting | input-chancalan | 14.6 ± 0.5 | 13.7 | 17.4 | 14.84 ± 2.82 |
| mattcl-py | input-lanjian | 14.6 ± 0.5 | 13.7 | 18.1 | 14.87 ± 2.83 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.6 | 18.5 | 14.87 ± 2.85 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.6 | 17.6 | 14.88 ± 2.86 |
| mattcl-py | input-aspidites | 14.7 ± 0.6 | 13.7 | 18.1 | 14.93 ± 2.87 |
| pting | input-mattcl | 14.7 ± 0.8 | 13.5 | 17.9 | 14.96 ± 2.91 |
| mattcl-py | input-kcen | 14.7 ± 0.6 | 13.5 | 18.3 | 14.96 ± 2.87 |
| pting | input-kcen | 14.8 ± 2.4 | 13.6 | 46.9 | 15.06 ± 3.70 |
| chancalan | input-kcen | 15.2 ± 0.6 | 14.1 | 18.4 | 15.40 ± 2.94 |
| chancalan | input-aspidites | 15.2 ± 0.6 | 14.3 | 18.3 | 15.41 ± 2.94 |
| chancalan | input-lanjian | 15.2 ± 0.6 | 13.9 | 18.3 | 15.43 ± 2.95 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.1 | 15.44 ± 2.95 |
| chancalan | input-chancalan | 15.2 ± 0.6 | 14.4 | 17.9 | 15.49 ± 2.96 |
| kcen | input-chancalan | 15.4 ± 0.5 | 14.3 | 18.3 | 15.68 ± 2.99 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.4 | 18.5 | 15.70 ± 3.00 |
| kcen | input-mattcl | 15.5 ± 0.6 | 14.7 | 18.6 | 15.74 ± 3.01 |
| kcen | input-lanjian | 15.5 ± 0.7 | 14.4 | 18.7 | 15.78 ± 3.05 |
| kcen | input-aspidites | 15.5 ± 0.7 | 14.3 | 19.1 | 15.79 ± 3.03 |


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