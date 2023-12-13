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
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.00 ± 0.32 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.30 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.30 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.2 | 1.07 ± 0.29 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.2 | 1.4 | 1.09 ± 0.30 |
| mattcl-ts | input-kcen | 9.9 ± 0.3 | 8.8 | 11.0 | 12.02 ± 2.71 |
| mattcl-ts | input-pting | 9.9 ± 0.4 | 8.9 | 11.0 | 12.02 ± 2.72 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.2 | 10.8 | 12.07 ± 2.72 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 9.0 | 11.3 | 12.10 ± 2.73 |
| mattcl-ts | input-chancalan | 10.0 ± 0.3 | 8.8 | 10.8 | 12.10 ± 2.73 |
| chancalan | input-pting | 14.1 ± 0.4 | 13.2 | 17.1 | 17.11 ± 3.85 |
| kcen | input-pting | 14.2 ± 0.5 | 13.3 | 16.8 | 17.18 ± 3.88 |
| chancalan | input-chancalan | 14.2 ± 0.6 | 13.2 | 16.9 | 17.19 ± 3.89 |
| kcen | input-lanjian | 14.2 ± 0.5 | 13.0 | 16.7 | 17.25 ± 3.89 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.2 | 17.3 | 17.25 ± 3.92 |
| chancalan | input-lanjian | 14.2 ± 0.7 | 12.9 | 17.9 | 17.26 ± 3.95 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.3 | 17.3 | 17.26 ± 3.91 |
| kcen | input-chancalan | 14.2 ± 0.7 | 13.1 | 17.5 | 17.27 ± 3.93 |
| mattcl-py | input-mattcl | 14.2 ± 0.7 | 13.0 | 17.9 | 17.27 ± 3.94 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.7 | 17.27 ± 3.92 |
| kcen | input-kcen | 14.3 ± 0.6 | 13.0 | 17.5 | 17.28 ± 3.92 |
| mattcl-py | input-kcen | 14.3 ± 0.7 | 13.3 | 17.8 | 17.28 ± 3.94 |
| pting | input-mattcl | 14.3 ± 0.6 | 13.4 | 17.3 | 17.28 ± 3.92 |
| chancalan | input-mattcl | 14.3 ± 0.7 | 13.4 | 17.5 | 17.29 ± 3.95 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.2 | 17.6 | 17.29 ± 3.94 |
| pting | input-pting | 14.3 ± 0.6 | 13.4 | 17.6 | 17.31 ± 3.93 |
| pting | input-kcen | 14.3 ± 0.7 | 13.2 | 17.6 | 17.39 ± 3.97 |
| pting | input-chancalan | 14.4 ± 0.7 | 13.1 | 17.8 | 17.44 ± 3.99 |
| kcen | input-mattcl | 14.5 ± 1.2 | 13.1 | 28.4 | 17.52 ± 4.16 |
| chancalan | input-kcen | 14.7 ± 3.9 | 13.0 | 52.3 | 17.87 ± 6.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|