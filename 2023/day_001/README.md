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
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.2 | 1.01 ± 0.25 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.4 | 1.2 | 1.03 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.4 | 1.06 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.4 | 1.06 ± 0.23 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.3 | 3.0 | 1.99 ± 0.44 |
| lanjian | input-aspidites | 1.9 ± 0.3 | 1.3 | 3.2 | 2.03 ± 0.46 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.3 | 3.3 | 2.03 ± 0.48 |
| lanjian | input-chancalan | 1.9 ± 0.3 | 1.6 | 3.0 | 2.04 ± 0.47 |
| lanjian | input-mattcl | 1.9 ± 0.3 | 1.2 | 3.0 | 2.05 ± 0.46 |
| lanjian | input-pting | 2.0 ± 0.3 | 1.4 | 3.0 | 2.09 ± 0.48 |
| aspidites | input-pting | 13.0 ± 0.4 | 11.7 | 14.7 | 13.76 ± 2.43 |
| aspidites | input-chancalan | 13.0 ± 0.4 | 12.0 | 14.2 | 13.77 ± 2.44 |
| aspidites | input-lanjian | 13.0 ± 0.5 | 12.1 | 14.9 | 13.85 ± 2.45 |
| aspidites | input-mattcl | 13.1 ± 0.5 | 12.0 | 14.5 | 13.86 ± 2.46 |
| aspidites | input-kcen | 13.1 ± 0.5 | 11.4 | 14.6 | 13.89 ± 2.46 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 11.9 | 14.6 | 13.92 ± 2.47 |
| pting | input-aspidites | 18.1 ± 0.8 | 16.8 | 21.4 | 19.18 ± 3.43 |
| pting | input-kcen | 18.1 ± 0.8 | 17.1 | 21.9 | 19.23 ± 3.44 |
| pting | input-chancalan | 18.2 ± 0.7 | 17.1 | 21.3 | 19.30 ± 3.44 |
| pting | input-mattcl | 18.2 ± 0.7 | 17.2 | 21.5 | 19.35 ± 3.44 |
| pting | input-pting | 18.2 ± 0.8 | 17.2 | 21.1 | 19.38 ± 3.48 |
| pting | input-lanjian | 18.3 ± 3.0 | 16.8 | 53.8 | 19.47 ± 4.61 |
| chancalan | input-aspidites | 18.5 ± 0.8 | 17.3 | 22.3 | 19.67 ± 3.51 |
| chancalan | input-pting | 18.6 ± 0.6 | 17.5 | 21.4 | 19.72 ± 3.48 |
| chancalan | input-chancalan | 18.6 ± 0.7 | 17.6 | 21.9 | 19.74 ± 3.51 |
| mattcl-py | input-kcen | 18.6 ± 0.6 | 17.7 | 21.9 | 19.77 ± 3.50 |
| mattcl-py | input-chancalan | 18.6 ± 0.7 | 17.6 | 21.9 | 19.80 ± 3.52 |
| mattcl-py | input-pting | 18.6 ± 0.7 | 17.4 | 21.5 | 19.80 ± 3.51 |
| mattcl-py | input-aspidites | 18.7 ± 0.8 | 17.4 | 22.2 | 19.81 ± 3.53 |
| chancalan | input-kcen | 18.7 ± 0.8 | 17.6 | 21.7 | 19.81 ± 3.53 |
| chancalan | input-lanjian | 18.7 ± 0.8 | 17.3 | 21.4 | 19.83 ± 3.53 |
| mattcl-py | input-lanjian | 18.7 ± 0.7 | 17.3 | 22.2 | 19.83 ± 3.53 |
| chancalan | input-mattcl | 18.7 ± 0.7 | 17.6 | 21.5 | 19.84 ± 3.52 |
| mattcl-py | input-mattcl | 18.7 ± 0.7 | 17.6 | 21.3 | 19.87 ± 3.53 |
| kcen | input-aspidites | 18.8 ± 0.7 | 17.8 | 21.3 | 20.01 ± 3.55 |
| kcen | input-kcen | 18.9 ± 0.6 | 18.0 | 21.7 | 20.02 ± 3.52 |
| kcen | input-chancalan | 18.9 ± 0.6 | 17.8 | 21.9 | 20.04 ± 3.53 |
| kcen | input-lanjian | 18.9 ± 0.7 | 18.0 | 22.0 | 20.09 ± 3.56 |
| kcen | input-mattcl | 19.0 ± 0.7 | 17.5 | 21.9 | 20.16 ± 3.58 |
| kcen | input-pting | 19.0 ± 0.7 | 17.9 | 21.9 | 20.20 ± 3.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|