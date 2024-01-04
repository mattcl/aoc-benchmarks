# Day 8 benchmarks

[link to problem](https://adventofcode.com/2023/day/8)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 8)

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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.0 | 1.00 ± 0.29 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.2 | 1.02 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.2 | 1.0 | 2.0 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.03 ± 0.29 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.2 | 1.06 ± 0.29 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.1 | 1.09 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.2 | 1.0 | 2.1 | 1.10 ± 0.29 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.4 | 15.8 | 11.88 ± 2.32 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.0 | 15.9 | 12.02 ± 2.35 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.2 | 16.2 | 12.05 ± 2.35 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 13.8 | 15.9 | 12.08 ± 2.36 |
| mattcl-ts | input-pting | 15.1 ± 0.2 | 14.5 | 16.6 | 12.08 ± 2.35 |
| pting | input-chancalan | 21.9 ± 0.6 | 20.8 | 25.3 | 17.54 ± 3.44 |
| mattcl-py | input-chancalan | 22.1 ± 0.7 | 21.3 | 24.7 | 17.69 ± 3.48 |
| pting | input-mattcl | 22.3 ± 0.6 | 21.4 | 25.3 | 17.87 ± 3.50 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.5 | 25.4 | 17.87 ± 3.52 |
| mattcl-py | input-lanjian | 22.7 ± 0.6 | 21.7 | 25.8 | 18.15 ± 3.56 |
| pting | input-lanjian | 22.7 ± 0.8 | 21.7 | 26.8 | 18.18 ± 3.59 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 22.0 | 25.8 | 18.24 ± 3.60 |
| pting | input-kcen | 22.8 ± 0.8 | 21.6 | 26.2 | 18.27 ± 3.61 |
| pting | input-pting | 22.9 ± 0.5 | 21.9 | 24.7 | 18.34 ± 3.59 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.0 | 26.3 | 18.48 ± 3.65 |
| chancalan | input-chancalan | 23.5 ± 0.8 | 22.3 | 26.9 | 18.79 ± 3.70 |
| chancalan | input-mattcl | 23.7 ± 0.8 | 22.3 | 26.8 | 18.97 ± 3.75 |
| chancalan | input-lanjian | 24.1 ± 0.7 | 23.0 | 26.3 | 19.28 ± 3.78 |
| chancalan | input-pting | 24.4 ± 0.7 | 23.3 | 27.9 | 19.55 ± 3.84 |
| chancalan | input-kcen | 24.4 ± 2.6 | 22.9 | 52.3 | 19.56 ± 4.34 |
| kcen | input-chancalan | 27.8 ± 0.9 | 26.8 | 31.2 | 22.27 ± 4.39 |
| kcen | input-mattcl | 28.2 ± 0.9 | 26.9 | 31.9 | 22.60 ± 4.45 |
| kcen | input-lanjian | 29.0 ± 0.8 | 27.8 | 32.3 | 23.19 ± 4.54 |
| kcen | input-kcen | 29.3 ± 0.8 | 27.9 | 32.3 | 23.44 ± 4.60 |
| kcen | input-pting | 29.6 ± 0.8 | 28.5 | 32.4 | 23.73 ± 4.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|