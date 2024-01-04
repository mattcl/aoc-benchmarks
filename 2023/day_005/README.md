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
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.2 | 1.5 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.31 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.03 ± 0.32 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.31 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.1 | 1.6 | 1.06 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.1 | 1.08 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.6 | 1.09 ± 0.33 |
| mattcl-ts | input-mikofo | 12.4 ± 0.4 | 11.4 | 13.2 | 15.20 ± 3.67 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.4 | 13.5 | 15.27 ± 3.69 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.8 | 13.9 | 15.38 ± 3.71 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.9 | 13.6 | 15.55 ± 3.75 |
| mattcl-ts | input-lanjian | 13.7 ± 0.3 | 12.8 | 14.6 | 16.71 ± 4.03 |
| kcen | input-mattcl | 14.7 ± 0.5 | 13.7 | 17.5 | 17.96 ± 4.36 |
| kcen | input-mikofo | 14.7 ± 0.6 | 13.7 | 17.5 | 18.04 ± 4.40 |
| kcen | input-chancalan | 14.9 ± 0.5 | 13.9 | 17.7 | 18.25 ± 4.42 |
| pting | input-mikofo | 15.0 ± 0.5 | 14.2 | 16.9 | 18.34 ± 4.44 |
| pting | input-mattcl | 15.0 ± 0.6 | 13.9 | 18.0 | 18.36 ± 4.47 |
| pting | input-chancalan | 15.1 ± 0.5 | 14.2 | 17.9 | 18.49 ± 4.47 |
| kcen | input-kcen | 15.1 ± 0.6 | 14.1 | 19.0 | 18.54 ± 4.52 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.0 | 18.55 ± 4.51 |
| mattcl-py | input-mikofo | 15.2 ± 0.7 | 14.1 | 18.4 | 18.58 ± 4.54 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.4 | 18.3 | 18.59 ± 4.53 |
| chancalan | input-chancalan | 15.4 ± 0.6 | 14.3 | 18.3 | 18.82 ± 4.58 |
| chancalan | input-mikofo | 15.4 ± 3.1 | 14.1 | 58.2 | 18.87 ± 5.95 |
| mattcl-py | input-chancalan | 15.6 ± 0.7 | 14.9 | 19.3 | 19.13 ± 4.67 |
| pting | input-kcen | 15.7 ± 0.5 | 14.9 | 18.1 | 19.19 ± 4.65 |
| chancalan | input-kcen | 15.9 ± 0.7 | 14.8 | 19.4 | 19.49 ± 4.76 |
| kcen | input-lanjian | 16.0 ± 0.6 | 14.9 | 18.8 | 19.53 ± 4.75 |
| mattcl-py | input-kcen | 16.0 ± 0.6 | 14.9 | 18.9 | 19.56 ± 4.75 |
| pting | input-lanjian | 17.0 ± 0.8 | 15.9 | 20.4 | 20.82 ± 5.08 |
| chancalan | input-lanjian | 17.2 ± 0.6 | 16.2 | 19.9 | 21.01 ± 5.10 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.3 | 20.8 | 21.52 ± 5.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|