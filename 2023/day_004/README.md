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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.4 | 1.01 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.26 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.35 ± 0.32 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.8 | 1.6 | 1.37 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.7 | 1.9 | 1.38 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.7 | 1.38 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 2.1 | 1.40 ± 0.31 |
| mattcl-py | input-lanjian | 16.8 ± 0.6 | 16.1 | 20.0 | 17.57 ± 3.28 |
| pting | input-mattcl | 16.9 ± 0.6 | 15.5 | 20.4 | 17.65 ± 3.30 |
| pting | input-kcen | 16.9 ± 0.7 | 15.7 | 21.0 | 17.67 ± 3.31 |
| pting | input-lanjian | 16.9 ± 0.7 | 15.7 | 20.4 | 17.70 ± 3.32 |
| mattcl-py | input-chancalan | 17.0 ± 0.7 | 15.9 | 20.6 | 17.75 ± 3.34 |
| pting | input-chancalan | 17.0 ± 0.7 | 16.0 | 19.7 | 17.75 ± 3.33 |
| mattcl-py | input-pting | 17.0 ± 0.6 | 15.7 | 19.7 | 17.75 ± 3.31 |
| pting | input-pting | 17.0 ± 0.7 | 15.9 | 19.8 | 17.79 ± 3.34 |
| mattcl-py | input-mattcl | 17.0 ± 0.8 | 15.7 | 20.4 | 17.83 ± 3.36 |
| kcen | input-mattcl | 17.1 ± 0.7 | 16.0 | 21.0 | 17.88 ± 3.36 |
| kcen | input-chancalan | 17.1 ± 0.7 | 15.7 | 20.1 | 17.88 ± 3.34 |
| kcen | input-lanjian | 17.1 ± 0.8 | 16.0 | 20.6 | 17.94 ± 3.39 |
| kcen | input-kcen | 17.2 ± 0.7 | 16.2 | 19.8 | 17.99 ± 3.37 |
| chancalan | input-chancalan | 17.4 ± 0.7 | 16.2 | 20.2 | 18.15 ± 3.41 |
| chancalan | input-mattcl | 17.4 ± 0.7 | 16.0 | 20.4 | 18.16 ± 3.41 |
| mattcl-py | input-kcen | 17.4 ± 3.8 | 15.9 | 65.2 | 18.17 ± 5.15 |
| kcen | input-pting | 17.4 ± 0.8 | 16.1 | 20.6 | 18.17 ± 3.43 |
| chancalan | input-kcen | 17.4 ± 0.6 | 16.0 | 20.4 | 18.18 ± 3.39 |
| chancalan | input-pting | 17.5 ± 0.7 | 16.4 | 20.9 | 18.31 ± 3.44 |
| chancalan | input-lanjian | 17.5 ± 0.8 | 16.4 | 20.4 | 18.32 ± 3.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|