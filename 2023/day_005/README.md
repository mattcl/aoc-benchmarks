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
| lanjian | input-chancalan | 0.7 ± 0.3 | 0.2 | 2.7 | 1.00 |
| mattcl | input-chancalan | 0.7 ± 0.3 | 0.2 | 1.5 | 1.01 ± 0.63 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.2 | 1.42 ± 0.67 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.3 | 1.2 | 1.44 ± 0.67 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.4 | 1.44 ± 0.69 |
| lanjian | input-mikofo | 1.0 ± 0.1 | 0.4 | 1.6 | 1.44 ± 0.67 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.2 | 1.45 ± 0.69 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.47 ± 0.69 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.5 | 1.47 ± 0.69 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.5 | 1.53 ± 0.71 |
| mattcl-ts | input-mikofo | 12.3 ± 0.4 | 11.0 | 13.2 | 17.93 ± 7.93 |
| mattcl-ts | input-mattcl | 12.3 ± 0.4 | 11.4 | 13.3 | 17.94 ± 7.94 |
| mattcl-ts | input-chancalan | 12.6 ± 0.4 | 11.8 | 13.6 | 18.42 ± 8.15 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 12.0 | 13.8 | 18.61 ± 8.22 |
| mattcl-ts | input-lanjian | 13.5 ± 0.4 | 12.7 | 14.5 | 19.73 ± 8.72 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.8 | 19.1 | 21.78 ± 9.66 |
| kcen | input-chancalan | 15.1 ± 0.6 | 14.1 | 18.3 | 22.00 ± 9.75 |
| pting | input-mikofo | 15.1 ± 0.6 | 14.0 | 17.9 | 22.13 ± 9.80 |
| pting | input-mattcl | 15.2 ± 0.5 | 14.5 | 18.3 | 22.16 ± 9.81 |
| kcen | input-mattcl | 15.2 ± 3.8 | 13.7 | 59.4 | 22.20 ± 11.24 |
| chancalan | input-mikofo | 15.3 ± 0.7 | 14.2 | 18.3 | 22.31 ± 9.89 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.3 | 18.3 | 22.33 ± 9.90 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.3 | 18.0 | 22.40 ± 9.92 |
| mattcl-py | input-mikofo | 15.4 ± 0.6 | 14.4 | 18.5 | 22.46 ± 9.95 |
| pting | input-chancalan | 15.4 ± 0.7 | 14.3 | 18.7 | 22.52 ± 9.99 |
| chancalan | input-chancalan | 15.6 ± 0.6 | 14.8 | 18.2 | 22.77 ± 10.08 |
| chancalan | input-mattcl | 15.8 ± 4.3 | 14.3 | 69.4 | 23.09 ± 12.00 |
| pting | input-kcen | 15.9 ± 0.5 | 15.0 | 18.3 | 23.22 ± 10.27 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.6 | 19.3 | 23.24 ± 10.31 |
| kcen | input-lanjian | 16.1 ± 0.6 | 15.0 | 19.7 | 23.53 ± 10.42 |
| mattcl-py | input-kcen | 16.1 ± 0.7 | 15.1 | 19.2 | 23.60 ± 10.46 |
| chancalan | input-kcen | 16.1 ± 0.6 | 15.0 | 19.5 | 23.60 ± 10.45 |
| pting | input-lanjian | 17.2 ± 1.0 | 15.9 | 26.8 | 25.12 ± 11.18 |
| chancalan | input-lanjian | 17.4 ± 0.7 | 16.3 | 20.8 | 25.41 ± 11.26 |
| mattcl-py | input-lanjian | 17.7 ± 0.6 | 16.8 | 20.8 | 25.89 ± 11.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|