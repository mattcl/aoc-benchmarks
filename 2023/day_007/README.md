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
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.29 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.27 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.28 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.2 | 1.7 | 1.08 ± 0.30 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.08 ± 0.27 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.09 ± 0.27 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.10 ± 0.28 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.6 | 1.9 | 1.10 ± 0.27 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 2.1 | 1.10 ± 0.31 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 14.0 | 16.1 | 13.82 ± 2.88 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 13.9 | 16.1 | 13.89 ± 2.89 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.0 | 16.4 | 13.90 ± 2.90 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.0 | 15.9 | 13.92 ± 2.90 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.0 | 16.0 | 13.93 ± 2.90 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.8 | 19.6 | 15.43 ± 3.24 |
| mattcl-py | input-chancalan | 16.7 ± 0.8 | 15.6 | 20.2 | 15.48 ± 3.28 |
| mattcl-py | input-kcen | 16.7 ± 0.7 | 15.7 | 20.4 | 15.50 ± 3.28 |
| mattcl-py | input-pting | 16.8 ± 0.7 | 15.7 | 20.1 | 15.62 ± 3.30 |
| mattcl-py | input-mattcl | 16.9 ± 2.3 | 15.6 | 45.6 | 15.70 ± 3.88 |
| pting | input-kcen | 17.1 ± 0.6 | 15.7 | 20.1 | 15.86 ± 3.33 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.1 | 20.0 | 15.90 ± 3.34 |
| pting | input-chancalan | 17.1 ± 0.7 | 15.9 | 19.9 | 15.90 ± 3.34 |
| pting | input-mattcl | 17.2 ± 0.8 | 15.6 | 21.0 | 15.93 ± 3.38 |
| pting | input-pting | 17.3 ± 0.8 | 16.1 | 20.2 | 16.06 ± 3.40 |
| kcen | input-pting | 20.5 ± 0.7 | 19.2 | 24.4 | 19.03 ± 3.99 |
| kcen | input-kcen | 20.5 ± 0.5 | 19.3 | 22.2 | 19.05 ± 3.97 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.5 | 24.3 | 19.08 ± 4.00 |
| kcen | input-chancalan | 20.6 ± 0.8 | 19.4 | 23.5 | 19.10 ± 4.02 |
| kcen | input-lanjian | 20.6 ± 0.8 | 19.1 | 23.4 | 19.16 ± 4.03 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 22.8 | 28.2 | 22.79 ± 4.77 |
| chancalan | input-chancalan | 24.6 ± 0.7 | 23.1 | 27.0 | 22.83 ± 4.77 |
| chancalan | input-lanjian | 24.7 ± 0.9 | 23.3 | 28.3 | 22.91 ± 4.82 |
| chancalan | input-kcen | 24.7 ± 0.7 | 23.3 | 27.6 | 22.94 ± 4.79 |
| chancalan | input-pting | 24.8 ± 0.9 | 23.5 | 28.0 | 22.99 ± 4.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|