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
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.34 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.36 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.33 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.06 ± 0.34 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.0 | 1.09 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.10 ± 0.35 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.1 | 1.4 | 1.10 ± 0.33 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.4 | 2.1 | 1.11 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.4 | 1.12 ± 0.35 |
| mattcl-ts | input-mikofo | 12.5 ± 0.3 | 11.5 | 13.7 | 15.97 ± 4.01 |
| mattcl-ts | input-chancalan | 12.7 ± 0.4 | 11.6 | 14.2 | 16.19 ± 4.07 |
| mattcl-ts | input-kcen | 12.9 ± 0.3 | 12.2 | 13.8 | 16.44 ± 4.13 |
| mattcl-ts | input-mattcl | 13.2 ± 4.9 | 11.6 | 62.8 | 16.87 ± 7.50 |
| mattcl-ts | input-lanjian | 13.8 ± 0.4 | 12.9 | 15.0 | 17.57 ± 4.42 |
| kcen | input-mikofo | 14.9 ± 0.5 | 13.8 | 17.9 | 18.91 ± 4.77 |
| kcen | input-mattcl | 14.9 ± 0.9 | 13.6 | 18.3 | 19.02 ± 4.90 |
| pting | input-mikofo | 15.0 ± 0.5 | 14.2 | 17.4 | 19.14 ± 4.82 |
| kcen | input-chancalan | 15.1 ± 0.5 | 14.0 | 17.4 | 19.17 ± 4.82 |
| pting | input-mattcl | 15.1 ± 0.6 | 14.1 | 18.3 | 19.20 ± 4.85 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.0 | 18.2 | 19.21 ± 4.84 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.0 | 17.8 | 19.24 ± 4.85 |
| chancalan | input-mikofo | 15.3 ± 0.6 | 14.5 | 18.5 | 19.43 ± 4.92 |
| pting | input-chancalan | 15.3 ± 0.6 | 14.3 | 18.5 | 19.49 ± 4.94 |
| mattcl-py | input-mattcl | 15.5 ± 0.8 | 14.3 | 18.9 | 19.70 ± 5.02 |
| chancalan | input-chancalan | 15.6 ± 0.7 | 14.6 | 18.7 | 19.88 ± 5.04 |
| mattcl-py | input-mikofo | 15.8 ± 4.5 | 14.2 | 64.4 | 20.06 ± 7.60 |
| mattcl-py | input-chancalan | 15.9 ± 0.8 | 14.6 | 18.8 | 20.24 ± 5.15 |
| pting | input-kcen | 15.9 ± 0.6 | 14.7 | 19.4 | 20.27 ± 5.13 |
| kcen | input-lanjian | 16.0 ± 0.6 | 15.1 | 18.9 | 20.43 ± 5.17 |
| chancalan | input-kcen | 16.1 ± 0.6 | 15.1 | 19.0 | 20.52 ± 5.19 |
| mattcl-py | input-kcen | 16.2 ± 0.7 | 14.9 | 19.1 | 20.56 ± 5.21 |
| pting | input-lanjian | 17.0 ± 0.6 | 15.7 | 20.1 | 21.67 ± 5.47 |
| chancalan | input-lanjian | 17.5 ± 0.8 | 16.0 | 20.8 | 22.34 ± 5.68 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.5 | 21.4 | 22.43 ± 5.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|