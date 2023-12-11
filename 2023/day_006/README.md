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
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.33 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.34 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.33 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.35 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.34 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.33 |
| mattcl-ts | input-pting | 9.7 ± 0.4 | 8.5 | 10.7 | 12.12 ± 2.81 |
| mattcl-ts | input-chancalan | 9.7 ± 0.4 | 8.8 | 10.7 | 12.13 ± 2.81 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 8.8 | 10.9 | 12.19 ± 2.83 |
| mattcl-ts | input-lanjian | 9.8 ± 0.4 | 8.8 | 10.9 | 12.23 ± 2.83 |
| mattcl-ts | input-mattcl | 10.1 ± 3.4 | 8.4 | 51.5 | 12.54 ± 5.14 |
| kcen | input-mattcl | 14.0 ± 0.2 | 13.4 | 15.0 | 17.38 ± 3.99 |
| chancalan | input-chancalan | 14.0 ± 0.5 | 13.2 | 16.7 | 17.43 ± 4.03 |
| chancalan | input-pting | 14.0 ± 0.5 | 13.1 | 16.6 | 17.43 ± 4.03 |
| mattcl-py | input-kcen | 14.0 ± 0.4 | 13.2 | 16.9 | 17.44 ± 4.03 |
| kcen | input-chancalan | 14.0 ± 0.5 | 13.0 | 17.1 | 17.44 ± 4.04 |
| pting | input-pting | 14.0 ± 0.4 | 13.1 | 17.1 | 17.45 ± 4.03 |
| pting | input-chancalan | 14.0 ± 0.5 | 13.2 | 17.3 | 17.46 ± 4.04 |
| mattcl-py | input-chancalan | 14.0 ± 0.6 | 12.9 | 17.1 | 17.49 ± 4.07 |
| kcen | input-lanjian | 14.1 ± 0.5 | 13.1 | 17.4 | 17.49 ± 4.05 |
| mattcl-py | input-pting | 14.1 ± 0.6 | 13.0 | 17.0 | 17.51 ± 4.07 |
| chancalan | input-mattcl | 14.1 ± 0.7 | 12.9 | 17.2 | 17.51 ± 4.09 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.6 | 17.51 ± 4.08 |
| chancalan | input-lanjian | 14.1 ± 0.7 | 13.0 | 17.8 | 17.51 ± 4.09 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.0 | 17.5 | 17.52 ± 4.08 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.2 | 17.0 | 17.52 ± 4.08 |
| kcen | input-pting | 14.1 ± 0.7 | 13.0 | 17.8 | 17.54 ± 4.10 |
| pting | input-kcen | 14.1 ± 0.6 | 13.4 | 17.1 | 17.55 ± 4.08 |
| pting | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.3 | 17.55 ± 4.08 |
| mattcl-py | input-lanjian | 14.1 ± 0.7 | 13.2 | 17.9 | 17.56 ± 4.11 |
| kcen | input-kcen | 14.1 ± 0.7 | 13.0 | 17.4 | 17.57 ± 4.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|