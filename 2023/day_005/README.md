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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.33 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.30 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.04 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.33 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.32 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.2 | 1.1 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.09 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.6 | 1.13 ± 0.32 |
| mattcl-ts | input-mikofo | 12.5 ± 0.4 | 11.5 | 13.2 | 14.45 ± 3.45 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.3 | 14.3 | 14.46 ± 3.46 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.7 | 13.5 | 14.62 ± 3.48 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.9 | 13.7 | 14.75 ± 3.51 |
| mattcl-ts | input-lanjian | 14.1 ± 4.4 | 12.9 | 60.1 | 16.40 ± 6.43 |
| kcen | input-mikofo | 14.7 ± 0.6 | 13.7 | 17.9 | 17.06 ± 4.10 |
| kcen | input-mattcl | 14.8 ± 0.6 | 13.8 | 17.8 | 17.16 ± 4.13 |
| kcen | input-chancalan | 14.9 ± 0.6 | 14.0 | 18.0 | 17.30 ± 4.15 |
| pting | input-mattcl | 15.0 ± 0.6 | 14.0 | 18.3 | 17.45 ± 4.20 |
| pting | input-mikofo | 15.0 ± 0.7 | 14.0 | 18.1 | 17.45 ± 4.21 |
| chancalan | input-mattcl | 15.1 ± 0.4 | 14.0 | 17.0 | 17.49 ± 4.18 |
| kcen | input-kcen | 15.1 ± 0.6 | 14.0 | 18.2 | 17.51 ± 4.20 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.2 | 17.64 ± 4.24 |
| chancalan | input-mikofo | 15.2 ± 0.8 | 14.1 | 18.3 | 17.67 ± 4.28 |
| pting | input-chancalan | 15.2 ± 0.6 | 14.1 | 18.4 | 17.69 ± 4.25 |
| mattcl-py | input-mikofo | 15.3 ± 0.6 | 14.6 | 18.2 | 17.70 ± 4.25 |
| chancalan | input-chancalan | 15.5 ± 0.7 | 14.4 | 19.1 | 17.94 ± 4.34 |
| mattcl-py | input-chancalan | 15.7 ± 0.7 | 14.7 | 18.7 | 18.21 ± 4.38 |
| pting | input-kcen | 15.8 ± 0.7 | 14.8 | 19.2 | 18.37 ± 4.43 |
| kcen | input-lanjian | 15.9 ± 0.6 | 15.0 | 19.4 | 18.48 ± 4.43 |
| mattcl-py | input-kcen | 16.0 ± 0.6 | 14.9 | 19.1 | 18.57 ± 4.45 |
| chancalan | input-kcen | 16.1 ± 0.7 | 15.0 | 19.2 | 18.70 ± 4.51 |
| pting | input-lanjian | 17.1 ± 2.9 | 15.8 | 54.1 | 19.89 ± 5.80 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.1 | 20.7 | 20.04 ± 4.83 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.4 | 20.6 | 20.48 ± 4.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|