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
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-mattcl | 0.6 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.25 ± 0.55 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.28 ± 0.56 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.2 | 1.2 | 1.28 ± 0.55 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.28 ± 0.55 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.30 ± 0.54 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.3 | 1.31 ± 0.54 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.33 ± 0.58 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.1 | 1.5 | 1.34 ± 0.60 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.34 ± 0.57 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.3 | 1.34 ± 0.57 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.38 ± 0.57 |
| aspidites | input-mattcl | 13.0 ± 0.5 | 11.9 | 14.7 | 20.45 ± 7.61 |
| aspidites | input-kcen | 13.0 ± 0.5 | 11.9 | 14.6 | 20.45 ± 7.61 |
| aspidites | input-aspidites | 13.0 ± 0.4 | 12.1 | 13.9 | 20.48 ± 7.62 |
| aspidites | input-lanjian | 13.1 ± 0.4 | 12.1 | 14.1 | 20.49 ± 7.62 |
| aspidites | input-pting | 13.1 ± 0.5 | 12.1 | 14.7 | 20.51 ± 7.63 |
| aspidites | input-chancalan | 13.1 ± 0.5 | 12.1 | 14.5 | 20.52 ± 7.64 |
| pting | input-pting | 16.4 ± 0.5 | 15.4 | 19.5 | 25.76 ± 9.58 |
| pting | input-lanjian | 16.4 ± 0.5 | 15.6 | 19.3 | 25.76 ± 9.58 |
| pting | input-aspidites | 16.4 ± 0.6 | 15.4 | 19.0 | 25.81 ± 9.61 |
| pting | input-kcen | 16.4 ± 0.6 | 15.4 | 19.6 | 25.82 ± 9.62 |
| mattcl-py | input-chancalan | 16.5 ± 0.5 | 15.6 | 19.6 | 25.85 ± 9.61 |
| pting | input-mattcl | 16.5 ± 0.6 | 15.5 | 19.4 | 25.85 ± 9.62 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.4 | 19.7 | 25.90 ± 9.65 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.7 | 19.3 | 25.93 ± 9.65 |
| pting | input-chancalan | 16.5 ± 0.8 | 15.5 | 19.8 | 25.96 ± 9.69 |
| mattcl-py | input-kcen | 16.6 ± 0.7 | 15.7 | 19.7 | 26.03 ± 9.71 |
| mattcl-py | input-aspidites | 16.6 ± 1.7 | 15.3 | 38.3 | 26.10 ± 10.05 |
| mattcl-py | input-pting | 16.7 ± 0.8 | 15.7 | 22.2 | 26.17 ± 9.78 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.7 | 27.14 ± 10.12 |
| chancalan | input-chancalan | 17.3 ± 0.7 | 16.1 | 20.5 | 27.21 ± 10.14 |
| chancalan | input-mattcl | 17.4 ± 0.7 | 16.1 | 20.9 | 27.26 ± 10.16 |
| chancalan | input-aspidites | 17.4 ± 0.7 | 16.1 | 20.8 | 27.27 ± 10.17 |
| chancalan | input-pting | 17.4 ± 0.7 | 16.3 | 20.7 | 27.28 ± 10.17 |
| chancalan | input-kcen | 17.4 ± 1.4 | 16.1 | 29.9 | 27.32 ± 10.37 |
| kcen | input-lanjian | 17.7 ± 0.7 | 16.9 | 20.9 | 27.74 ± 10.34 |
| kcen | input-chancalan | 17.7 ± 0.7 | 16.9 | 20.8 | 27.86 ± 10.38 |
| kcen | input-aspidites | 17.8 ± 0.7 | 17.0 | 20.7 | 27.87 ± 10.38 |
| kcen | input-kcen | 17.8 ± 0.7 | 16.5 | 20.6 | 27.98 ± 10.42 |
| kcen | input-pting | 17.9 ± 0.9 | 16.9 | 21.1 | 28.09 ± 10.50 |
| kcen | input-mattcl | 18.1 ± 3.1 | 16.8 | 53.9 | 28.44 ± 11.58 |
| mikofo | input-pting | 315.8 ± 1.7 | 313.2 | 317.8 | 495.64 ± 183.63 |
| mikofo | input-kcen | 315.9 ± 2.1 | 312.2 | 318.7 | 495.80 ± 183.70 |
| mikofo | input-lanjian | 316.0 ± 1.3 | 314.1 | 318.4 | 495.96 ± 183.73 |
| mikofo | input-chancalan | 316.0 ± 1.4 | 313.8 | 318.0 | 496.02 ± 183.76 |
| mikofo | input-mattcl | 316.1 ± 1.4 | 313.8 | 317.4 | 496.16 ± 183.81 |
| mikofo | input-aspidites | 316.5 ± 1.9 | 313.8 | 319.4 | 496.85 ± 184.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|