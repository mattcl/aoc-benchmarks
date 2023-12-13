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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.00 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.21 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.22 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.04 ± 0.22 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.23 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.9 | 1.04 ± 0.23 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.05 ± 0.22 |
| mattcl | input-kcen | 1.5 ± 4.3 | 0.3 | 62.1 | 1.19 ± 3.53 |
| mattcl-ts | input-chancalan | 14.7 ± 0.4 | 13.7 | 15.7 | 12.01 ± 2.01 |
| mattcl-ts | input-kcen | 14.7 ± 0.3 | 13.9 | 15.7 | 12.03 ± 2.01 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.9 | 15.9 | 12.06 ± 2.01 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.9 | 16.1 | 12.06 ± 2.02 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 14.0 | 15.8 | 12.07 ± 2.01 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.6 | 20.3 | 13.75 ± 2.33 |
| mattcl-py | input-lanjian | 16.9 ± 0.7 | 15.7 | 20.1 | 13.78 ± 2.35 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 15.7 | 19.8 | 13.78 ± 2.34 |
| mattcl-py | input-kcen | 17.0 ± 0.7 | 16.0 | 19.7 | 13.91 ± 2.36 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.6 | 20.3 | 14.12 ± 2.39 |
| pting | input-mattcl | 17.3 ± 0.7 | 16.0 | 20.9 | 14.13 ± 2.40 |
| pting | input-kcen | 17.3 ± 0.5 | 16.3 | 19.9 | 14.14 ± 2.37 |
| pting | input-chancalan | 17.4 ± 0.7 | 16.3 | 20.6 | 14.20 ± 2.41 |
| pting | input-pting | 17.4 ± 0.6 | 16.2 | 19.7 | 14.22 ± 2.40 |
| mattcl-py | input-pting | 17.7 ± 5.1 | 15.8 | 54.5 | 14.44 ± 4.79 |
| kcen | input-chancalan | 20.5 ± 0.7 | 19.5 | 23.6 | 16.72 ± 2.82 |
| kcen | input-pting | 20.5 ± 0.7 | 19.2 | 23.6 | 16.74 ± 2.83 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.4 | 23.9 | 16.87 ± 2.84 |
| kcen | input-kcen | 20.7 ± 0.8 | 19.5 | 23.6 | 16.91 ± 2.87 |
| kcen | input-lanjian | 20.8 ± 0.7 | 19.5 | 24.0 | 16.97 ± 2.87 |
| chancalan | input-chancalan | 24.6 ± 0.7 | 23.5 | 27.5 | 20.11 ± 3.37 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.3 | 28.5 | 20.12 ± 3.38 |
| chancalan | input-mattcl | 24.7 ± 0.8 | 23.5 | 27.6 | 20.16 ± 3.39 |
| chancalan | input-kcen | 24.8 ± 0.8 | 23.7 | 27.3 | 20.21 ± 3.39 |
| chancalan | input-lanjian | 24.9 ± 0.8 | 23.7 | 27.4 | 20.30 ± 3.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|