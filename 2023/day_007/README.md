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
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.23 |
| lanjian | input-kcen | 1.1 ± 0.1 | 0.3 | 1.7 | 1.04 ± 0.21 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 2.0 | 1.05 ± 0.22 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 2.6 | 1.07 ± 0.26 |
| mattcl | input-kcen | 1.2 ± 3.5 | 0.2 | 50.1 | 1.08 ± 3.16 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 13.9 | 15.8 | 13.51 ± 2.14 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 14.1 | 15.8 | 13.53 ± 2.14 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.1 | 16.3 | 13.57 ± 2.15 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.0 | 15.8 | 13.59 ± 2.15 |
| mattcl-ts | input-kcen | 15.3 ± 3.7 | 13.9 | 65.2 | 13.84 ± 3.97 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.8 | 19.7 | 15.15 ± 2.43 |
| mattcl-py | input-kcen | 16.7 ± 0.7 | 15.4 | 19.7 | 15.15 ± 2.45 |
| mattcl-py | input-mattcl | 16.9 ± 0.7 | 15.6 | 20.1 | 15.27 ± 2.48 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 15.9 | 20.4 | 15.29 ± 2.48 |
| pting | input-mattcl | 17.2 ± 0.6 | 16.2 | 20.2 | 15.54 ± 2.49 |
| pting | input-lanjian | 17.2 ± 0.6 | 16.2 | 20.3 | 15.60 ± 2.50 |
| pting | input-chancalan | 17.2 ± 0.7 | 16.3 | 20.3 | 15.62 ± 2.52 |
| pting | input-pting | 17.3 ± 0.7 | 16.4 | 20.2 | 15.64 ± 2.52 |
| pting | input-kcen | 17.3 ± 0.6 | 16.3 | 20.9 | 15.69 ± 2.53 |
| mattcl-py | input-chancalan | 17.5 ± 4.9 | 15.8 | 62.3 | 15.82 ± 5.05 |
| kcen | input-chancalan | 20.4 ± 0.8 | 19.1 | 23.5 | 18.43 ± 2.97 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.1 | 23.2 | 18.54 ± 2.97 |
| kcen | input-lanjian | 20.6 ± 0.8 | 19.3 | 23.9 | 18.64 ± 3.00 |
| kcen | input-pting | 20.6 ± 0.7 | 19.5 | 23.3 | 18.68 ± 3.00 |
| kcen | input-kcen | 20.8 ± 3.6 | 19.2 | 60.5 | 18.88 ± 4.37 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.5 | 28.1 | 22.16 ± 3.54 |
| chancalan | input-chancalan | 24.5 ± 0.8 | 23.2 | 27.3 | 22.21 ± 3.56 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 23.3 | 27.6 | 22.29 ± 3.57 |
| chancalan | input-pting | 24.7 ± 0.6 | 23.5 | 27.4 | 22.34 ± 3.54 |
| chancalan | input-lanjian | 24.7 ± 0.9 | 23.4 | 27.9 | 22.34 ± 3.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|