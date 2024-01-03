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
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.5 | 1.8 | 1.00 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.5 | 1.9 | 1.09 ± 0.32 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 1.9 | 1.11 ± 0.32 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.9 | 1.11 ± 0.31 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.5 | 1.9 | 1.11 ± 0.32 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.5 | 1.9 | 1.12 ± 0.32 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.1 | 1.12 ± 0.31 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.9 | 1.13 ± 0.31 |
| lanjian | input-chancalan | 1.5 ± 0.1 | 0.9 | 1.9 | 1.15 ± 0.31 |
| lanjian | input-pting | 1.5 ± 0.2 | 0.9 | 2.2 | 1.17 ± 0.33 |
| mattcl-ts | input-chancalan | 15.2 ± 0.3 | 14.2 | 16.2 | 12.06 ± 2.99 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.2 | 16.1 | 12.07 ± 2.99 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.5 | 16.5 | 12.10 ± 3.00 |
| mattcl-ts | input-lanjian | 15.2 ± 0.3 | 14.5 | 16.6 | 12.12 ± 3.01 |
| mattcl-ts | input-mattcl | 15.5 ± 2.7 | 14.5 | 53.1 | 12.37 ± 3.75 |
| mattcl-py | input-lanjian | 16.9 ± 0.7 | 15.6 | 20.0 | 13.43 ± 3.36 |
| mattcl-py | input-kcen | 16.9 ± 0.6 | 16.1 | 19.3 | 13.46 ± 3.36 |
| mattcl-py | input-pting | 17.0 ± 0.7 | 15.8 | 20.3 | 13.50 ± 3.38 |
| mattcl-py | input-mattcl | 17.0 ± 0.8 | 15.9 | 20.2 | 13.53 ± 3.40 |
| mattcl-py | input-chancalan | 17.1 ± 1.2 | 16.1 | 30.2 | 13.63 ± 3.50 |
| pting | input-mattcl | 17.4 ± 0.6 | 16.1 | 19.8 | 13.81 ± 3.44 |
| pting | input-kcen | 17.4 ± 0.7 | 16.0 | 21.1 | 13.85 ± 3.47 |
| pting | input-pting | 17.5 ± 0.7 | 16.1 | 20.8 | 13.88 ± 3.48 |
| pting | input-chancalan | 17.6 ± 0.7 | 16.6 | 20.9 | 13.96 ± 3.50 |
| pting | input-lanjian | 17.6 ± 0.8 | 16.4 | 21.0 | 13.97 ± 3.50 |
| kcen | input-lanjian | 20.7 ± 0.7 | 19.5 | 25.1 | 16.46 ± 4.10 |
| kcen | input-pting | 20.8 ± 0.7 | 19.4 | 23.4 | 16.51 ± 4.12 |
| kcen | input-kcen | 20.8 ± 0.7 | 19.7 | 23.9 | 16.53 ± 4.12 |
| kcen | input-mattcl | 20.8 ± 0.7 | 19.9 | 23.5 | 16.54 ± 4.12 |
| kcen | input-chancalan | 21.2 ± 4.1 | 19.4 | 56.4 | 16.89 ± 5.30 |
| chancalan | input-lanjian | 24.8 ± 0.7 | 23.6 | 27.2 | 19.71 ± 4.90 |
| chancalan | input-mattcl | 24.8 ± 0.8 | 23.2 | 28.2 | 19.74 ± 4.91 |
| chancalan | input-pting | 24.8 ± 0.9 | 23.3 | 28.0 | 19.74 ± 4.92 |
| chancalan | input-kcen | 24.9 ± 0.8 | 23.7 | 28.1 | 19.80 ± 4.93 |
| chancalan | input-chancalan | 25.4 ± 3.7 | 23.8 | 64.5 | 20.18 ± 5.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|