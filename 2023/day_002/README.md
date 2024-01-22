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
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.29 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.28 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.2 | 1.04 ± 0.26 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.29 |
| lanjian | input-aspidites | 0.9 ± 0.1 | 0.2 | 1.1 | 1.07 ± 0.26 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.5 | 1.08 ± 0.27 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.5 | 1.08 ± 0.27 |
| mattcl-ts | input-mattcl | 10.4 ± 0.4 | 9.3 | 11.5 | 11.96 ± 2.40 |
| mikofo | input-lanjian | 10.4 ± 0.4 | 9.5 | 11.5 | 11.97 ± 2.40 |
| mattcl-ts | input-kcen | 10.5 ± 0.4 | 9.3 | 11.5 | 12.00 ± 2.40 |
| mikofo | input-kcen | 10.5 ± 0.4 | 9.5 | 11.8 | 12.02 ± 2.42 |
| mikofo | input-chancalan | 10.5 ± 0.4 | 9.6 | 11.5 | 12.03 ± 2.42 |
| mikofo | input-mattcl | 10.5 ± 0.4 | 9.5 | 11.7 | 12.04 ± 2.42 |
| mattcl-ts | input-chancalan | 10.5 ± 0.4 | 9.4 | 11.4 | 12.05 ± 2.41 |
| mattcl-ts | input-lanjian | 10.5 ± 0.4 | 9.3 | 11.8 | 12.06 ± 2.42 |
| mikofo | input-aspidites | 10.5 ± 0.4 | 9.6 | 11.7 | 12.08 ± 2.42 |
| mattcl-ts | input-aspidites | 10.5 ± 0.4 | 9.2 | 11.9 | 12.09 ± 2.43 |
| aspidites | input-kcen | 12.3 ± 0.7 | 11.0 | 14.0 | 14.17 ± 2.89 |
| aspidites | input-lanjian | 12.6 ± 0.5 | 11.6 | 14.2 | 14.47 ± 2.90 |
| aspidites | input-aspidites | 12.6 ± 0.5 | 11.6 | 14.0 | 14.50 ± 2.91 |
| aspidites | input-chancalan | 12.6 ± 0.4 | 11.6 | 14.0 | 14.51 ± 2.90 |
| aspidites | input-mattcl | 12.6 ± 0.5 | 11.8 | 14.1 | 14.52 ± 2.91 |
| pting | input-chancalan | 14.5 ± 0.5 | 13.4 | 18.1 | 16.62 ± 3.33 |
| pting | input-aspidites | 14.5 ± 0.6 | 13.2 | 17.5 | 16.65 ± 3.35 |
| mattcl-py | input-chancalan | 14.5 ± 0.6 | 13.4 | 17.6 | 16.67 ± 3.35 |
| pting | input-kcen | 14.5 ± 0.6 | 13.5 | 17.6 | 16.69 ± 3.36 |
| mattcl-py | input-kcen | 14.6 ± 0.5 | 13.8 | 17.8 | 16.71 ± 3.34 |
| pting | input-mattcl | 14.6 ± 0.6 | 13.5 | 17.4 | 16.72 ± 3.36 |
| pting | input-lanjian | 14.6 ± 0.7 | 13.7 | 18.1 | 16.73 ± 3.38 |
| mattcl-py | input-aspidites | 14.6 ± 0.6 | 13.6 | 18.2 | 16.75 ± 3.37 |
| mattcl-py | input-lanjian | 14.6 ± 0.6 | 13.2 | 16.8 | 16.78 ± 3.37 |
| mattcl-py | input-mattcl | 14.7 ± 0.7 | 13.6 | 18.2 | 16.87 ± 3.41 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.8 | 18.3 | 17.38 ± 3.50 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 13.8 | 18.3 | 17.39 ± 3.50 |
| chancalan | input-lanjian | 15.2 ± 0.7 | 14.0 | 18.7 | 17.42 ± 3.54 |
| chancalan | input-aspidites | 15.2 ± 0.6 | 14.2 | 18.0 | 17.44 ± 3.51 |
| chancalan | input-chancalan | 15.2 ± 0.8 | 14.0 | 18.3 | 17.45 ± 3.54 |
| kcen | input-chancalan | 15.3 ± 0.6 | 14.2 | 18.5 | 17.60 ± 3.54 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.5 | 18.4 | 17.70 ± 3.56 |
| kcen | input-mattcl | 15.4 ± 0.7 | 14.2 | 18.3 | 17.73 ± 3.57 |
| kcen | input-lanjian | 15.5 ± 0.7 | 14.5 | 18.2 | 17.75 ± 3.58 |
| kcen | input-aspidites | 15.5 ± 0.7 | 14.4 | 18.5 | 17.76 ± 3.59 |


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