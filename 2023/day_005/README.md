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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mikofo | 0.8 ± 2.4 | 0.1 | 33.8 | 1.07 ± 3.03 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.10 ± 0.36 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.3 | 1.11 ± 0.37 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.3 | 1.11 ± 0.39 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.13 ± 0.37 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.15 ± 0.38 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.16 ± 0.39 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.1 | 1.16 ± 0.36 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.17 ± 0.39 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.5 | 13.3 | 15.93 ± 4.38 |
| mattcl-ts | input-mikofo | 12.5 ± 0.3 | 11.6 | 13.3 | 15.95 ± 4.38 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.9 | 13.7 | 16.19 ± 4.45 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 12.0 | 13.8 | 16.25 ± 4.46 |
| mattcl-ts | input-lanjian | 13.6 ± 0.4 | 12.6 | 15.2 | 17.40 ± 4.78 |
| kcen | input-mattcl | 14.7 ± 0.5 | 13.7 | 18.2 | 18.74 ± 5.17 |
| kcen | input-chancalan | 14.8 ± 0.5 | 13.8 | 17.5 | 18.92 ± 5.21 |
| pting | input-mikofo | 15.0 ± 0.5 | 13.9 | 18.4 | 19.13 ± 5.27 |
| pting | input-mattcl | 15.0 ± 0.7 | 13.9 | 18.5 | 19.18 ± 5.32 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.0 | 18.1 | 19.24 ± 5.29 |
| kcen | input-mikofo | 15.1 ± 3.7 | 13.7 | 59.9 | 19.26 ± 7.07 |
| kcen | input-kcen | 15.1 ± 0.6 | 14.0 | 18.1 | 19.31 ± 5.33 |
| chancalan | input-mikofo | 15.1 ± 0.6 | 14.2 | 18.4 | 19.33 ± 5.34 |
| pting | input-chancalan | 15.1 ± 0.5 | 14.1 | 18.3 | 19.34 ± 5.33 |
| mattcl-py | input-mikofo | 15.2 ± 0.5 | 14.2 | 17.8 | 19.34 ± 5.32 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.3 | 18.3 | 19.39 ± 5.35 |
| chancalan | input-chancalan | 15.4 ± 0.6 | 14.4 | 18.0 | 19.62 ± 5.43 |
| mattcl-py | input-chancalan | 15.7 ± 0.7 | 14.7 | 18.5 | 20.00 ± 5.54 |
| pting | input-kcen | 15.7 ± 0.6 | 14.8 | 18.4 | 20.00 ± 5.51 |
| kcen | input-lanjian | 16.0 ± 0.6 | 14.9 | 18.8 | 20.37 ± 5.61 |
| chancalan | input-kcen | 16.0 ± 0.8 | 14.8 | 19.7 | 20.41 ± 5.66 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 15.0 | 18.9 | 20.47 ± 5.67 |
| pting | input-lanjian | 16.9 ± 0.7 | 16.1 | 19.7 | 21.60 ± 5.97 |
| chancalan | input-lanjian | 17.2 ± 0.7 | 16.1 | 20.4 | 21.93 ± 6.05 |
| mattcl-py | input-lanjian | 17.6 ± 0.8 | 16.6 | 20.9 | 22.49 ± 6.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|