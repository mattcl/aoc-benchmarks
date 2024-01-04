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
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.5 | 1.05 ± 0.34 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.05 ± 0.32 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.5 | 1.06 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.07 ± 0.33 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.3 | 1.1 | 1.07 ± 0.31 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.5 | 1.10 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.5 | 1.13 ± 0.34 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.7 | 1.15 ± 0.35 |
| mattcl-ts | input-mikofo | 12.5 ± 0.4 | 11.5 | 13.7 | 15.43 ± 3.71 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.6 | 15.49 ± 3.72 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.9 | 13.9 | 15.82 ± 3.80 |
| mattcl-ts | input-kcen | 13.6 ± 4.7 | 12.1 | 64.3 | 16.76 ± 7.03 |
| mattcl-ts | input-lanjian | 13.8 ± 0.3 | 13.0 | 14.7 | 17.04 ± 4.09 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.9 | 17.8 | 18.37 ± 4.44 |
| kcen | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.1 | 18.43 ± 4.46 |
| pting | input-mattcl | 15.1 ± 0.5 | 14.0 | 17.8 | 18.59 ± 4.48 |
| kcen | input-chancalan | 15.1 ± 0.6 | 14.0 | 18.2 | 18.62 ± 4.50 |
| pting | input-mikofo | 15.2 ± 0.6 | 13.9 | 17.8 | 18.77 ± 4.54 |
| chancalan | input-mikofo | 15.3 ± 0.6 | 14.3 | 18.4 | 18.88 ± 4.57 |
| mattcl-py | input-mikofo | 15.4 ± 0.5 | 14.5 | 18.0 | 18.94 ± 4.56 |
| chancalan | input-mattcl | 15.4 ± 0.7 | 14.1 | 18.6 | 18.98 ± 4.62 |
| mattcl-py | input-mattcl | 15.5 ± 0.6 | 14.2 | 18.4 | 19.06 ± 4.62 |
| chancalan | input-chancalan | 15.7 ± 0.6 | 14.7 | 18.8 | 19.31 ± 4.67 |
| kcen | input-kcen | 15.8 ± 4.1 | 14.1 | 63.2 | 19.42 ± 6.88 |
| pting | input-chancalan | 15.9 ± 3.2 | 14.7 | 58.1 | 19.63 ± 6.12 |
| mattcl-py | input-chancalan | 16.0 ± 0.7 | 15.0 | 19.1 | 19.71 ± 4.78 |
| pting | input-kcen | 16.1 ± 0.6 | 14.9 | 18.8 | 19.82 ± 4.80 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.0 | 20.05 ± 4.87 |
| mattcl-py | input-kcen | 16.5 ± 3.2 | 14.8 | 56.9 | 20.35 ± 6.25 |
| chancalan | input-kcen | 16.6 ± 3.6 | 14.9 | 63.8 | 20.43 ± 6.61 |
| pting | input-lanjian | 17.3 ± 0.7 | 15.8 | 20.3 | 21.29 ± 5.16 |
| chancalan | input-lanjian | 17.4 ± 0.7 | 16.3 | 20.8 | 21.50 ± 5.20 |
| mattcl-py | input-lanjian | 17.9 ± 0.8 | 17.1 | 21.5 | 22.04 ± 5.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|