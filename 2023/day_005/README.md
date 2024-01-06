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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.36 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.36 |
| lanjian | input-mikofo | 0.9 ± 0.1 | 0.2 | 1.1 | 1.07 ± 0.32 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.1 | 1.07 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.7 | 1.09 ± 0.35 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.2 | 1.1 | 1.10 ± 0.33 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.1 | 1.10 ± 0.33 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.1 | 1.11 ± 0.33 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.17 ± 0.35 |
| mattcl-ts | input-mikofo | 12.6 ± 0.4 | 11.4 | 13.4 | 15.11 ± 3.83 |
| mattcl-ts | input-chancalan | 12.8 ± 0.3 | 12.0 | 14.0 | 15.41 ± 3.90 |
| mattcl-ts | input-mattcl | 12.9 ± 2.6 | 11.5 | 48.9 | 15.47 ± 4.98 |
| mattcl-ts | input-kcen | 13.0 ± 0.3 | 12.2 | 13.8 | 15.58 ± 3.94 |
| mattcl-ts | input-lanjian | 13.8 ± 0.3 | 13.2 | 14.7 | 16.62 ± 4.20 |
| kcen | input-mattcl | 15.0 ± 0.5 | 14.0 | 17.6 | 17.97 ± 4.56 |
| kcen | input-mikofo | 15.0 ± 0.6 | 14.0 | 18.0 | 18.06 ± 4.60 |
| kcen | input-chancalan | 15.1 ± 0.7 | 13.8 | 18.2 | 18.11 ± 4.63 |
| pting | input-mikofo | 15.1 ± 0.6 | 14.1 | 17.9 | 18.15 ± 4.62 |
| mattcl-py | input-mikofo | 15.3 ± 0.5 | 14.5 | 18.6 | 18.35 ± 4.67 |
| mattcl-py | input-mattcl | 15.3 ± 0.5 | 14.2 | 18.1 | 18.37 ± 4.67 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.1 | 18.6 | 18.37 ± 4.70 |
| chancalan | input-mattcl | 15.4 ± 0.8 | 14.5 | 18.8 | 18.46 ± 4.73 |
| chancalan | input-mikofo | 15.4 ± 0.7 | 14.0 | 18.5 | 18.48 ± 4.73 |
| pting | input-chancalan | 15.4 ± 0.6 | 14.3 | 18.6 | 18.53 ± 4.72 |
| pting | input-mattcl | 15.5 ± 3.0 | 14.1 | 55.3 | 18.57 ± 5.88 |
| chancalan | input-chancalan | 15.6 ± 0.6 | 14.5 | 18.7 | 18.66 ± 4.75 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.7 | 18.7 | 19.13 ± 4.88 |
| pting | input-kcen | 16.1 ± 0.7 | 15.0 | 19.7 | 19.28 ± 4.92 |
| chancalan | input-kcen | 16.2 ± 0.7 | 14.9 | 18.6 | 19.43 ± 4.96 |
| mattcl-py | input-kcen | 16.2 ± 0.7 | 15.0 | 19.9 | 19.50 ± 4.99 |
| kcen | input-lanjian | 16.3 ± 0.8 | 14.8 | 19.6 | 19.51 ± 5.00 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.3 | 20.5 | 20.68 ± 5.27 |
| chancalan | input-lanjian | 17.5 ± 0.6 | 16.3 | 20.4 | 20.94 ± 5.32 |
| mattcl-py | input-lanjian | 17.9 ± 0.6 | 17.0 | 20.9 | 21.44 ± 5.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|