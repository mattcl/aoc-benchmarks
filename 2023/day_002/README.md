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
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.30 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.30 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.1 | 1.03 ± 0.29 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.7 | 1.04 ± 0.30 |
| mattcl | input-aspidites | 1.0 ± 0.1 | 0.3 | 1.4 | 1.07 ± 0.29 |
| mattcl-ts | input-lanjian | 10.9 ± 0.4 | 9.8 | 12.0 | 11.98 ± 2.74 |
| mattcl-ts | input-kcen | 10.9 ± 0.4 | 9.9 | 11.9 | 12.04 ± 2.75 |
| mattcl-ts | input-mattcl | 11.0 ± 0.4 | 9.6 | 12.0 | 12.05 ± 2.75 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 9.8 | 12.3 | 12.06 ± 2.75 |
| mattcl-ts | input-aspidites | 11.0 ± 0.4 | 9.8 | 12.0 | 12.06 ± 2.75 |
| mikofo | input-lanjian | 11.0 ± 0.4 | 10.0 | 11.8 | 12.09 ± 2.75 |
| mikofo | input-kcen | 11.1 ± 0.4 | 10.0 | 11.8 | 12.16 ± 2.77 |
| mikofo | input-mattcl | 11.1 ± 0.4 | 10.1 | 12.0 | 12.16 ± 2.77 |
| mikofo | input-chancalan | 11.1 ± 0.4 | 10.0 | 12.1 | 12.17 ± 2.77 |
| mikofo | input-aspidites | 11.3 ± 3.7 | 10.1 | 63.2 | 12.38 ± 4.95 |
| aspidites | input-kcen | 12.6 ± 0.4 | 11.6 | 13.7 | 13.85 ± 3.15 |
| aspidites | input-aspidites | 12.6 ± 0.4 | 11.9 | 13.8 | 13.86 ± 3.16 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.7 | 15.0 | 13.92 ± 3.18 |
| aspidites | input-mattcl | 12.7 ± 0.4 | 11.7 | 14.1 | 13.93 ± 3.17 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.9 | 14.2 | 13.96 ± 3.18 |
| pting | input-lanjian | 14.2 ± 0.5 | 13.3 | 17.1 | 15.61 ± 3.57 |
| pting | input-aspidites | 14.3 ± 0.6 | 13.5 | 17.5 | 15.71 ± 3.60 |
| pting | input-mattcl | 14.3 ± 0.6 | 13.2 | 17.6 | 15.74 ± 3.61 |
| mattcl-py | input-chancalan | 14.3 ± 0.6 | 13.3 | 17.8 | 15.76 ± 3.61 |
| pting | input-kcen | 14.3 ± 0.7 | 13.5 | 17.5 | 15.77 ± 3.64 |
| mattcl-py | input-aspidites | 14.3 ± 0.6 | 13.5 | 17.6 | 15.77 ± 3.61 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.4 | 17.2 | 15.77 ± 3.61 |
| mattcl-py | input-kcen | 14.4 ± 0.6 | 13.4 | 17.5 | 15.83 ± 3.64 |
| pting | input-chancalan | 14.4 ± 0.6 | 13.7 | 17.5 | 15.84 ± 3.63 |
| mattcl-py | input-mattcl | 14.5 ± 2.2 | 13.4 | 43.3 | 15.99 ± 4.31 |
| chancalan | input-kcen | 14.9 ± 0.5 | 14.2 | 17.3 | 16.37 ± 3.73 |
| chancalan | input-chancalan | 14.9 ± 0.5 | 14.2 | 17.9 | 16.38 ± 3.74 |
| chancalan | input-lanjian | 15.0 ± 1.3 | 13.9 | 31.7 | 16.52 ± 4.00 |
| chancalan | input-aspidites | 15.0 ± 0.8 | 13.8 | 21.5 | 16.52 ± 3.84 |
| kcen | input-kcen | 15.2 ± 0.4 | 14.4 | 17.5 | 16.68 ± 3.79 |
| kcen | input-lanjian | 15.2 ± 0.6 | 14.2 | 18.1 | 16.72 ± 3.82 |
| kcen | input-chancalan | 15.2 ± 0.7 | 14.2 | 18.4 | 16.72 ± 3.85 |
| chancalan | input-mattcl | 15.3 ± 2.4 | 14.1 | 46.7 | 16.83 ± 4.61 |
| kcen | input-mattcl | 15.4 ± 1.6 | 14.0 | 35.5 | 16.89 ± 4.20 |
| kcen | input-aspidites | 15.8 ± 4.2 | 14.3 | 61.4 | 17.34 ± 6.03 |


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