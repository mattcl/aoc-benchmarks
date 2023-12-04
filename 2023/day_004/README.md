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
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.00 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.5 | 1.01 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.6 | 1.06 ± 0.31 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.5 | 1.38 ± 0.39 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.4 | 1.39 ± 0.41 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.40 ± 0.40 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 2.2 | 1.48 ± 0.43 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.9 | 1.53 ± 0.41 |
| pting | input-lanjian | 16.5 ± 0.5 | 15.7 | 19.4 | 20.36 ± 4.67 |
| pting | input-kcen | 16.5 ± 0.6 | 15.5 | 19.0 | 20.38 ± 4.68 |
| pting | input-chancalan | 16.5 ± 0.7 | 15.6 | 19.4 | 20.40 ± 4.71 |
| pting | input-mattcl | 16.6 ± 0.7 | 15.7 | 19.7 | 20.50 ± 4.74 |
| pting | input-pting | 16.8 ± 2.0 | 15.5 | 42.7 | 20.75 ± 5.34 |
| chancalan | input-kcen | 17.2 ± 0.6 | 16.3 | 19.4 | 21.21 ± 4.87 |
| chancalan | input-lanjian | 17.2 ± 0.7 | 16.2 | 21.0 | 21.30 ± 4.92 |
| chancalan | input-chancalan | 17.3 ± 0.6 | 16.4 | 20.6 | 21.31 ± 4.91 |
| mattcl-py | input-chancalan | 17.3 ± 0.6 | 16.3 | 20.5 | 21.32 ± 4.90 |
| chancalan | input-mattcl | 17.3 ± 0.8 | 16.1 | 20.6 | 21.32 ± 4.96 |
| mattcl-py | input-mattcl | 17.3 ± 0.6 | 16.2 | 20.1 | 21.35 ± 4.90 |
| chancalan | input-pting | 17.3 ± 0.7 | 16.5 | 20.6 | 21.42 ± 4.95 |
| mattcl-py | input-pting | 17.3 ± 0.5 | 16.3 | 19.9 | 21.43 ± 4.92 |
| mattcl-py | input-kcen | 17.4 ± 0.8 | 16.2 | 20.8 | 21.44 ± 4.96 |
| mattcl-py | input-lanjian | 17.4 ± 0.8 | 16.4 | 20.7 | 21.45 ± 4.97 |
| kcen | input-lanjian | 17.5 ± 0.6 | 16.9 | 20.2 | 21.61 ± 4.96 |
| kcen | input-kcen | 17.5 ± 0.6 | 16.6 | 21.0 | 21.62 ± 4.97 |
| kcen | input-chancalan | 17.5 ± 2.8 | 16.4 | 52.6 | 21.68 ± 6.00 |
| kcen | input-mattcl | 17.6 ± 0.7 | 16.5 | 21.1 | 21.70 ± 5.01 |
| kcen | input-pting | 17.6 ± 0.7 | 16.5 | 20.6 | 21.76 ± 5.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|