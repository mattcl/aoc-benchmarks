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
| lanjian | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.4 | 1.00 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.3 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.26 |
| lanjian | input-chancalan | 1.0 ± 0.1 | 0.6 | 1.7 | 1.04 ± 0.24 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.4 | 1.6 | 1.05 ± 0.26 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.7 | 1.05 ± 0.24 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.2 | 1.06 ± 0.25 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.7 | 1.2 | 1.10 ± 0.22 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.4 | 1.3 | 1.11 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.6 | 1.2 | 1.11 ± 0.23 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.8 | 13.6 | 12.85 ± 2.32 |
| mattcl-ts | input-mikofo | 12.7 ± 0.4 | 11.8 | 14.0 | 12.86 ± 2.33 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 11.9 | 14.1 | 13.09 ± 2.37 |
| mattcl-ts | input-kcen | 13.5 ± 3.7 | 12.2 | 58.4 | 13.67 ± 4.46 |
| mattcl-ts | input-lanjian | 14.0 ± 0.4 | 13.1 | 15.2 | 14.15 ± 2.56 |
| kcen | input-mikofo | 15.0 ± 0.5 | 13.7 | 18.0 | 15.12 ± 2.75 |
| kcen | input-mattcl | 15.0 ± 0.6 | 13.8 | 18.1 | 15.13 ± 2.76 |
| kcen | input-chancalan | 15.1 ± 0.4 | 14.0 | 17.2 | 15.25 ± 2.76 |
| pting | input-mikofo | 15.1 ± 0.5 | 14.0 | 17.9 | 15.32 ± 2.78 |
| pting | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.2 | 15.44 ± 2.83 |
| chancalan | input-mattcl | 15.4 ± 0.6 | 14.5 | 17.9 | 15.53 ± 2.84 |
| chancalan | input-mikofo | 15.4 ± 0.6 | 14.3 | 18.1 | 15.56 ± 2.84 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.2 | 18.5 | 15.60 ± 2.85 |
| mattcl-py | input-mikofo | 15.4 ± 0.6 | 14.4 | 18.4 | 15.62 ± 2.86 |
| pting | input-chancalan | 15.7 ± 0.8 | 14.5 | 18.7 | 15.88 ± 2.94 |
| kcen | input-kcen | 15.8 ± 2.6 | 14.4 | 49.9 | 15.93 ± 3.86 |
| chancalan | input-chancalan | 15.8 ± 0.8 | 14.4 | 19.2 | 16.01 ± 2.97 |
| mattcl-py | input-chancalan | 16.0 ± 0.8 | 15.0 | 19.3 | 16.21 ± 3.00 |
| pting | input-kcen | 16.2 ± 0.8 | 15.0 | 19.1 | 16.41 ± 3.05 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.1 | 19.4 | 16.47 ± 3.03 |
| chancalan | input-kcen | 16.4 ± 0.7 | 15.1 | 19.4 | 16.59 ± 3.05 |
| mattcl-py | input-kcen | 16.8 ± 4.6 | 14.8 | 60.0 | 16.95 ± 5.53 |
| pting | input-lanjian | 17.5 ± 0.8 | 16.2 | 20.7 | 17.69 ± 3.27 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.3 | 21.0 | 17.74 ± 3.25 |
| mattcl-py | input-lanjian | 17.9 ± 0.8 | 17.0 | 21.5 | 18.14 ± 3.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|