# Day 4 benchmarks

[link to problem](https://adventofcode.com/2023/day/4)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 4)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.28 |
| mattcl | input-pting | 0.9 ± 3.0 | 0.1 | 43.2 | 1.03 ± 3.34 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.4 | 1.04 ± 0.25 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.27 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.34 ± 0.33 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.37 ± 0.34 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.5 | 1.38 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.42 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.8 | 2.4 | 1.45 ± 0.36 |
| mattcl-py | input-chancalan | 16.8 ± 0.5 | 15.5 | 20.0 | 18.57 ± 3.73 |
| pting | input-mattcl | 16.8 ± 0.6 | 15.5 | 20.1 | 18.60 ± 3.75 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 15.8 | 19.5 | 18.69 ± 3.76 |
| mattcl-py | input-lanjian | 16.9 ± 0.6 | 15.8 | 19.6 | 18.72 ± 3.77 |
| pting | input-lanjian | 17.0 ± 0.8 | 16.2 | 20.6 | 18.75 ± 3.82 |
| pting | input-kcen | 17.0 ± 0.8 | 15.8 | 19.9 | 18.77 ± 3.82 |
| mattcl-py | input-kcen | 17.0 ± 0.8 | 15.8 | 20.5 | 18.78 ± 3.82 |
| pting | input-pting | 17.0 ± 0.7 | 15.6 | 19.7 | 18.79 ± 3.80 |
| pting | input-chancalan | 17.0 ± 0.7 | 15.8 | 20.1 | 18.79 ± 3.81 |
| kcen | input-kcen | 17.2 ± 0.6 | 16.3 | 20.5 | 19.01 ± 3.84 |
| kcen | input-lanjian | 17.2 ± 0.6 | 16.1 | 20.2 | 19.02 ± 3.83 |
| mattcl-py | input-pting | 17.2 ± 2.4 | 15.6 | 46.5 | 19.05 ± 4.60 |
| kcen | input-chancalan | 17.2 ± 0.8 | 15.8 | 20.3 | 19.08 ± 3.88 |
| kcen | input-pting | 17.3 ± 0.7 | 16.3 | 20.3 | 19.14 ± 3.88 |
| kcen | input-mattcl | 17.3 ± 0.7 | 16.2 | 20.4 | 19.14 ± 3.88 |
| chancalan | input-kcen | 17.4 ± 0.5 | 16.1 | 19.9 | 19.28 ± 3.87 |
| chancalan | input-mattcl | 17.4 ± 0.7 | 16.1 | 20.4 | 19.29 ± 3.90 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.7 | 20.9 | 19.30 ± 3.90 |
| chancalan | input-pting | 17.5 ± 0.5 | 16.6 | 20.4 | 19.35 ± 3.89 |
| chancalan | input-chancalan | 17.5 ± 0.8 | 16.3 | 20.9 | 19.39 ± 3.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|