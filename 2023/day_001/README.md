# Day 1 benchmarks

[link to problem](https://adventofcode.com/2023/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.23 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.5 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 1.8 ± 0.2 | 1.0 | 2.7 | 1.82 ± 0.36 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.3 | 2.7 | 1.88 ± 0.39 |
| lanjian | input-chancalan | 1.9 ± 0.3 | 1.3 | 3.3 | 1.90 ± 0.41 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.3 | 2.7 | 1.92 ± 0.42 |
| lanjian | input-pting | 2.0 ± 0.3 | 1.5 | 3.0 | 2.03 ± 0.48 |
| pting | input-mattcl | 18.0 ± 0.5 | 17.1 | 20.6 | 18.17 ± 3.14 |
| pting | input-chancalan | 18.0 ± 0.7 | 16.8 | 21.0 | 18.21 ± 3.18 |
| pting | input-kcen | 18.0 ± 0.7 | 16.9 | 21.0 | 18.22 ± 3.18 |
| pting | input-lanjian | 18.0 ± 0.7 | 17.1 | 21.5 | 18.23 ± 3.18 |
| pting | input-pting | 18.1 ± 0.7 | 17.2 | 21.1 | 18.28 ± 3.19 |
| chancalan | input-chancalan | 18.4 ± 0.7 | 17.6 | 21.8 | 18.64 ± 3.26 |
| chancalan | input-kcen | 18.5 ± 0.5 | 17.5 | 20.9 | 18.65 ± 3.22 |
| mattcl-py | input-chancalan | 18.6 ± 0.6 | 17.8 | 21.2 | 18.78 ± 3.26 |
| mattcl-py | input-mattcl | 18.6 ± 0.5 | 17.6 | 21.4 | 18.79 ± 3.24 |
| mattcl-py | input-lanjian | 18.6 ± 0.7 | 17.5 | 21.5 | 18.80 ± 3.29 |
| chancalan | input-mattcl | 18.6 ± 0.7 | 17.5 | 22.1 | 18.84 ± 3.29 |
| mattcl-py | input-kcen | 18.7 ± 0.8 | 17.5 | 21.8 | 18.85 ± 3.30 |
| mattcl-py | input-pting | 18.7 ± 0.7 | 17.7 | 21.8 | 18.86 ± 3.28 |
| chancalan | input-pting | 18.7 ± 0.7 | 17.9 | 21.5 | 18.87 ± 3.29 |
| kcen | input-kcen | 18.7 ± 0.6 | 17.9 | 21.9 | 18.94 ± 3.28 |
| chancalan | input-lanjian | 18.8 ± 3.2 | 17.4 | 58.6 | 18.97 ± 4.61 |
| kcen | input-mattcl | 18.8 ± 0.5 | 17.8 | 21.4 | 18.97 ± 3.27 |
| kcen | input-chancalan | 18.8 ± 0.7 | 17.8 | 21.8 | 18.99 ± 3.31 |
| kcen | input-pting | 18.9 ± 0.7 | 17.9 | 22.1 | 19.10 ± 3.33 |
| kcen | input-lanjian | 18.9 ± 0.9 | 17.7 | 22.0 | 19.13 ± 3.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|