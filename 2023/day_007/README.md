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
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.8 | 1.01 ± 0.21 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.7 | 2.0 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 2.0 | 1.02 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.6 | 1.7 | 1.04 ± 0.21 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.1 | 1.04 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 2.0 | 1.05 ± 0.24 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.2 | 16.2 | 12.48 ± 2.14 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.1 | 16.0 | 12.50 ± 2.15 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 13.9 | 16.2 | 12.53 ± 2.15 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.0 | 12.54 ± 2.15 |
| mattcl-ts | input-kcen | 15.4 ± 4.5 | 14.2 | 77.6 | 12.83 ± 4.36 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.6 | 19.7 | 14.00 ± 2.46 |
| mattcl-py | input-chancalan | 16.8 ± 0.5 | 15.9 | 20.1 | 14.02 ± 2.42 |
| mattcl-py | input-lanjian | 16.9 ± 0.5 | 15.7 | 19.7 | 14.06 ± 2.43 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 16.0 | 19.9 | 14.10 ± 2.47 |
| mattcl-py | input-mattcl | 17.0 ± 0.8 | 16.0 | 20.0 | 14.18 ± 2.50 |
| pting | input-kcen | 17.2 ± 0.7 | 16.0 | 20.0 | 14.36 ± 2.50 |
| pting | input-pting | 17.3 ± 0.6 | 16.3 | 20.3 | 14.41 ± 2.50 |
| pting | input-chancalan | 17.4 ± 0.7 | 16.3 | 20.7 | 14.44 ± 2.53 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.3 | 20.7 | 14.49 ± 2.53 |
| pting | input-lanjian | 17.5 ± 0.7 | 16.5 | 20.7 | 14.53 ± 2.53 |
| kcen | input-kcen | 20.5 ± 0.7 | 19.6 | 23.7 | 17.08 ± 2.96 |
| kcen | input-chancalan | 20.6 ± 0.7 | 19.4 | 23.3 | 17.12 ± 2.97 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.4 | 23.3 | 17.16 ± 2.97 |
| kcen | input-lanjian | 20.7 ± 0.7 | 19.6 | 23.2 | 17.21 ± 2.99 |
| kcen | input-pting | 20.7 ± 0.9 | 19.1 | 24.5 | 17.21 ± 3.02 |
| chancalan | input-chancalan | 24.6 ± 0.8 | 22.9 | 27.7 | 20.46 ± 3.55 |
| chancalan | input-lanjian | 24.7 ± 0.8 | 23.5 | 28.2 | 20.54 ± 3.56 |
| chancalan | input-mattcl | 24.7 ± 0.8 | 23.4 | 27.7 | 20.58 ± 3.57 |
| chancalan | input-kcen | 24.8 ± 0.9 | 23.4 | 28.2 | 20.62 ± 3.59 |
| chancalan | input-pting | 24.8 ± 1.0 | 23.5 | 28.0 | 20.67 ± 3.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|