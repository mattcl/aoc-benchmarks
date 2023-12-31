# Day 5 benchmarks

[link to problem](https://adventofcode.com/2023/day/5)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 5)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.35 |
| lanjian | input-mikofo | 0.9 ± 0.1 | 0.5 | 1.3 | 1.06 ± 0.31 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.08 ± 0.35 |
| lanjian | input-pting | 1.0 ± 0.1 | 0.5 | 1.7 | 1.08 ± 0.32 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.33 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.3 | 1.1 | 1.09 ± 0.33 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.3 | 1.2 | 1.10 ± 0.33 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.3 | 1.2 | 1.10 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.2 | 1.11 ± 0.33 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.7 | 1.12 ± 0.35 |
| mattcl-ts | input-mikofo | 12.7 ± 0.4 | 11.8 | 13.7 | 14.18 ± 3.67 |
| mattcl-ts | input-chancalan | 12.9 ± 0.3 | 11.9 | 13.8 | 14.44 ± 3.74 |
| mattcl-ts | input-mattcl | 12.9 ± 2.9 | 11.8 | 52.7 | 14.47 ± 4.90 |
| mattcl-ts | input-kcen | 13.0 ± 0.4 | 12.1 | 14.8 | 14.58 ± 3.77 |
| mattcl-ts | input-pting | 13.3 ± 2.8 | 12.2 | 51.8 | 14.87 ± 4.91 |
| mattcl-ts | input-lanjian | 14.4 ± 4.7 | 12.8 | 66.6 | 16.05 ± 6.68 |
| kcen | input-mikofo | 15.0 ± 0.6 | 13.7 | 17.7 | 16.75 ± 4.37 |
| kcen | input-mattcl | 15.0 ± 0.5 | 13.8 | 17.9 | 16.77 ± 4.36 |
| kcen | input-chancalan | 15.2 ± 0.5 | 14.2 | 17.7 | 16.94 ± 4.40 |
| pting | input-mattcl | 15.2 ± 0.5 | 13.9 | 18.0 | 16.96 ± 4.40 |
| pting | input-mikofo | 15.2 ± 0.5 | 14.3 | 18.3 | 17.01 ± 4.42 |
| kcen | input-pting | 15.4 ± 0.7 | 14.3 | 18.3 | 17.20 ± 4.50 |
| chancalan | input-mattcl | 15.4 ± 0.6 | 14.1 | 18.8 | 17.21 ± 4.48 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.4 | 18.5 | 17.26 ± 4.49 |
| kcen | input-kcen | 15.5 ± 0.7 | 14.6 | 18.4 | 17.30 ± 4.52 |
| chancalan | input-mikofo | 15.5 ± 0.7 | 14.3 | 19.2 | 17.31 ± 4.52 |
| pting | input-chancalan | 15.5 ± 0.6 | 14.4 | 18.3 | 17.37 ± 4.52 |
| mattcl-py | input-mikofo | 15.5 ± 0.7 | 14.5 | 18.4 | 17.37 ± 4.53 |
| pting | input-pting | 15.8 ± 0.5 | 14.6 | 18.7 | 17.63 ± 4.58 |
| chancalan | input-chancalan | 15.8 ± 0.6 | 14.5 | 18.7 | 17.68 ± 4.60 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.6 | 19.7 | 17.80 ± 4.65 |
| chancalan | input-pting | 16.1 ± 0.7 | 14.9 | 19.1 | 17.99 ± 4.69 |
| pting | input-kcen | 16.2 ± 0.7 | 14.8 | 19.0 | 18.07 ± 4.71 |
| mattcl-py | input-pting | 16.3 ± 0.7 | 14.9 | 19.7 | 18.19 ± 4.75 |
| kcen | input-lanjian | 16.3 ± 0.7 | 14.8 | 19.7 | 18.24 ± 4.76 |
| chancalan | input-kcen | 16.3 ± 0.7 | 15.2 | 19.0 | 18.24 ± 4.76 |
| mattcl-py | input-kcen | 16.3 ± 0.7 | 15.0 | 19.8 | 18.24 ± 4.76 |
| pting | input-lanjian | 17.6 ± 3.5 | 16.1 | 50.9 | 19.66 ± 6.36 |
| chancalan | input-lanjian | 17.6 ± 0.7 | 16.6 | 20.7 | 19.67 ± 5.12 |
| mattcl-py | input-lanjian | 17.9 ± 0.6 | 17.0 | 20.5 | 19.99 ± 5.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|