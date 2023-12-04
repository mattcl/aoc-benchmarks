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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.31 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.1 | 1.08 ± 0.29 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.37 ± 0.38 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.38 ± 0.38 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.6 | 1.38 ± 0.39 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.43 ± 0.39 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.7 | 1.7 | 1.44 ± 0.38 |
| pting | input-lanjian | 16.6 ± 0.7 | 15.6 | 20.2 | 19.16 ± 4.56 |
| pting | input-chancalan | 16.6 ± 0.7 | 15.9 | 19.7 | 19.19 ± 4.56 |
| pting | input-kcen | 16.6 ± 0.6 | 15.8 | 20.4 | 19.20 ± 4.56 |
| pting | input-mattcl | 16.7 ± 0.7 | 16.0 | 19.5 | 19.27 ± 4.59 |
| pting | input-pting | 16.8 ± 0.7 | 15.9 | 19.6 | 19.34 ± 4.61 |
| kcen | input-chancalan | 17.0 ± 0.7 | 16.2 | 20.1 | 19.58 ± 4.65 |
| kcen | input-kcen | 17.0 ± 0.7 | 15.9 | 20.3 | 19.60 ± 4.67 |
| kcen | input-mattcl | 17.0 ± 0.6 | 16.1 | 19.9 | 19.61 ± 4.66 |
| kcen | input-lanjian | 17.1 ± 1.0 | 16.0 | 27.5 | 19.68 ± 4.75 |
| kcen | input-pting | 17.1 ± 0.7 | 15.9 | 20.3 | 19.77 ± 4.70 |
| mattcl-py | input-chancalan | 17.3 ± 0.6 | 16.3 | 20.7 | 19.97 ± 4.74 |
| chancalan | input-lanjian | 17.3 ± 0.6 | 16.5 | 20.6 | 19.97 ± 4.74 |
| chancalan | input-kcen | 17.3 ± 0.6 | 16.3 | 19.9 | 19.98 ± 4.74 |
| chancalan | input-chancalan | 17.3 ± 0.7 | 16.2 | 20.4 | 19.98 ± 4.75 |
| mattcl-py | input-lanjian | 17.3 ± 0.5 | 16.4 | 19.7 | 19.98 ± 4.72 |
| chancalan | input-mattcl | 17.4 ± 0.7 | 16.2 | 20.3 | 20.03 ± 4.77 |
| mattcl-py | input-pting | 17.4 ± 0.5 | 16.4 | 20.5 | 20.04 ± 4.74 |
| mattcl-py | input-mattcl | 17.4 ± 0.7 | 16.3 | 20.6 | 20.08 ± 4.77 |
| mattcl-py | input-kcen | 17.4 ± 0.7 | 16.4 | 20.7 | 20.09 ± 4.78 |
| chancalan | input-pting | 17.5 ± 0.6 | 16.6 | 20.6 | 20.15 ± 4.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|