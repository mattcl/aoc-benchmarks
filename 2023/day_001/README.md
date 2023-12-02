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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.27 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.1 | 1.6 | 1.05 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.4 | 1.05 ± 0.27 |
| mattcl | input-lanjian | 0.9 ± 3.2 | 0.0 | 46.0 | 1.07 ± 3.65 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 1.2 | 2.7 | 2.00 ± 0.47 |
| lanjian | input-mattcl | 1.8 ± 0.3 | 1.2 | 3.5 | 2.09 ± 0.54 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.2 | 2.8 | 2.10 ± 0.52 |
| lanjian | input-pting | 1.9 ± 0.3 | 1.3 | 2.8 | 2.10 ± 0.51 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.2 | 3.1 | 2.11 ± 0.53 |
| pting | input-lanjian | 17.8 ± 0.6 | 16.8 | 20.9 | 20.21 ± 4.00 |
| pting | input-mattcl | 17.9 ± 0.5 | 16.9 | 21.3 | 20.23 ± 3.99 |
| pting | input-chancalan | 17.9 ± 0.7 | 17.2 | 20.9 | 20.27 ± 4.02 |
| pting | input-pting | 17.9 ± 0.6 | 17.0 | 21.2 | 20.28 ± 4.02 |
| pting | input-kcen | 18.0 ± 0.7 | 17.0 | 21.1 | 20.35 ± 4.06 |
| chancalan | input-chancalan | 18.3 ± 0.5 | 17.3 | 20.2 | 20.71 ± 4.08 |
| mattcl-py | input-mattcl | 18.4 ± 0.6 | 17.5 | 21.3 | 20.89 ± 4.12 |
| mattcl-py | input-chancalan | 18.5 ± 0.6 | 17.5 | 21.4 | 20.91 ± 4.14 |
| chancalan | input-pting | 18.5 ± 0.6 | 17.3 | 21.3 | 20.94 ± 4.15 |
| chancalan | input-lanjian | 18.5 ± 0.8 | 17.2 | 22.0 | 20.95 ± 4.19 |
| chancalan | input-kcen | 18.5 ± 0.7 | 17.4 | 21.7 | 20.96 ± 4.17 |
| mattcl-py | input-pting | 18.5 ± 0.6 | 17.5 | 21.5 | 20.98 ± 4.15 |
| chancalan | input-mattcl | 18.5 ± 0.6 | 17.6 | 21.2 | 21.00 ± 4.15 |
| mattcl-py | input-kcen | 18.6 ± 0.8 | 17.5 | 22.0 | 21.03 ± 4.20 |
| kcen | input-chancalan | 18.6 ± 0.5 | 17.6 | 21.5 | 21.09 ± 4.16 |
| kcen | input-pting | 18.7 ± 0.6 | 17.9 | 22.1 | 21.15 ± 4.18 |
| kcen | input-mattcl | 18.7 ± 0.6 | 17.6 | 21.3 | 21.20 ± 4.19 |
| mattcl-py | input-lanjian | 18.7 ± 3.2 | 17.3 | 58.2 | 21.22 ± 5.50 |
| kcen | input-kcen | 18.8 ± 0.8 | 17.6 | 22.5 | 21.34 ± 4.27 |
| kcen | input-lanjian | 19.0 ± 2.4 | 17.7 | 47.2 | 21.55 ± 4.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|