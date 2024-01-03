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
| lanjian | input-mattcl | 0.6 ± 0.2 | 0.1 | 1.4 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.33 ± 0.60 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.34 ± 0.61 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.36 ± 0.60 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.0 | 1.36 ± 0.60 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.36 ± 0.62 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.1 | 1.37 ± 0.59 |
| lanjian | input-aspidites | 0.9 ± 0.1 | 0.5 | 1.1 | 1.38 ± 0.59 |
| mattcl | input-aspidites | 0.9 ± 0.1 | 0.5 | 1.1 | 1.41 ± 0.59 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.5 | 1.0 | 1.41 ± 0.59 |
| mattcl-ts | input-chancalan | 10.7 ± 0.4 | 9.5 | 11.7 | 16.93 ± 6.72 |
| mattcl-ts | input-kcen | 10.7 ± 0.5 | 9.4 | 11.8 | 16.98 ± 6.74 |
| mattcl-ts | input-mattcl | 10.7 ± 0.4 | 9.3 | 11.9 | 17.00 ± 6.75 |
| mattcl-ts | input-aspidites | 10.7 ± 0.4 | 9.8 | 11.7 | 17.02 ± 6.75 |
| mikofo | input-lanjian | 10.7 ± 0.4 | 9.7 | 12.3 | 17.03 ± 6.76 |
| mattcl-ts | input-lanjian | 10.7 ± 0.4 | 9.5 | 11.8 | 17.03 ± 6.76 |
| mikofo | input-aspidites | 10.8 ± 0.4 | 9.9 | 11.8 | 17.22 ± 6.83 |
| mikofo | input-chancalan | 10.9 ± 0.4 | 9.7 | 12.1 | 17.23 ± 6.84 |
| mikofo | input-kcen | 10.9 ± 0.4 | 10.0 | 11.7 | 17.37 ± 6.89 |
| mikofo | input-mattcl | 11.0 ± 2.8 | 9.9 | 50.3 | 17.49 ± 8.23 |
| aspidites | input-kcen | 12.6 ± 0.4 | 11.7 | 14.3 | 19.99 ± 7.92 |
| aspidites | input-chancalan | 12.6 ± 0.5 | 11.5 | 13.9 | 20.01 ± 7.94 |
| aspidites | input-lanjian | 12.6 ± 0.4 | 11.6 | 14.1 | 20.05 ± 7.95 |
| aspidites | input-aspidites | 12.8 ± 3.6 | 10.7 | 60.5 | 20.33 ± 9.86 |
| aspidites | input-mattcl | 12.9 ± 4.4 | 11.0 | 64.3 | 20.43 ± 10.71 |
| pting | input-kcen | 14.2 ± 0.6 | 13.3 | 17.5 | 22.57 ± 8.97 |
| pting | input-lanjian | 14.2 ± 0.5 | 13.3 | 17.5 | 22.59 ± 8.96 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.4 | 17.8 | 22.67 ± 9.01 |
| mattcl-py | input-aspidites | 14.3 ± 0.5 | 13.4 | 17.6 | 22.69 ± 9.00 |
| mattcl-py | input-mattcl | 14.3 ± 0.5 | 13.2 | 17.4 | 22.70 ± 9.00 |
| pting | input-chancalan | 14.3 ± 0.8 | 13.3 | 17.7 | 22.71 ± 9.05 |
| mattcl-py | input-kcen | 14.3 ± 0.6 | 13.4 | 18.1 | 22.71 ± 9.02 |
| pting | input-mattcl | 14.3 ± 0.7 | 13.3 | 18.4 | 22.73 ± 9.05 |
| mattcl-py | input-chancalan | 14.3 ± 0.6 | 13.2 | 18.1 | 22.76 ± 9.04 |
| pting | input-aspidites | 14.5 ± 2.9 | 13.2 | 53.9 | 22.99 ± 10.17 |
| chancalan | input-aspidites | 14.8 ± 0.5 | 14.0 | 17.2 | 23.56 ± 9.34 |
| chancalan | input-chancalan | 14.8 ± 0.6 | 14.0 | 17.6 | 23.57 ± 9.35 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.9 | 17.6 | 23.68 ± 9.40 |
| chancalan | input-kcen | 14.9 ± 0.7 | 13.9 | 17.9 | 23.74 ± 9.43 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 13.9 | 18.1 | 23.76 ± 9.44 |
| kcen | input-lanjian | 15.1 ± 0.5 | 14.0 | 18.8 | 23.97 ± 9.50 |
| kcen | input-aspidites | 15.2 ± 0.6 | 14.3 | 18.2 | 24.10 ± 9.56 |
| kcen | input-chancalan | 15.2 ± 1.9 | 14.0 | 39.5 | 24.14 ± 9.98 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.3 | 18.4 | 24.23 ± 9.62 |
| kcen | input-mattcl | 15.7 ± 3.8 | 14.1 | 62.2 | 24.85 ± 11.56 |


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