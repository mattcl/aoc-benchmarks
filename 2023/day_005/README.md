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
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.41 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.6 | 1.02 ± 0.39 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.37 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.36 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.5 | 1.07 ± 0.38 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.6 | 1.08 ± 0.37 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.10 ± 0.41 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.11 ± 0.37 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.12 ± 0.40 |
| mattcl-ts | input-mikofo | 12.4 ± 0.4 | 11.3 | 13.3 | 15.25 ± 4.44 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.5 | 14.5 | 15.33 ± 4.46 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.7 | 15.59 ± 4.53 |
| mattcl-ts | input-kcen | 12.9 ± 0.3 | 12.3 | 13.7 | 15.82 ± 4.59 |
| mattcl-ts | input-lanjian | 13.7 ± 0.3 | 12.8 | 14.6 | 16.85 ± 4.89 |
| kcen | input-mikofo | 14.9 ± 0.5 | 13.7 | 17.6 | 18.26 ± 5.32 |
| kcen | input-mattcl | 15.0 ± 0.6 | 13.6 | 17.9 | 18.34 ± 5.35 |
| kcen | input-chancalan | 15.0 ± 0.6 | 13.7 | 18.2 | 18.45 ± 5.39 |
| pting | input-mikofo | 15.1 ± 0.4 | 13.9 | 17.9 | 18.47 ± 5.37 |
| pting | input-mattcl | 15.1 ± 0.6 | 13.8 | 18.2 | 18.48 ± 5.39 |
| chancalan | input-mikofo | 15.2 ± 0.5 | 14.0 | 18.5 | 18.58 ± 5.42 |
| chancalan | input-mattcl | 15.3 ± 0.6 | 14.3 | 18.2 | 18.74 ± 5.48 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.1 | 18.2 | 18.78 ± 5.49 |
| mattcl-py | input-mikofo | 15.3 ± 0.6 | 14.2 | 18.1 | 18.80 ± 5.48 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.4 | 18.8 | 18.91 ± 5.53 |
| pting | input-chancalan | 15.4 ± 0.6 | 14.1 | 17.9 | 18.93 ± 5.52 |
| chancalan | input-chancalan | 15.6 ± 0.6 | 14.7 | 18.7 | 19.11 ± 5.58 |
| mattcl-py | input-chancalan | 16.0 ± 0.6 | 14.9 | 18.5 | 19.58 ± 5.71 |
| pting | input-kcen | 16.0 ± 0.7 | 14.9 | 19.4 | 19.67 ± 5.76 |
| kcen | input-lanjian | 16.1 ± 0.6 | 14.8 | 19.4 | 19.76 ± 5.77 |
| mattcl-py | input-kcen | 16.2 ± 0.6 | 15.2 | 19.1 | 19.81 ± 5.77 |
| chancalan | input-kcen | 16.2 ± 0.6 | 14.8 | 19.6 | 19.84 ± 5.79 |
| pting | input-lanjian | 17.2 ± 0.6 | 16.0 | 20.7 | 21.05 ± 6.14 |
| chancalan | input-lanjian | 17.4 ± 0.7 | 16.2 | 20.8 | 21.29 ± 6.22 |
| mattcl-py | input-lanjian | 17.8 ± 0.7 | 17.0 | 20.9 | 21.81 ± 6.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|