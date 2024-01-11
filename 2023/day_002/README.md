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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.31 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.1 | 1.05 ± 0.29 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.30 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 2.5 | 1.06 ± 0.32 |
| mattcl | input-aspidites | 1.0 ± 0.1 | 0.5 | 1.4 | 1.06 ± 0.28 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 10.1 | 12.1 | 12.23 ± 2.80 |
| mattcl-ts | input-lanjian | 11.1 ± 0.4 | 9.9 | 12.0 | 12.24 ± 2.79 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 10.0 | 12.0 | 12.24 ± 2.80 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 9.5 | 12.2 | 12.28 ± 2.80 |
| mattcl-ts | input-chancalan | 11.1 ± 0.4 | 9.8 | 12.3 | 12.30 ± 2.81 |
| mikofo | input-chancalan | 11.3 ± 0.3 | 10.3 | 12.4 | 12.49 ± 2.84 |
| mikofo | input-mattcl | 11.3 ± 0.4 | 10.3 | 12.5 | 12.52 ± 2.85 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.2 | 12.4 | 12.54 ± 2.85 |
| mikofo | input-kcen | 11.4 ± 0.3 | 10.4 | 12.4 | 12.57 ± 2.85 |
| mikofo | input-lanjian | 11.4 ± 0.4 | 10.4 | 12.5 | 12.58 ± 2.87 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.4 | 14.4 | 14.07 ± 3.22 |
| aspidites | input-mattcl | 12.7 ± 2.8 | 11.1 | 51.0 | 14.09 ± 4.43 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.5 | 14.3 | 14.09 ± 3.23 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.7 | 14.6 | 14.14 ± 3.24 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.9 | 14.1 | 14.15 ± 3.24 |
| pting | input-kcen | 14.5 ± 0.6 | 13.6 | 17.7 | 15.98 ± 3.67 |
| pting | input-mattcl | 14.5 ± 0.6 | 13.6 | 17.9 | 16.00 ± 3.68 |
| pting | input-aspidites | 14.5 ± 0.6 | 13.4 | 17.7 | 16.04 ± 3.68 |
| pting | input-lanjian | 14.5 ± 0.6 | 13.6 | 17.0 | 16.06 ± 3.68 |
| pting | input-chancalan | 14.5 ± 0.7 | 13.5 | 17.8 | 16.07 ± 3.70 |
| mattcl-py | input-kcen | 14.5 ± 0.5 | 13.7 | 18.1 | 16.08 ± 3.67 |
| mattcl-py | input-aspidites | 14.6 ± 0.6 | 13.4 | 17.9 | 16.10 ± 3.70 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.1 | 17.5 | 16.11 ± 3.69 |
| mattcl-py | input-lanjian | 14.6 ± 0.7 | 13.6 | 18.3 | 16.13 ± 3.72 |
| mattcl-py | input-mattcl | 14.7 ± 0.8 | 13.2 | 18.4 | 16.23 ± 3.76 |
| chancalan | input-aspidites | 15.0 ± 0.5 | 13.7 | 18.4 | 16.60 ± 3.79 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.8 | 18.3 | 16.69 ± 3.83 |
| chancalan | input-chancalan | 15.1 ± 0.7 | 13.7 | 18.6 | 16.73 ± 3.85 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 14.0 | 18.6 | 16.74 ± 3.83 |
| chancalan | input-lanjian | 15.2 ± 0.7 | 14.0 | 18.4 | 16.77 ± 3.87 |
| kcen | input-lanjian | 15.3 ± 0.5 | 14.1 | 18.3 | 16.88 ± 3.85 |
| kcen | input-kcen | 15.4 ± 0.7 | 14.1 | 18.8 | 17.00 ± 3.90 |
| kcen | input-chancalan | 15.4 ± 0.6 | 14.1 | 18.1 | 17.00 ± 3.89 |
| kcen | input-mattcl | 15.4 ± 0.6 | 14.3 | 18.6 | 17.03 ± 3.90 |
| kcen | input-aspidites | 15.5 ± 1.1 | 14.1 | 27.5 | 17.18 ± 4.05 |


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