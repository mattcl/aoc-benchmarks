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
| mattcl | input-kcen | 0.9 ± 2.7 | 0.1 | 38.2 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.2 | 1.00 ± 3.13 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.2 | 1.03 ± 3.21 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.2 | 1.03 ± 3.22 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.4 | 1.03 ± 3.23 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 3.23 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.03 ± 3.23 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.3 | 1.03 ± 3.23 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.3 | 1.06 ± 3.31 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.1 | 1.4 | 1.07 ± 3.35 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 9.8 | 11.9 | 12.90 ± 40.23 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 10.0 | 11.9 | 12.95 ± 40.40 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 9.8 | 12.2 | 12.98 ± 40.48 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 9.8 | 11.9 | 12.98 ± 40.50 |
| mattcl-ts | input-lanjian | 11.1 ± 0.4 | 10.1 | 12.1 | 12.99 ± 40.51 |
| mikofo | input-aspidites | 11.2 ± 0.4 | 10.3 | 12.3 | 13.15 ± 41.02 |
| mikofo | input-mattcl | 11.3 ± 0.4 | 10.3 | 12.5 | 13.20 ± 41.17 |
| mikofo | input-lanjian | 11.3 ± 0.3 | 10.2 | 12.3 | 13.24 ± 41.29 |
| mikofo | input-kcen | 11.3 ± 0.3 | 10.2 | 12.7 | 13.26 ± 41.35 |
| mikofo | input-chancalan | 11.3 ± 0.3 | 10.4 | 12.6 | 13.28 ± 41.42 |
| aspidites | input-aspidites | 12.6 ± 0.5 | 11.6 | 14.0 | 14.76 ± 46.04 |
| aspidites | input-kcen | 12.6 ± 0.5 | 11.5 | 14.8 | 14.80 ± 46.17 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.4 | 14.2 | 14.83 ± 46.27 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.7 | 14.4 | 14.91 ± 46.51 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.6 | 14.3 | 15.00 ± 46.78 |
| pting | input-kcen | 14.4 ± 0.5 | 13.3 | 17.3 | 16.86 ± 52.58 |
| pting | input-mattcl | 14.5 ± 0.8 | 13.5 | 17.9 | 16.94 ± 52.84 |
| pting | input-aspidites | 14.5 ± 0.6 | 13.5 | 17.7 | 16.95 ± 52.86 |
| pting | input-chancalan | 14.5 ± 0.7 | 13.1 | 17.7 | 16.96 ± 52.92 |
| mattcl-py | input-mattcl | 14.5 ± 0.6 | 13.5 | 17.9 | 17.00 ± 53.04 |
| mattcl-py | input-chancalan | 14.5 ± 0.6 | 13.5 | 17.4 | 17.01 ± 53.05 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.5 | 18.2 | 17.02 ± 53.09 |
| pting | input-lanjian | 14.5 ± 0.6 | 13.6 | 17.3 | 17.04 ± 53.14 |
| mattcl-py | input-aspidites | 14.6 ± 0.6 | 13.6 | 18.2 | 17.08 ± 53.26 |
| mattcl-py | input-kcen | 15.0 ± 3.4 | 13.5 | 54.4 | 17.58 ± 54.98 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.8 | 17.3 | 17.61 ± 54.92 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 14.0 | 18.4 | 17.66 ± 55.07 |
| chancalan | input-aspidites | 15.1 ± 0.7 | 14.0 | 18.1 | 17.66 ± 55.10 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.9 | 18.3 | 17.69 ± 55.17 |
| kcen | input-mattcl | 15.3 ± 0.6 | 14.3 | 18.1 | 17.90 ± 55.83 |
| kcen | input-chancalan | 15.3 ± 0.6 | 14.1 | 18.0 | 17.94 ± 55.96 |
| kcen | input-lanjian | 15.3 ± 0.6 | 14.5 | 18.7 | 17.94 ± 55.97 |
| kcen | input-aspidites | 15.4 ± 0.6 | 14.5 | 18.3 | 17.98 ± 56.07 |
| kcen | input-kcen | 15.4 ± 0.7 | 14.0 | 18.9 | 18.08 ± 56.41 |
| chancalan | input-kcen | 15.7 ± 4.2 | 13.8 | 60.6 | 18.35 ± 57.43 |


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