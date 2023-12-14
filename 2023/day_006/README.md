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
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.41 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.06 ± 0.41 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.06 ± 0.39 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.41 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.42 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.11 ± 0.42 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.11 ± 0.41 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.14 ± 0.39 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.5 | 1.16 ± 0.41 |
| mattcl-ts | input-lanjian | 9.9 ± 0.3 | 9.0 | 10.9 | 14.09 ± 4.32 |
| mattcl-ts | input-chancalan | 9.9 ± 0.4 | 8.9 | 11.0 | 14.12 ± 4.33 |
| mattcl-ts | input-kcen | 9.9 ± 0.4 | 9.0 | 11.0 | 14.16 ± 4.34 |
| mattcl-ts | input-pting | 9.9 ± 0.4 | 8.8 | 10.7 | 14.17 ± 4.35 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 8.9 | 10.8 | 14.19 ± 4.35 |
| chancalan | input-chancalan | 13.9 ± 0.5 | 12.9 | 16.6 | 19.85 ± 6.08 |
| pting | input-lanjian | 13.9 ± 0.3 | 13.0 | 15.7 | 19.86 ± 6.07 |
| pting | input-kcen | 13.9 ± 0.5 | 12.9 | 17.2 | 19.87 ± 6.09 |
| mattcl-py | input-mattcl | 13.9 ± 0.5 | 12.9 | 16.6 | 19.88 ± 6.09 |
| pting | input-mattcl | 13.9 ± 0.5 | 13.1 | 17.2 | 19.89 ± 6.10 |
| chancalan | input-pting | 13.9 ± 0.5 | 13.4 | 16.7 | 19.91 ± 6.11 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 12.9 | 17.2 | 19.92 ± 6.11 |
| mattcl-py | input-pting | 13.9 ± 0.5 | 13.0 | 17.5 | 19.92 ± 6.12 |
| mattcl-py | input-chancalan | 13.9 ± 0.6 | 13.0 | 17.2 | 19.92 ± 6.12 |
| kcen | input-mattcl | 13.9 ± 0.5 | 12.9 | 17.0 | 19.92 ± 6.12 |
| kcen | input-lanjian | 14.0 ± 0.5 | 13.2 | 17.0 | 19.93 ± 6.12 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.2 | 19.94 ± 6.13 |
| chancalan | input-mattcl | 14.0 ± 0.7 | 13.0 | 17.0 | 19.94 ± 6.14 |
| kcen | input-kcen | 14.0 ± 0.7 | 12.8 | 17.5 | 19.95 ± 6.16 |
| chancalan | input-kcen | 14.0 ± 0.6 | 13.0 | 17.5 | 19.95 ± 6.14 |
| pting | input-chancalan | 14.0 ± 0.6 | 13.0 | 17.0 | 19.97 ± 6.14 |
| kcen | input-pting | 14.0 ± 0.6 | 13.0 | 17.3 | 20.01 ± 6.17 |
| pting | input-pting | 14.0 ± 0.6 | 13.0 | 16.8 | 20.03 ± 6.17 |
| chancalan | input-lanjian | 14.2 ± 3.0 | 12.9 | 55.4 | 20.23 ± 7.51 |
| kcen | input-chancalan | 14.2 ± 2.3 | 12.9 | 44.9 | 20.35 ± 7.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|