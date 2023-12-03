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
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.5 | 1.00 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.24 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.3 | 1.6 | 1.03 ± 0.22 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.3 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-aspidites | 1.9 ± 0.2 | 1.4 | 3.1 | 1.88 ± 0.36 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.4 | 3.1 | 1.90 ± 0.39 |
| lanjian | input-kcen | 1.9 ± 0.2 | 1.4 | 2.7 | 1.91 ± 0.38 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.3 | 3.2 | 1.91 ± 0.39 |
| lanjian | input-mattcl | 2.0 ± 0.3 | 1.3 | 3.1 | 1.93 ± 0.40 |
| lanjian | input-chancalan | 2.0 ± 0.2 | 1.4 | 3.3 | 1.94 ± 0.40 |
| aspidites | input-aspidites | 13.0 ± 0.6 | 11.0 | 15.8 | 12.71 ± 2.16 |
| aspidites | input-kcen | 13.1 ± 0.4 | 12.0 | 14.1 | 12.80 ± 2.14 |
| aspidites | input-lanjian | 13.1 ± 0.5 | 11.5 | 14.7 | 12.83 ± 2.16 |
| aspidites | input-mattcl | 13.1 ± 0.4 | 12.3 | 14.5 | 12.84 ± 2.15 |
| aspidites | input-chancalan | 13.2 ± 0.4 | 12.2 | 14.6 | 12.89 ± 2.16 |
| aspidites | input-pting | 13.2 ± 0.5 | 12.1 | 14.5 | 12.93 ± 2.17 |
| pting | input-aspidites | 17.8 ± 0.5 | 17.1 | 20.7 | 17.42 ± 2.89 |
| pting | input-chancalan | 17.9 ± 0.7 | 17.1 | 21.3 | 17.57 ± 2.96 |
| pting | input-mattcl | 18.0 ± 0.7 | 17.2 | 21.1 | 17.61 ± 2.98 |
| pting | input-pting | 18.0 ± 0.8 | 17.0 | 21.6 | 17.63 ± 3.00 |
| pting | input-lanjian | 18.1 ± 0.9 | 17.1 | 21.5 | 17.68 ± 3.03 |
| pting | input-kcen | 18.1 ± 1.9 | 17.0 | 40.1 | 17.70 ± 3.46 |
| chancalan | input-aspidites | 18.4 ± 0.6 | 17.1 | 21.0 | 18.01 ± 3.01 |
| mattcl-py | input-lanjian | 18.4 ± 0.6 | 17.3 | 21.6 | 18.04 ± 3.02 |
| chancalan | input-pting | 18.5 ± 0.7 | 17.5 | 21.6 | 18.13 ± 3.05 |
| chancalan | input-lanjian | 18.5 ± 0.7 | 17.5 | 21.9 | 18.14 ± 3.06 |
| chancalan | input-chancalan | 18.6 ± 0.8 | 17.2 | 22.2 | 18.18 ± 3.08 |
| mattcl-py | input-chancalan | 18.6 ± 0.6 | 17.5 | 21.8 | 18.18 ± 3.05 |
| chancalan | input-kcen | 18.6 ± 0.7 | 17.5 | 21.4 | 18.18 ± 3.06 |
| chancalan | input-mattcl | 18.6 ± 0.8 | 17.4 | 22.0 | 18.19 ± 3.08 |
| mattcl-py | input-kcen | 18.6 ± 0.7 | 17.5 | 21.8 | 18.19 ± 3.06 |
| mattcl-py | input-aspidites | 18.6 ± 0.8 | 17.4 | 22.0 | 18.20 ± 3.10 |
| mattcl-py | input-mattcl | 18.6 ± 0.8 | 17.6 | 21.8 | 18.25 ± 3.09 |
| kcen | input-kcen | 18.7 ± 0.4 | 17.9 | 21.7 | 18.34 ± 3.04 |
| mattcl-py | input-pting | 18.7 ± 0.8 | 17.5 | 22.1 | 18.34 ± 3.12 |
| kcen | input-pting | 18.7 ± 0.5 | 17.9 | 21.6 | 18.35 ± 3.06 |
| kcen | input-mattcl | 18.8 ± 0.6 | 17.9 | 22.0 | 18.38 ± 3.07 |
| kcen | input-chancalan | 18.8 ± 0.7 | 17.8 | 21.8 | 18.42 ± 3.10 |
| kcen | input-aspidites | 18.9 ± 0.8 | 17.9 | 21.8 | 18.51 ± 3.14 |
| kcen | input-lanjian | 18.9 ± 0.8 | 17.8 | 21.7 | 18.54 ± 3.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|