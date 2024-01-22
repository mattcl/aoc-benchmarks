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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.6 | 1.04 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.04 ± 0.31 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.33 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.07 ± 0.31 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.10 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.11 ± 0.31 |
| mattcl-ts | input-mikofo | 11.9 ± 0.4 | 10.7 | 12.8 | 14.20 ± 3.22 |
| mattcl-ts | input-mattcl | 11.9 ± 0.4 | 10.7 | 13.1 | 14.25 ± 3.23 |
| mattcl-ts | input-chancalan | 12.1 ± 0.4 | 11.1 | 13.5 | 14.52 ± 3.29 |
| mattcl-ts | input-kcen | 12.4 ± 0.4 | 11.2 | 13.1 | 14.77 ± 3.34 |
| mattcl-ts | input-lanjian | 13.0 ± 0.4 | 11.7 | 14.0 | 15.54 ± 3.51 |
| kcen | input-mikofo | 14.9 ± 0.5 | 13.7 | 17.9 | 17.84 ± 4.04 |
| kcen | input-mattcl | 15.0 ± 0.6 | 13.9 | 17.6 | 17.94 ± 4.07 |
| kcen | input-chancalan | 15.0 ± 0.4 | 14.2 | 17.5 | 17.95 ± 4.04 |
| pting | input-mattcl | 15.1 ± 0.5 | 13.9 | 17.9 | 18.03 ± 4.07 |
| pting | input-mikofo | 15.1 ± 0.7 | 14.2 | 18.3 | 18.11 ± 4.13 |
| chancalan | input-mikofo | 15.3 ± 0.7 | 14.3 | 19.0 | 18.30 ± 4.17 |
| chancalan | input-mattcl | 15.3 ± 0.7 | 14.3 | 18.3 | 18.34 ± 4.19 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.3 | 18.1 | 18.36 ± 4.18 |
| mattcl-py | input-mikofo | 15.4 ± 0.8 | 14.1 | 19.0 | 18.48 ± 4.23 |
| mattcl-py | input-mattcl | 15.5 ± 0.7 | 14.5 | 18.5 | 18.52 ± 4.22 |
| pting | input-chancalan | 15.5 ± 0.7 | 14.2 | 19.0 | 18.53 ± 4.23 |
| chancalan | input-chancalan | 15.6 ± 0.6 | 14.5 | 18.5 | 18.67 ± 4.24 |
| mattcl-py | input-chancalan | 16.0 ± 0.7 | 14.5 | 19.5 | 19.14 ± 4.37 |
| pting | input-kcen | 16.0 ± 0.7 | 15.0 | 19.5 | 19.17 ± 4.37 |
| kcen | input-lanjian | 16.1 ± 0.5 | 15.1 | 19.0 | 19.31 ± 4.36 |
| chancalan | input-kcen | 16.3 ± 0.8 | 14.8 | 19.4 | 19.47 ± 4.45 |
| mattcl-py | input-kcen | 16.3 ± 0.6 | 15.3 | 18.9 | 19.47 ± 4.42 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.1 | 20.5 | 20.69 ± 4.71 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.4 | 20.6 | 20.99 ± 4.78 |
| mattcl-py | input-lanjian | 17.8 ± 0.6 | 17.0 | 20.9 | 21.33 ± 4.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|