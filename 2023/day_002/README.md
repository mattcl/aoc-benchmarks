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
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.31 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.7 | 1.03 ± 0.31 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.04 ± 0.31 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.2 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.6 | 1.6 | 1.05 ± 0.30 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.32 |
| mattcl-ts | input-mattcl | 10.7 ± 0.4 | 9.7 | 11.7 | 11.64 ± 2.82 |
| mattcl-ts | input-lanjian | 10.8 ± 0.4 | 9.4 | 11.8 | 11.70 ± 2.84 |
| mattcl-ts | input-aspidites | 10.8 ± 0.4 | 9.4 | 11.8 | 11.71 ± 2.84 |
| mattcl-ts | input-kcen | 10.8 ± 0.4 | 9.6 | 11.7 | 11.72 ± 2.85 |
| mattcl-ts | input-chancalan | 10.8 ± 0.4 | 9.6 | 11.9 | 11.72 ± 2.84 |
| mikofo | input-lanjian | 10.9 ± 0.4 | 9.9 | 11.8 | 11.83 ± 2.87 |
| mikofo | input-mattcl | 10.9 ± 0.4 | 9.9 | 12.0 | 11.84 ± 2.88 |
| mikofo | input-aspidites | 11.0 ± 0.4 | 10.2 | 11.9 | 11.89 ± 2.89 |
| mikofo | input-kcen | 11.0 ± 0.4 | 10.0 | 12.0 | 11.91 ± 2.90 |
| mikofo | input-chancalan | 11.0 ± 0.4 | 9.9 | 12.0 | 11.93 ± 2.89 |
| aspidites | input-aspidites | 12.5 ± 0.4 | 11.2 | 13.6 | 13.60 ± 3.29 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.7 | 14.1 | 13.73 ± 3.33 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.7 | 14.8 | 13.73 ± 3.34 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.7 | 14.1 | 13.74 ± 3.34 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.8 | 14.0 | 13.82 ± 3.35 |
| pting | input-mattcl | 14.5 ± 0.6 | 13.5 | 17.6 | 15.71 ± 3.83 |
| pting | input-chancalan | 14.5 ± 0.7 | 13.6 | 17.6 | 15.71 ± 3.84 |
| mattcl-py | input-mattcl | 14.5 ± 0.6 | 13.7 | 17.8 | 15.72 ± 3.83 |
| pting | input-aspidites | 14.5 ± 0.6 | 13.7 | 18.0 | 15.72 ± 3.83 |
| pting | input-lanjian | 14.5 ± 0.6 | 13.6 | 17.8 | 15.75 ± 3.84 |
| pting | input-kcen | 14.5 ± 0.6 | 13.3 | 17.3 | 15.76 ± 3.85 |
| mattcl-py | input-aspidites | 14.6 ± 0.7 | 13.3 | 18.0 | 15.81 ± 3.86 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.5 | 18.3 | 15.83 ± 3.85 |
| mattcl-py | input-kcen | 14.6 ± 0.8 | 13.6 | 18.0 | 15.88 ± 3.90 |
| mattcl-py | input-lanjian | 14.7 ± 0.8 | 13.3 | 17.8 | 15.90 ± 3.90 |
| chancalan | input-chancalan | 15.1 ± 0.5 | 13.9 | 18.1 | 16.33 ± 3.96 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.1 | 17.7 | 16.34 ± 3.96 |
| chancalan | input-lanjian | 15.1 ± 0.5 | 14.1 | 17.9 | 16.35 ± 3.96 |
| chancalan | input-aspidites | 15.2 ± 0.6 | 14.2 | 18.4 | 16.47 ± 4.01 |
| chancalan | input-kcen | 15.2 ± 0.7 | 14.1 | 18.1 | 16.47 ± 4.02 |
| kcen | input-lanjian | 15.4 ± 0.7 | 14.1 | 18.6 | 16.64 ± 4.06 |
| kcen | input-mattcl | 15.4 ± 0.7 | 14.3 | 18.3 | 16.68 ± 4.07 |
| kcen | input-aspidites | 15.4 ± 0.6 | 14.5 | 18.3 | 16.68 ± 4.05 |
| kcen | input-chancalan | 15.4 ± 0.7 | 14.2 | 19.1 | 16.74 ± 4.09 |
| kcen | input-kcen | 15.5 ± 0.8 | 14.6 | 18.7 | 16.81 ± 4.12 |


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