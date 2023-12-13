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
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.00 ± 0.35 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.37 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.35 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.37 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.0 | 1.05 ± 0.34 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.0 | 1.08 ± 0.36 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.3 | 1.10 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.5 | 1.2 | 1.12 ± 0.33 |
| mattcl-ts | input-lanjian | 9.8 ± 0.4 | 8.8 | 10.9 | 12.31 ± 3.34 |
| mattcl-ts | input-chancalan | 9.8 ± 0.4 | 8.7 | 10.6 | 12.32 ± 3.34 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 8.9 | 10.7 | 12.33 ± 3.34 |
| mattcl-ts | input-pting | 9.8 ± 0.4 | 8.7 | 10.8 | 12.34 ± 3.34 |
| mattcl-ts | input-mattcl | 10.0 ± 2.4 | 8.8 | 42.8 | 12.60 ± 4.51 |
| pting | input-kcen | 14.0 ± 0.4 | 13.1 | 16.7 | 17.65 ± 4.76 |
| mattcl-py | input-pting | 14.0 ± 0.5 | 13.0 | 17.5 | 17.67 ± 4.78 |
| mattcl-py | input-chancalan | 14.0 ± 0.4 | 13.2 | 16.8 | 17.67 ± 4.77 |
| chancalan | input-mattcl | 14.0 ± 0.5 | 13.1 | 16.6 | 17.69 ± 4.79 |
| mattcl-py | input-lanjian | 14.0 ± 0.5 | 13.1 | 17.0 | 17.70 ± 4.79 |
| pting | input-lanjian | 14.0 ± 0.5 | 13.3 | 16.9 | 17.70 ± 4.79 |
| chancalan | input-chancalan | 14.0 ± 0.6 | 12.9 | 17.3 | 17.72 ± 4.80 |
| pting | input-mattcl | 14.0 ± 0.6 | 13.1 | 17.5 | 17.73 ± 4.82 |
| kcen | input-kcen | 14.1 ± 0.6 | 13.1 | 17.4 | 17.76 ± 4.81 |
| kcen | input-pting | 14.1 ± 0.7 | 13.0 | 17.5 | 17.76 ± 4.84 |
| pting | input-pting | 14.1 ± 0.6 | 13.3 | 17.5 | 17.77 ± 4.83 |
| chancalan | input-kcen | 14.1 ± 0.7 | 12.9 | 17.7 | 17.78 ± 4.85 |
| chancalan | input-pting | 14.1 ± 0.7 | 13.0 | 17.3 | 17.80 ± 4.85 |
| pting | input-chancalan | 14.1 ± 0.6 | 13.1 | 16.9 | 17.81 ± 4.84 |
| kcen | input-chancalan | 14.1 ± 0.7 | 13.0 | 17.8 | 17.82 ± 4.87 |
| mattcl-py | input-kcen | 14.1 ± 0.7 | 13.2 | 17.2 | 17.83 ± 4.86 |
| kcen | input-lanjian | 14.1 ± 0.7 | 13.1 | 17.5 | 17.84 ± 4.85 |
| kcen | input-mattcl | 14.1 ± 0.7 | 13.2 | 17.7 | 17.84 ± 4.87 |
| mattcl-py | input-mattcl | 14.1 ± 0.7 | 13.1 | 17.2 | 17.84 ± 4.86 |
| chancalan | input-lanjian | 14.2 ± 2.2 | 13.2 | 44.0 | 17.96 ± 5.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|