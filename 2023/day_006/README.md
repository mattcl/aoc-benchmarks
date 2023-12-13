# Day 6 benchmarks

[link to problem](https://adventofcode.com/2023/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.4 | 1.01 ± 0.33 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.02 ± 0.30 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.2 | 1.0 | 1.02 ± 0.30 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.02 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.0 | 1.02 ± 0.30 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.1 | 1.0 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.32 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.2 | 1.06 ± 0.31 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 8.9 | 10.9 | 12.86 ± 3.01 |
| mattcl-ts | input-kcen | 10.0 ± 0.4 | 9.1 | 11.2 | 12.92 ± 3.03 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 9.3 | 11.3 | 13.00 ± 3.04 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 9.2 | 11.7 | 13.03 ± 3.04 |
| mattcl-ts | input-lanjian | 10.3 ± 3.5 | 9.1 | 59.0 | 13.25 ± 5.42 |
| chancalan | input-pting | 14.1 ± 0.6 | 13.2 | 17.1 | 18.10 ± 4.26 |
| kcen | input-chancalan | 14.1 ± 0.6 | 12.9 | 17.3 | 18.10 ± 4.26 |
| chancalan | input-kcen | 14.1 ± 0.6 | 12.8 | 17.4 | 18.11 ± 4.26 |
| chancalan | input-chancalan | 14.1 ± 0.7 | 12.9 | 17.6 | 18.11 ± 4.29 |
| mattcl-py | input-pting | 14.1 ± 0.5 | 12.9 | 17.3 | 18.11 ± 4.24 |
| pting | input-mattcl | 14.1 ± 0.5 | 12.9 | 17.2 | 18.12 ± 4.25 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 12.9 | 17.5 | 18.12 ± 4.27 |
| chancalan | input-lanjian | 14.1 ± 0.5 | 13.0 | 16.7 | 18.13 ± 4.25 |
| mattcl-py | input-lanjian | 14.1 ± 0.7 | 13.3 | 17.1 | 18.14 ± 4.28 |
| mattcl-py | input-chancalan | 14.1 ± 0.7 | 13.0 | 17.9 | 18.17 ± 4.32 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.2 | 17.4 | 18.17 ± 4.27 |
| kcen | input-lanjian | 14.1 ± 0.5 | 13.2 | 17.4 | 18.17 ± 4.26 |
| kcen | input-pting | 14.2 ± 0.7 | 12.9 | 17.4 | 18.23 ± 4.32 |
| mattcl-py | input-kcen | 14.2 ± 0.7 | 13.1 | 17.2 | 18.26 ± 4.31 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.2 | 17.3 | 18.26 ± 4.30 |
| pting | input-kcen | 14.2 ± 0.7 | 13.2 | 17.2 | 18.29 ± 4.32 |
| pting | input-pting | 14.2 ± 0.7 | 13.0 | 17.5 | 18.29 ± 4.33 |
| pting | input-chancalan | 14.2 ± 0.7 | 13.4 | 17.4 | 18.29 ± 4.32 |
| kcen | input-mattcl | 14.3 ± 2.2 | 13.1 | 44.9 | 18.39 ± 5.14 |
| chancalan | input-mattcl | 14.5 ± 3.6 | 13.3 | 52.1 | 18.59 ± 6.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|