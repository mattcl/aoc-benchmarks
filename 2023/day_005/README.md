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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.7 | 1.03 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.33 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.32 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.1 | 1.06 ± 0.28 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.3 | 1.6 | 1.07 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.4 | 1.07 ± 0.30 |
| mattcl-ts | input-mikofo | 12.5 ± 0.4 | 11.6 | 13.6 | 14.37 ± 3.30 |
| mattcl-ts | input-chancalan | 12.8 ± 0.3 | 12.1 | 14.3 | 14.66 ± 3.36 |
| mattcl-ts | input-mattcl | 12.9 ± 0.5 | 11.5 | 14.3 | 14.78 ± 3.42 |
| mattcl-ts | input-kcen | 12.9 ± 0.3 | 12.1 | 13.8 | 14.84 ± 3.40 |
| mattcl-ts | input-lanjian | 13.8 ± 0.4 | 12.8 | 14.9 | 15.87 ± 3.64 |
| kcen | input-mattcl | 15.0 ± 0.6 | 13.8 | 18.2 | 17.15 ± 3.97 |
| kcen | input-mikofo | 15.0 ± 0.5 | 14.2 | 18.1 | 17.22 ± 3.97 |
| kcen | input-chancalan | 15.1 ± 0.6 | 14.4 | 18.0 | 17.33 ± 4.01 |
| pting | input-mattcl | 15.1 ± 0.5 | 13.9 | 18.3 | 17.35 ± 4.00 |
| pting | input-mikofo | 15.2 ± 0.6 | 14.1 | 18.3 | 17.37 ± 4.01 |
| kcen | input-kcen | 15.2 ± 0.5 | 14.1 | 18.1 | 17.47 ± 4.02 |
| chancalan | input-mattcl | 15.3 ± 0.6 | 14.0 | 18.5 | 17.52 ± 4.05 |
| chancalan | input-mikofo | 15.4 ± 0.7 | 14.4 | 18.7 | 17.59 ± 4.08 |
| pting | input-chancalan | 15.4 ± 0.5 | 14.3 | 18.3 | 17.65 ± 4.07 |
| mattcl-py | input-mikofo | 15.4 ± 0.7 | 14.2 | 18.8 | 17.70 ± 4.11 |
| mattcl-py | input-mattcl | 15.6 ± 0.8 | 14.3 | 18.8 | 17.91 ± 4.17 |
| chancalan | input-chancalan | 15.8 ± 0.7 | 14.9 | 19.1 | 18.05 ± 4.20 |
| pting | input-kcen | 16.0 ± 0.5 | 15.0 | 18.3 | 18.29 ± 4.21 |
| mattcl-py | input-chancalan | 16.0 ± 0.6 | 14.9 | 18.9 | 18.30 ± 4.23 |
| chancalan | input-kcen | 16.1 ± 0.5 | 15.0 | 18.5 | 18.49 ± 4.25 |
| kcen | input-lanjian | 16.2 ± 0.6 | 14.9 | 18.8 | 18.55 ± 4.29 |
| mattcl-py | input-kcen | 16.3 ± 0.8 | 15.2 | 20.0 | 18.67 ± 4.34 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.3 | 20.6 | 19.72 ± 4.57 |
| chancalan | input-lanjian | 17.5 ± 0.8 | 16.0 | 20.9 | 20.10 ± 4.68 |
| mattcl-py | input-lanjian | 17.9 ± 0.9 | 16.7 | 21.3 | 20.57 ± 4.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|