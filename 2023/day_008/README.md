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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.33 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.33 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.32 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.07 ± 0.33 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.07 ± 0.33 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.09 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.33 |
| lanjian | input-pting | 1.4 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.35 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 16.2 | 12.53 ± 2.86 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.4 | 16.4 | 12.69 ± 2.89 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.5 | 16.5 | 12.71 ± 2.90 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.3 | 16.4 | 12.77 ± 2.91 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.6 | 16.6 | 12.78 ± 2.92 |
| mattcl-py | input-chancalan | 22.3 ± 0.7 | 21.3 | 25.1 | 18.60 ± 4.26 |
| pting | input-chancalan | 22.3 ± 0.8 | 21.3 | 25.2 | 18.62 ± 4.27 |
| pting | input-mattcl | 22.5 ± 0.9 | 21.5 | 25.7 | 18.74 ± 4.31 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.4 | 25.9 | 18.75 ± 4.30 |
| pting | input-kcen | 22.9 ± 0.8 | 21.6 | 25.8 | 19.06 ± 4.37 |
| mattcl-py | input-lanjian | 22.9 ± 0.7 | 21.8 | 25.8 | 19.08 ± 4.37 |
| pting | input-pting | 23.0 ± 0.7 | 21.8 | 26.0 | 19.16 ± 4.38 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.8 | 28.4 | 19.16 ± 4.41 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 21.9 | 26.9 | 19.16 ± 4.38 |
| mattcl-py | input-pting | 23.2 ± 0.7 | 22.3 | 26.1 | 19.34 ± 4.42 |
| chancalan | input-chancalan | 23.6 ± 0.7 | 22.2 | 26.4 | 19.65 ± 4.50 |
| chancalan | input-mattcl | 23.8 ± 0.9 | 22.5 | 27.8 | 19.84 ± 4.56 |
| chancalan | input-lanjian | 24.4 ± 0.8 | 23.3 | 27.4 | 20.30 ± 4.64 |
| chancalan | input-pting | 24.7 ± 0.9 | 23.5 | 27.7 | 20.57 ± 4.72 |
| chancalan | input-kcen | 24.9 ± 3.7 | 23.4 | 64.5 | 20.76 ± 5.64 |
| kcen | input-chancalan | 28.3 ± 1.1 | 26.6 | 31.6 | 23.55 ± 5.41 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.0 | 30.9 | 23.61 ± 5.40 |
| kcen | input-lanjian | 29.4 ± 0.9 | 28.1 | 32.6 | 24.48 ± 5.60 |
| kcen | input-pting | 29.8 ± 1.4 | 28.2 | 40.8 | 24.86 ± 5.76 |
| kcen | input-kcen | 29.8 ± 4.0 | 27.8 | 63.8 | 24.86 ± 6.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|