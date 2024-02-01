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
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.6 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.27 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.2 | 1.03 ± 0.26 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.27 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.7 | 1.04 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.28 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.4 | 1.04 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.8 | 1.06 ± 0.30 |
| mattcl-ts | input-mikofo | 12.3 ± 0.4 | 11.3 | 13.5 | 13.36 ± 2.78 |
| mattcl-ts | input-mattcl | 12.3 ± 0.4 | 11.0 | 13.5 | 13.37 ± 2.79 |
| mattcl-ts | input-chancalan | 12.5 ± 0.3 | 11.5 | 13.8 | 13.62 ± 2.83 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.8 | 13.4 | 13.76 ± 2.85 |
| mattcl-ts | input-lanjian | 13.4 ± 0.4 | 12.3 | 14.4 | 14.64 ± 3.04 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.6 | 17.5 | 16.27 ± 3.41 |
| kcen | input-mattcl | 15.0 ± 0.6 | 13.8 | 17.6 | 16.41 ± 3.43 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.2 | 17.9 | 16.57 ± 3.46 |
| pting | input-mikofo | 15.2 ± 0.6 | 14.2 | 18.1 | 16.57 ± 3.47 |
| kcen | input-chancalan | 15.2 ± 0.7 | 14.0 | 18.4 | 16.57 ± 3.50 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.5 | 18.8 | 16.68 ± 3.51 |
| chancalan | input-mattcl | 15.4 ± 0.6 | 14.2 | 18.2 | 16.76 ± 3.52 |
| mattcl-py | input-mikofo | 15.4 ± 0.6 | 14.4 | 18.4 | 16.77 ± 3.52 |
| chancalan | input-mikofo | 15.4 ± 0.7 | 14.3 | 18.3 | 16.77 ± 3.52 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.3 | 18.1 | 16.83 ± 3.53 |
| pting | input-chancalan | 15.4 ± 0.6 | 14.4 | 18.5 | 16.84 ± 3.52 |
| chancalan | input-chancalan | 15.7 ± 0.7 | 14.6 | 18.4 | 17.09 ± 3.59 |
| mattcl-py | input-chancalan | 15.8 ± 0.7 | 14.5 | 19.4 | 17.27 ± 3.63 |
| pting | input-kcen | 16.0 ± 0.6 | 15.1 | 18.6 | 17.43 ± 3.65 |
| mattcl-py | input-kcen | 16.2 ± 0.6 | 14.9 | 18.8 | 17.68 ± 3.70 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.4 | 19.1 | 17.73 ± 3.71 |
| chancalan | input-kcen | 16.3 ± 0.6 | 14.9 | 19.3 | 17.73 ± 3.71 |
| pting | input-lanjian | 17.2 ± 0.8 | 16.2 | 20.7 | 18.80 ± 3.95 |
| chancalan | input-lanjian | 17.5 ± 0.6 | 16.5 | 20.7 | 19.05 ± 3.98 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.9 | 21.2 | 19.33 ± 4.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|