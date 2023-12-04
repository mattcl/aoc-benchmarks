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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.4 | 1.1 | 1.03 ± 0.27 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.27 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.7 | 1.05 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.3 | 1.06 ± 0.27 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.6 | 1.35 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.5 | 1.41 ± 0.34 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.9 | 1.41 ± 0.35 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.9 | 1.42 ± 0.37 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.44 ± 0.35 |
| pting | input-chancalan | 16.5 ± 0.6 | 15.8 | 19.7 | 19.27 ± 3.91 |
| pting | input-kcen | 16.5 ± 0.6 | 15.6 | 19.6 | 19.28 ± 3.91 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.7 | 19.2 | 19.31 ± 3.92 |
| pting | input-mattcl | 16.6 ± 0.6 | 15.5 | 19.4 | 19.34 ± 3.93 |
| mattcl-py | input-kcen | 16.6 ± 0.6 | 15.9 | 19.7 | 19.37 ± 3.93 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.9 | 20.0 | 19.49 ± 3.96 |
| mattcl-py | input-mattcl | 16.7 ± 0.8 | 15.5 | 19.9 | 19.52 ± 4.00 |
| mattcl-py | input-lanjian | 16.7 ± 0.8 | 15.6 | 20.0 | 19.54 ± 4.02 |
| pting | input-pting | 16.8 ± 0.7 | 15.7 | 19.6 | 19.59 ± 4.01 |
| kcen | input-mattcl | 16.9 ± 0.6 | 15.9 | 19.7 | 19.77 ± 4.02 |
| kcen | input-lanjian | 17.0 ± 0.6 | 16.2 | 20.3 | 19.80 ± 4.03 |
| kcen | input-kcen | 17.0 ± 0.7 | 15.8 | 20.5 | 19.82 ± 4.04 |
| kcen | input-chancalan | 17.0 ± 0.7 | 16.2 | 19.8 | 19.82 ± 4.04 |
| pting | input-lanjian | 17.0 ± 3.7 | 15.7 | 64.3 | 19.86 ± 5.86 |
| kcen | input-pting | 17.1 ± 0.7 | 16.0 | 20.1 | 19.96 ± 4.08 |
| chancalan | input-mattcl | 17.2 ± 0.7 | 16.1 | 20.6 | 20.14 ± 4.11 |
| chancalan | input-kcen | 17.3 ± 0.6 | 16.4 | 20.3 | 20.15 ± 4.09 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.2 | 20.2 | 20.17 ± 4.11 |
| chancalan | input-pting | 17.3 ± 0.6 | 16.2 | 20.7 | 20.26 ± 4.11 |
| chancalan | input-chancalan | 17.4 ± 3.4 | 16.1 | 60.8 | 20.30 ± 5.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|