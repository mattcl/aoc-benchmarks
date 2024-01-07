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
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.24 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.23 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.22 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.9 | 1.03 ± 0.23 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.4 | 1.7 | 1.04 ± 0.21 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.9 | 1.05 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.21 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.7 | 1.05 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.23 |
| mattcl-ts | input-chancalan | 14.5 ± 0.4 | 13.7 | 15.8 | 12.27 ± 2.09 |
| mattcl-ts | input-lanjian | 14.5 ± 0.4 | 13.4 | 15.7 | 12.29 ± 2.10 |
| mattcl-ts | input-pting | 14.6 ± 0.4 | 13.8 | 15.8 | 12.34 ± 2.10 |
| mattcl-ts | input-kcen | 14.6 ± 0.4 | 13.7 | 15.7 | 12.35 ± 2.10 |
| mattcl-ts | input-mattcl | 14.6 ± 0.3 | 13.8 | 15.7 | 12.35 ± 2.10 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.2 | 19.7 | 13.97 ± 2.40 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.6 | 19.7 | 13.99 ± 2.41 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.5 | 20.3 | 14.00 ± 2.43 |
| mattcl-py | input-kcen | 16.6 ± 0.8 | 15.5 | 19.6 | 14.02 ± 2.45 |
| mattcl-py | input-pting | 16.7 ± 0.8 | 15.5 | 20.1 | 14.11 ± 2.46 |
| pting | input-mattcl | 17.0 ± 0.5 | 16.0 | 19.6 | 14.36 ± 2.46 |
| pting | input-chancalan | 17.0 ± 0.7 | 15.7 | 20.3 | 14.36 ± 2.49 |
| pting | input-kcen | 17.0 ± 0.7 | 15.9 | 19.9 | 14.38 ± 2.50 |
| pting | input-pting | 17.1 ± 0.6 | 16.2 | 20.5 | 14.42 ± 2.49 |
| pting | input-lanjian | 17.1 ± 1.0 | 16.0 | 25.5 | 14.48 ± 2.58 |
| kcen | input-lanjian | 20.3 ± 0.6 | 19.3 | 22.6 | 17.12 ± 2.93 |
| kcen | input-pting | 20.3 ± 0.6 | 19.2 | 22.6 | 17.13 ± 2.92 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.4 | 22.9 | 17.16 ± 2.95 |
| kcen | input-chancalan | 20.4 ± 0.8 | 19.2 | 23.0 | 17.25 ± 2.99 |
| kcen | input-mattcl | 21.3 ± 7.3 | 19.1 | 80.8 | 18.03 ± 6.87 |
| chancalan | input-chancalan | 24.4 ± 0.7 | 23.5 | 27.1 | 20.62 ± 3.53 |
| chancalan | input-lanjian | 24.4 ± 0.8 | 23.5 | 27.2 | 20.62 ± 3.54 |
| chancalan | input-pting | 24.4 ± 0.7 | 23.2 | 27.2 | 20.66 ± 3.53 |
| chancalan | input-kcen | 24.6 ± 1.0 | 23.0 | 27.3 | 20.78 ± 3.59 |
| chancalan | input-mattcl | 24.7 ± 1.3 | 23.2 | 33.8 | 20.87 ± 3.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|