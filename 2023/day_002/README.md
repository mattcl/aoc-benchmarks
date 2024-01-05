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
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.4 | 1.2 | 1.00 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.5 | 1.2 | 1.00 ± 0.23 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.3 | 1.01 ± 0.24 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.6 | 1.3 | 1.02 ± 0.22 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 2.6 | 1.02 ± 0.26 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.2 | 1.03 ± 0.22 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 3.0 | 0.2 | 42.5 | 1.04 ± 2.97 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-kcen | 1.1 ± 3.2 | 0.2 | 46.4 | 1.08 ± 3.24 |
| mattcl-ts | input-aspidites | 11.0 ± 0.4 | 10.1 | 12.2 | 11.04 ± 1.95 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 9.8 | 11.7 | 11.06 ± 1.95 |
| mattcl-ts | input-lanjian | 11.1 ± 0.4 | 10.0 | 12.2 | 11.07 ± 1.96 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 10.0 | 12.0 | 11.09 ± 1.97 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 9.8 | 11.9 | 11.14 ± 1.97 |
| mikofo | input-lanjian | 11.4 ± 0.4 | 10.4 | 12.3 | 11.37 ± 2.00 |
| mikofo | input-aspidites | 11.4 ± 0.3 | 10.3 | 12.2 | 11.38 ± 2.00 |
| mikofo | input-mattcl | 11.4 ± 0.4 | 10.5 | 12.5 | 11.40 ± 2.01 |
| mikofo | input-chancalan | 11.4 ± 0.3 | 10.6 | 12.3 | 11.45 ± 2.01 |
| mikofo | input-kcen | 11.5 ± 0.3 | 10.5 | 12.5 | 11.50 ± 2.02 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.7 | 14.0 | 12.75 ± 2.25 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.8 | 14.2 | 12.82 ± 2.27 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.9 | 14.2 | 12.86 ± 2.28 |
| aspidites | input-mattcl | 12.8 ± 0.4 | 11.9 | 13.9 | 12.86 ± 2.27 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 12.0 | 14.6 | 12.91 ± 2.28 |
| pting | input-chancalan | 14.4 ± 0.5 | 13.3 | 17.1 | 14.40 ± 2.55 |
| mattcl-py | input-lanjian | 14.4 ± 0.4 | 13.5 | 16.5 | 14.41 ± 2.53 |
| pting | input-kcen | 14.4 ± 0.6 | 13.6 | 17.4 | 14.42 ± 2.57 |
| pting | input-aspidites | 14.4 ± 0.6 | 13.3 | 17.7 | 14.42 ± 2.56 |
| pting | input-lanjian | 14.4 ± 0.7 | 13.5 | 18.1 | 14.45 ± 2.60 |
| mattcl-py | input-aspidites | 14.5 ± 0.5 | 13.6 | 17.9 | 14.47 ± 2.57 |
| mattcl-py | input-kcen | 14.5 ± 0.6 | 13.5 | 17.8 | 14.49 ± 2.58 |
| mattcl-py | input-chancalan | 14.5 ± 0.7 | 13.5 | 17.4 | 14.49 ± 2.60 |
| pting | input-mattcl | 14.5 ± 0.8 | 13.3 | 18.4 | 14.54 ± 2.64 |
| mattcl-py | input-mattcl | 14.6 ± 0.8 | 13.4 | 18.3 | 14.60 ± 2.66 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.8 | 18.0 | 15.02 ± 2.66 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 13.9 | 17.8 | 15.03 ± 2.68 |
| chancalan | input-kcen | 15.0 ± 0.5 | 13.9 | 17.7 | 15.03 ± 2.66 |
| chancalan | input-mattcl | 15.0 ± 0.5 | 14.0 | 17.7 | 15.06 ± 2.66 |
| chancalan | input-aspidites | 15.2 ± 0.7 | 14.0 | 18.1 | 15.18 ± 2.71 |
| kcen | input-lanjian | 15.3 ± 0.6 | 14.1 | 18.4 | 15.33 ± 2.73 |
| kcen | input-aspidites | 15.3 ± 0.6 | 14.4 | 18.8 | 15.35 ± 2.72 |
| kcen | input-mattcl | 15.3 ± 0.7 | 14.2 | 18.6 | 15.35 ± 2.74 |
| kcen | input-chancalan | 15.4 ± 0.8 | 14.1 | 18.4 | 15.39 ± 2.77 |
| kcen | input-kcen | 15.4 ± 1.7 | 14.2 | 38.6 | 15.40 ± 3.19 |


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