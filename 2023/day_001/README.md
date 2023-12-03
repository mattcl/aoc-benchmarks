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
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.8 | 1.07 ± 0.28 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.09 ± 0.29 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.4 | 1.10 ± 0.27 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.7 | 1.4 | 1.11 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.7 | 1.6 | 1.12 ± 0.26 |
| lanjian | input-kcen | 2.1 ± 0.3 | 1.5 | 4.2 | 1.94 ± 0.47 |
| lanjian | input-mattcl | 2.1 ± 0.3 | 1.5 | 3.0 | 1.95 ± 0.47 |
| lanjian | input-lanjian | 2.1 ± 0.2 | 1.5 | 2.9 | 1.96 ± 0.46 |
| lanjian | input-aspidites | 2.1 ± 0.3 | 1.5 | 3.5 | 1.98 ± 0.50 |
| lanjian | input-chancalan | 2.1 ± 0.3 | 1.6 | 3.0 | 1.98 ± 0.48 |
| lanjian | input-pting | 2.2 ± 0.3 | 1.2 | 3.5 | 2.03 ± 0.51 |
| aspidites | input-lanjian | 13.1 ± 0.5 | 12.0 | 14.5 | 12.23 ± 2.55 |
| aspidites | input-chancalan | 13.2 ± 0.5 | 12.0 | 14.9 | 12.28 ± 2.56 |
| aspidites | input-aspidites | 13.2 ± 0.5 | 12.3 | 14.7 | 12.30 ± 2.56 |
| aspidites | input-kcen | 13.2 ± 0.4 | 12.0 | 14.4 | 12.32 ± 2.57 |
| aspidites | input-mattcl | 13.2 ± 0.4 | 11.9 | 14.7 | 12.33 ± 2.57 |
| aspidites | input-pting | 13.3 ± 0.5 | 12.4 | 14.7 | 12.36 ± 2.58 |
| pting | input-aspidites | 18.1 ± 0.6 | 17.4 | 21.4 | 16.86 ± 3.51 |
| pting | input-kcen | 18.2 ± 0.5 | 17.1 | 21.2 | 16.96 ± 3.52 |
| pting | input-chancalan | 18.3 ± 0.7 | 17.2 | 21.6 | 17.03 ± 3.56 |
| pting | input-lanjian | 18.4 ± 0.7 | 17.2 | 21.9 | 17.08 ± 3.58 |
| pting | input-mattcl | 18.4 ± 0.7 | 17.4 | 21.5 | 17.11 ± 3.58 |
| pting | input-pting | 18.4 ± 0.7 | 17.4 | 21.1 | 17.12 ± 3.58 |
| chancalan | input-chancalan | 18.7 ± 0.5 | 17.4 | 21.0 | 17.42 ± 3.61 |
| mattcl-py | input-mattcl | 18.8 ± 0.7 | 17.8 | 22.4 | 17.46 ± 3.64 |
| mattcl-py | input-aspidites | 18.8 ± 0.7 | 17.7 | 21.9 | 17.47 ± 3.66 |
| mattcl-py | input-kcen | 18.8 ± 0.7 | 17.8 | 22.4 | 17.48 ± 3.65 |
| chancalan | input-aspidites | 18.8 ± 0.8 | 17.9 | 22.1 | 17.48 ± 3.66 |
| chancalan | input-lanjian | 18.8 ± 0.6 | 17.8 | 22.0 | 17.49 ± 3.64 |
| chancalan | input-kcen | 18.8 ± 0.7 | 17.7 | 22.7 | 17.51 ± 3.66 |
| mattcl-py | input-lanjian | 18.8 ± 0.7 | 17.6 | 21.9 | 17.51 ± 3.66 |
| mattcl-py | input-chancalan | 18.8 ± 0.8 | 17.5 | 22.2 | 17.51 ± 3.67 |
| chancalan | input-pting | 18.8 ± 0.6 | 17.8 | 21.6 | 17.51 ± 3.64 |
| chancalan | input-mattcl | 18.9 ± 0.7 | 17.8 | 21.8 | 17.55 ± 3.67 |
| mattcl-py | input-pting | 18.9 ± 0.7 | 18.0 | 22.0 | 17.57 ± 3.67 |
| kcen | input-chancalan | 19.0 ± 0.7 | 17.7 | 21.9 | 17.69 ± 3.69 |
| kcen | input-kcen | 19.1 ± 0.6 | 18.2 | 22.1 | 17.73 ± 3.69 |
| kcen | input-lanjian | 19.1 ± 0.7 | 18.2 | 22.3 | 17.74 ± 3.70 |
| kcen | input-aspidites | 19.2 ± 0.8 | 18.0 | 21.9 | 17.83 ± 3.74 |
| kcen | input-pting | 19.2 ± 0.6 | 18.2 | 22.1 | 17.83 ± 3.71 |
| kcen | input-mattcl | 19.2 ± 0.8 | 18.1 | 22.1 | 17.87 ± 3.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|