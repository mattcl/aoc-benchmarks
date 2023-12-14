# Day 7 benchmarks

[link to problem](https://adventofcode.com/2023/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

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
| lanjian | input-lanjian | 1.0 ± 0.3 | 0.3 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.36 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.2 | 1.6 | 1.09 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.2 | 1.6 | 1.09 ± 0.37 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.7 | 1.11 ± 0.35 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.6 | 1.7 | 1.12 ± 0.34 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.12 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.13 ± 0.35 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.6 | 1.14 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.14 ± 0.35 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 16.1 | 14.61 ± 3.99 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 14.2 | 16.3 | 14.62 ± 3.99 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.1 | 15.9 | 14.63 ± 3.99 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.2 | 15.9 | 14.63 ± 3.99 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.2 | 16.1 | 14.64 ± 4.00 |
| mattcl-py | input-lanjian | 16.8 ± 0.7 | 15.5 | 19.8 | 16.34 ± 4.50 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.7 | 19.9 | 16.36 ± 4.50 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.9 | 19.6 | 16.38 ± 4.51 |
| mattcl-py | input-pting | 16.8 ± 0.7 | 15.9 | 19.8 | 16.41 ± 4.52 |
| mattcl-py | input-chancalan | 16.9 ± 0.8 | 15.6 | 20.0 | 16.47 ± 4.54 |
| pting | input-chancalan | 17.3 ± 0.8 | 16.0 | 20.9 | 16.87 ± 4.65 |
| pting | input-kcen | 17.3 ± 0.6 | 16.1 | 20.3 | 16.89 ± 4.64 |
| pting | input-pting | 17.4 ± 0.8 | 16.4 | 20.9 | 16.93 ± 4.66 |
| pting | input-lanjian | 17.4 ± 1.6 | 16.4 | 35.2 | 16.98 ± 4.86 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.1 | 20.7 | 16.99 ± 4.68 |
| kcen | input-chancalan | 20.5 ± 0.7 | 19.4 | 24.1 | 20.01 ± 5.49 |
| kcen | input-kcen | 20.5 ± 0.8 | 19.5 | 23.9 | 20.03 ± 5.51 |
| kcen | input-mattcl | 20.6 ± 0.9 | 19.0 | 25.1 | 20.11 ± 5.54 |
| kcen | input-pting | 20.6 ± 0.7 | 19.1 | 23.6 | 20.14 ± 5.52 |
| kcen | input-lanjian | 21.3 ± 4.2 | 19.4 | 58.9 | 20.75 ± 6.97 |
| chancalan | input-chancalan | 24.6 ± 0.7 | 23.4 | 27.8 | 23.96 ± 6.55 |
| chancalan | input-kcen | 24.6 ± 0.7 | 23.4 | 26.9 | 24.02 ± 6.57 |
| chancalan | input-lanjian | 24.7 ± 0.8 | 23.6 | 28.1 | 24.11 ± 6.61 |
| chancalan | input-pting | 24.8 ± 0.8 | 23.4 | 27.8 | 24.17 ± 6.62 |
| chancalan | input-mattcl | 25.5 ± 5.5 | 23.4 | 68.7 | 24.90 ± 8.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|