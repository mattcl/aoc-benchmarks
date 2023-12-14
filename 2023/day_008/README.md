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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.07 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.10 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.4 | 1.11 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.15 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.16 ± 0.34 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 16.3 | 12.93 ± 2.65 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.4 | 16.8 | 13.03 ± 2.67 |
| mattcl-ts | input-lanjian | 15.2 ± 0.3 | 14.5 | 16.3 | 13.09 ± 2.68 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.6 | 17.0 | 13.17 ± 2.70 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.6 | 16.4 | 13.19 ± 2.70 |
| pting | input-chancalan | 22.2 ± 0.6 | 21.1 | 24.6 | 19.05 ± 3.91 |
| mattcl-py | input-chancalan | 22.3 ± 0.8 | 21.4 | 25.2 | 19.15 ± 3.95 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.5 | 25.5 | 19.22 ± 3.95 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.3 | 25.4 | 19.33 ± 3.99 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.8 | 26.0 | 19.62 ± 4.04 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.7 | 26.6 | 19.64 ± 4.05 |
| pting | input-kcen | 22.9 ± 0.7 | 21.8 | 26.2 | 19.70 ± 4.05 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 22.0 | 26.2 | 19.78 ± 4.08 |
| pting | input-pting | 23.2 ± 0.7 | 21.8 | 26.0 | 19.93 ± 4.10 |
| mattcl-py | input-pting | 23.2 ± 0.7 | 22.2 | 25.6 | 19.95 ± 4.10 |
| chancalan | input-chancalan | 23.7 ± 0.8 | 22.7 | 26.8 | 20.35 ± 4.19 |
| chancalan | input-mattcl | 23.7 ± 0.6 | 22.7 | 26.4 | 20.41 ± 4.19 |
| chancalan | input-lanjian | 24.4 ± 0.9 | 23.0 | 27.6 | 21.00 ± 4.34 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.3 | 27.3 | 21.02 ± 4.33 |
| chancalan | input-pting | 24.8 ± 0.9 | 23.4 | 27.6 | 21.32 ± 4.40 |
| kcen | input-chancalan | 28.2 ± 0.9 | 26.7 | 31.2 | 24.22 ± 4.99 |
| kcen | input-mattcl | 28.3 ± 0.8 | 26.9 | 31.1 | 24.31 ± 5.00 |
| kcen | input-kcen | 29.1 ± 0.7 | 28.2 | 31.3 | 25.05 ± 5.13 |
| kcen | input-lanjian | 29.3 ± 1.0 | 28.1 | 32.7 | 25.21 ± 5.20 |
| kcen | input-pting | 29.8 ± 0.8 | 28.2 | 33.0 | 25.58 ± 5.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|