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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.03 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.21 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.21 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 2.1 | 1.07 ± 0.24 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.2 | 15.8 | 12.74 ± 2.06 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.0 | 16.2 | 12.76 ± 2.07 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.3 | 16.0 | 12.77 ± 2.07 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 14.1 | 16.0 | 12.79 ± 2.07 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 13.9 | 16.0 | 12.80 ± 2.08 |
| mattcl-py | input-lanjian | 16.8 ± 0.6 | 15.8 | 19.5 | 14.28 ± 2.34 |
| mattcl-py | input-pting | 16.8 ± 0.6 | 15.9 | 19.5 | 14.28 ± 2.35 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 16.0 | 20.0 | 14.36 ± 2.36 |
| mattcl-py | input-kcen | 16.9 ± 0.9 | 15.5 | 20.4 | 14.37 ± 2.42 |
| mattcl-py | input-chancalan | 16.9 ± 0.7 | 16.0 | 19.6 | 14.41 ± 2.38 |
| pting | input-chancalan | 17.4 ± 0.6 | 16.0 | 20.4 | 14.76 ± 2.43 |
| pting | input-kcen | 17.4 ± 0.7 | 16.4 | 20.6 | 14.79 ± 2.45 |
| pting | input-lanjian | 17.5 ± 0.7 | 16.3 | 20.5 | 14.85 ± 2.45 |
| pting | input-pting | 17.5 ± 0.7 | 16.1 | 20.7 | 14.85 ± 2.45 |
| pting | input-mattcl | 17.6 ± 2.4 | 16.6 | 47.3 | 14.99 ± 3.13 |
| kcen | input-pting | 20.5 ± 0.7 | 19.0 | 24.0 | 17.43 ± 2.85 |
| kcen | input-kcen | 20.5 ± 0.7 | 19.5 | 24.4 | 17.46 ± 2.86 |
| kcen | input-lanjian | 20.6 ± 0.8 | 19.0 | 23.7 | 17.55 ± 2.89 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.8 | 23.9 | 17.62 ± 2.89 |
| kcen | input-chancalan | 20.8 ± 0.8 | 19.6 | 23.3 | 17.67 ± 2.91 |
| chancalan | input-kcen | 24.6 ± 0.7 | 23.0 | 27.7 | 20.88 ± 3.40 |
| chancalan | input-chancalan | 24.7 ± 0.8 | 23.0 | 27.2 | 20.99 ± 3.44 |
| chancalan | input-lanjian | 24.7 ± 0.7 | 23.4 | 27.1 | 21.00 ± 3.43 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.4 | 28.1 | 21.02 ± 3.45 |
| chancalan | input-mattcl | 25.1 ± 3.5 | 23.4 | 56.1 | 21.35 ± 4.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|