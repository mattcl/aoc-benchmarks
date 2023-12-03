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
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.7 | 1.03 ± 0.29 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.3 | 1.04 ± 0.25 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.1 | 0.3 | 1.5 | 1.05 ± 0.24 |
| lanjian | input-kcen | 1.9 ± 0.2 | 1.3 | 2.7 | 1.90 ± 0.38 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.8 | 1.92 ± 0.40 |
| lanjian | input-aspidites | 2.0 ± 0.3 | 1.4 | 2.8 | 1.96 ± 0.44 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.1 | 3.2 | 2.02 ± 0.47 |
| lanjian | input-chancalan | 2.0 ± 0.3 | 1.4 | 3.3 | 2.02 ± 0.47 |
| lanjian | input-pting | 2.1 ± 0.4 | 1.3 | 3.8 | 2.07 ± 0.52 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.1 | 14.6 | 13.11 ± 2.42 |
| aspidites | input-lanjian | 13.1 ± 0.5 | 12.1 | 14.6 | 13.12 ± 2.42 |
| aspidites | input-pting | 13.1 ± 0.5 | 11.9 | 14.4 | 13.15 ± 2.42 |
| aspidites | input-mattcl | 13.1 ± 0.5 | 12.3 | 14.7 | 13.15 ± 2.42 |
| aspidites | input-kcen | 13.2 ± 0.4 | 12.2 | 14.4 | 13.18 ± 2.42 |
| aspidites | input-chancalan | 13.2 ± 0.5 | 11.9 | 14.9 | 13.19 ± 2.43 |
| pting | input-mattcl | 18.1 ± 0.8 | 17.1 | 21.7 | 18.12 ± 3.37 |
| pting | input-kcen | 18.2 ± 0.7 | 17.2 | 21.6 | 18.18 ± 3.36 |
| pting | input-aspidites | 18.2 ± 0.9 | 16.8 | 22.2 | 18.19 ± 3.40 |
| pting | input-chancalan | 18.2 ± 0.8 | 17.3 | 21.5 | 18.24 ± 3.38 |
| pting | input-pting | 18.3 ± 0.7 | 17.2 | 21.4 | 18.27 ± 3.39 |
| pting | input-lanjian | 18.4 ± 0.9 | 17.3 | 21.6 | 18.40 ± 3.45 |
| chancalan | input-aspidites | 18.5 ± 0.5 | 17.8 | 20.8 | 18.50 ± 3.39 |
| chancalan | input-chancalan | 18.6 ± 0.7 | 17.2 | 21.5 | 18.58 ± 3.42 |
| chancalan | input-pting | 18.6 ± 0.6 | 17.7 | 22.0 | 18.60 ± 3.41 |
| mattcl-py | input-mattcl | 18.7 ± 0.6 | 17.5 | 22.1 | 18.66 ± 3.43 |
| chancalan | input-mattcl | 18.7 ± 0.6 | 17.4 | 21.8 | 18.67 ± 3.43 |
| chancalan | input-kcen | 18.7 ± 0.6 | 17.8 | 21.6 | 18.69 ± 3.44 |
| chancalan | input-lanjian | 18.7 ± 0.7 | 17.7 | 21.5 | 18.72 ± 3.46 |
| mattcl-py | input-aspidites | 18.7 ± 0.8 | 17.7 | 22.3 | 18.73 ± 3.48 |
| mattcl-py | input-kcen | 18.8 ± 0.7 | 17.7 | 22.0 | 18.76 ± 3.47 |
| mattcl-py | input-chancalan | 18.8 ± 0.7 | 17.7 | 22.1 | 18.78 ± 3.47 |
| mattcl-py | input-lanjian | 18.8 ± 0.9 | 17.8 | 22.3 | 18.85 ± 3.54 |
| kcen | input-aspidites | 18.9 ± 0.6 | 17.6 | 21.5 | 18.86 ± 3.46 |
| mattcl-py | input-pting | 18.9 ± 0.9 | 17.5 | 22.3 | 18.86 ± 3.53 |
| kcen | input-mattcl | 18.9 ± 0.6 | 18.0 | 21.6 | 18.95 ± 3.49 |
| kcen | input-kcen | 19.0 ± 0.7 | 18.2 | 22.1 | 19.00 ± 3.50 |
| kcen | input-chancalan | 19.0 ± 0.7 | 17.9 | 22.1 | 19.02 ± 3.52 |
| kcen | input-pting | 19.1 ± 0.7 | 18.2 | 22.1 | 19.09 ± 3.51 |
| kcen | input-lanjian | 19.2 ± 1.6 | 18.0 | 37.1 | 19.20 ± 3.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|