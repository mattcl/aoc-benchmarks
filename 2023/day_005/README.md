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
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.32 |
| lanjian | input-mikofo | 0.9 ± 0.1 | 0.4 | 1.1 | 1.05 ± 0.29 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.31 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.30 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.3 | 1.10 ± 0.31 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.1 | 1.10 ± 0.31 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.12 ± 0.31 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.5 | 13.3 | 14.42 ± 3.34 |
| mattcl-ts | input-mikofo | 12.5 ± 0.4 | 11.6 | 13.6 | 14.45 ± 3.35 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 14.1 | 14.60 ± 3.38 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 11.9 | 13.6 | 14.78 ± 3.42 |
| mattcl-ts | input-lanjian | 13.7 ± 0.4 | 12.8 | 15.9 | 15.85 ± 3.67 |
| kcen | input-mikofo | 14.7 ± 0.6 | 13.7 | 18.6 | 16.97 ± 3.97 |
| kcen | input-mattcl | 14.9 ± 0.7 | 13.8 | 18.0 | 17.13 ± 4.03 |
| kcen | input-chancalan | 15.0 ± 0.6 | 13.9 | 18.0 | 17.33 ± 4.05 |
| pting | input-mattcl | 15.0 ± 0.5 | 14.1 | 17.6 | 17.34 ± 4.02 |
| pting | input-mikofo | 15.1 ± 0.6 | 14.2 | 18.3 | 17.37 ± 4.05 |
| chancalan | input-mikofo | 15.1 ± 0.5 | 14.1 | 18.1 | 17.44 ± 4.06 |
| kcen | input-kcen | 15.2 ± 0.6 | 14.2 | 18.3 | 17.50 ± 4.07 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.4 | 18.3 | 17.51 ± 4.08 |
| mattcl-py | input-mikofo | 15.2 ± 0.6 | 14.3 | 18.2 | 17.56 ± 4.10 |
| mattcl-py | input-mattcl | 15.3 ± 0.7 | 14.2 | 18.2 | 17.60 ± 4.12 |
| pting | input-chancalan | 15.3 ± 0.6 | 14.4 | 18.3 | 17.64 ± 4.12 |
| chancalan | input-chancalan | 15.5 ± 0.6 | 14.7 | 19.2 | 17.82 ± 4.16 |
| mattcl-py | input-chancalan | 15.8 ± 0.8 | 14.7 | 18.7 | 18.24 ± 4.28 |
| pting | input-kcen | 15.9 ± 0.6 | 14.9 | 18.7 | 18.30 ± 4.26 |
| mattcl-py | input-kcen | 16.1 ± 0.6 | 15.1 | 19.1 | 18.61 ± 4.34 |
| chancalan | input-kcen | 16.2 ± 0.7 | 14.9 | 19.3 | 18.65 ± 4.37 |
| kcen | input-lanjian | 16.2 ± 2.5 | 14.8 | 48.8 | 18.69 ± 5.16 |
| pting | input-lanjian | 17.0 ± 0.5 | 16.2 | 20.2 | 19.60 ± 4.54 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.4 | 20.6 | 20.13 ± 4.70 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 17.0 | 20.7 | 20.34 ± 4.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|