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

- [aspidites](https://github.com/aspidites/aoc2023) (haskell)
- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.4 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.6 | 1.01 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.5 | 1.07 ± 0.28 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 0.9 | 2.9 | 1.95 ± 0.46 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.2 | 3.1 | 2.02 ± 0.51 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.3 | 3.3 | 2.05 ± 0.50 |
| lanjian | input-mattcl | 1.9 ± 0.3 | 1.3 | 3.0 | 2.05 ± 0.49 |
| lanjian | input-aspidites | 1.9 ± 0.2 | 1.3 | 2.7 | 2.07 ± 0.49 |
| lanjian | input-pting | 1.9 ± 0.3 | 1.6 | 2.7 | 2.09 ± 0.50 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.3 | 14.3 | 13.92 ± 2.82 |
| aspidites | input-kcen | 13.0 ± 2.9 | 11.4 | 53.4 | 14.10 ± 4.24 |
| aspidites | input-pting | 13.0 ± 0.4 | 11.9 | 14.3 | 14.11 ± 2.83 |
| aspidites | input-lanjian | 13.0 ± 0.4 | 12.2 | 14.4 | 14.12 ± 2.84 |
| aspidites | input-aspidites | 13.0 ± 0.5 | 11.8 | 14.1 | 14.13 ± 2.84 |
| aspidites | input-mattcl | 13.1 ± 0.4 | 12.1 | 14.5 | 14.23 ± 2.85 |
| pting | input-mattcl | 18.0 ± 0.7 | 16.8 | 21.1 | 19.52 ± 3.94 |
| pting | input-lanjian | 18.0 ± 0.8 | 16.7 | 21.4 | 19.53 ± 3.96 |
| pting | input-aspidites | 18.0 ± 0.8 | 16.6 | 20.9 | 19.55 ± 3.96 |
| pting | input-chancalan | 18.1 ± 0.8 | 17.1 | 21.7 | 19.66 ± 4.00 |
| pting | input-pting | 18.2 ± 0.8 | 16.7 | 21.4 | 19.72 ± 4.00 |
| pting | input-kcen | 18.2 ± 0.8 | 17.1 | 21.6 | 19.73 ± 4.01 |
| mattcl-py | input-aspidites | 18.5 ± 0.8 | 17.2 | 21.5 | 20.06 ± 4.06 |
| mattcl-py | input-kcen | 18.5 ± 0.6 | 17.6 | 21.3 | 20.07 ± 4.03 |
| chancalan | input-pting | 18.5 ± 0.6 | 17.2 | 22.0 | 20.10 ± 4.04 |
| chancalan | input-chancalan | 18.6 ± 0.8 | 17.6 | 21.9 | 20.12 ± 4.07 |
| chancalan | input-lanjian | 18.6 ± 0.7 | 17.5 | 22.3 | 20.12 ± 4.06 |
| chancalan | input-mattcl | 18.6 ± 0.7 | 17.6 | 21.8 | 20.13 ± 4.05 |
| chancalan | input-aspidites | 18.6 ± 0.8 | 17.6 | 21.8 | 20.13 ± 4.08 |
| mattcl-py | input-chancalan | 18.6 ± 0.6 | 17.4 | 21.4 | 20.14 ± 4.04 |
| chancalan | input-kcen | 18.6 ± 0.8 | 17.6 | 22.2 | 20.16 ± 4.09 |
| mattcl-py | input-lanjian | 18.6 ± 0.7 | 17.1 | 21.6 | 20.16 ± 4.07 |
| mattcl-py | input-mattcl | 18.7 ± 0.8 | 17.6 | 22.3 | 20.30 ± 4.12 |
| mattcl-py | input-pting | 18.8 ± 0.8 | 17.6 | 21.5 | 20.37 ± 4.13 |
| kcen | input-kcen | 18.8 ± 0.8 | 17.7 | 22.0 | 20.37 ± 4.12 |
| kcen | input-aspidites | 18.8 ± 0.7 | 17.9 | 22.0 | 20.42 ± 4.11 |
| kcen | input-chancalan | 18.8 ± 0.7 | 17.6 | 21.6 | 20.43 ± 4.12 |
| kcen | input-mattcl | 18.9 ± 0.8 | 17.6 | 22.1 | 20.45 ± 4.14 |
| kcen | input-lanjian | 18.9 ± 0.8 | 17.9 | 22.2 | 20.46 ± 4.14 |
| kcen | input-pting | 19.0 ± 0.8 | 17.9 | 21.9 | 20.58 ± 4.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|