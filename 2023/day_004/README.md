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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.3 | 1.2 | 1.05 ± 0.25 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.6 | 1.37 ± 0.33 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.38 ± 0.33 |
| lanjian | input-chancalan | 1.3 ± 0.1 | 0.8 | 1.8 | 1.39 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.5 | 2.0 | 1.40 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.5 | 1.8 | 1.42 ± 0.34 |
| mattcl-py | input-lanjian | 16.9 ± 0.5 | 15.6 | 19.4 | 17.80 ± 3.50 |
| mattcl-py | input-kcen | 16.9 ± 0.6 | 15.9 | 19.8 | 17.88 ± 3.53 |
| mattcl-py | input-pting | 17.0 ± 0.6 | 15.9 | 20.1 | 17.90 ± 3.53 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.7 | 20.4 | 17.90 ± 3.54 |
| pting | input-chancalan | 17.0 ± 0.5 | 16.1 | 19.6 | 17.91 ± 3.52 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.1 | 20.1 | 17.91 ± 3.54 |
| pting | input-pting | 17.0 ± 0.6 | 16.1 | 20.3 | 17.95 ± 3.55 |
| mattcl-py | input-mattcl | 17.0 ± 0.7 | 16.0 | 20.0 | 17.96 ± 3.56 |
| kcen | input-kcen | 17.0 ± 0.5 | 16.3 | 20.4 | 17.97 ± 3.53 |
| mattcl-py | input-chancalan | 17.1 ± 0.7 | 15.9 | 20.5 | 18.00 ± 3.58 |
| pting | input-kcen | 17.1 ± 0.8 | 16.1 | 20.2 | 18.02 ± 3.59 |
| kcen | input-lanjian | 17.1 ± 0.7 | 15.9 | 20.3 | 18.09 ± 3.58 |
| kcen | input-mattcl | 17.2 ± 0.8 | 16.0 | 20.5 | 18.12 ± 3.61 |
| kcen | input-pting | 17.2 ± 0.7 | 16.4 | 20.8 | 18.20 ± 3.60 |
| kcen | input-chancalan | 17.3 ± 2.4 | 15.9 | 47.3 | 18.27 ± 4.34 |
| chancalan | input-chancalan | 17.4 ± 0.6 | 16.1 | 20.5 | 18.37 ± 3.62 |
| chancalan | input-kcen | 17.5 ± 0.6 | 16.3 | 20.6 | 18.46 ± 3.64 |
| chancalan | input-mattcl | 17.5 ± 0.6 | 16.5 | 20.5 | 18.48 ± 3.65 |
| chancalan | input-lanjian | 17.6 ± 0.7 | 16.5 | 20.8 | 18.53 ± 3.68 |
| chancalan | input-pting | 17.6 ± 0.7 | 16.5 | 20.4 | 18.53 ± 3.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|