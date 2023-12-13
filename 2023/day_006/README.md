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
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.35 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.34 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.33 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.34 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.5 | 1.06 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.34 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.5 | 1.09 ± 0.36 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.1 | 1.0 | 1.10 ± 0.33 |
| mattcl-ts | input-chancalan | 9.8 ± 0.4 | 8.8 | 10.7 | 12.97 ± 3.29 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.8 | 10.9 | 12.98 ± 3.29 |
| mattcl-ts | input-mattcl | 9.9 ± 0.4 | 8.9 | 10.8 | 13.02 ± 3.30 |
| mattcl-ts | input-pting | 9.9 ± 0.4 | 9.1 | 10.8 | 13.02 ± 3.30 |
| mattcl-ts | input-kcen | 10.1 ± 3.3 | 8.8 | 56.3 | 13.33 ± 5.48 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.2 | 17.5 | 18.60 ± 4.73 |
| chancalan | input-lanjian | 14.1 ± 0.5 | 13.3 | 16.9 | 18.61 ± 4.71 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.0 | 17.1 | 18.61 ± 4.73 |
| mattcl-py | input-chancalan | 14.1 ± 0.5 | 13.4 | 17.0 | 18.62 ± 4.72 |
| kcen | input-pting | 14.1 ± 0.5 | 13.4 | 17.7 | 18.63 ± 4.73 |
| chancalan | input-pting | 14.1 ± 0.6 | 12.9 | 17.3 | 18.63 ± 4.73 |
| chancalan | input-kcen | 14.1 ± 0.7 | 13.0 | 17.8 | 18.64 ± 4.76 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 13.5 | 17.3 | 18.65 ± 4.74 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.1 | 18.66 ± 4.74 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.0 | 17.9 | 18.67 ± 4.75 |
| mattcl-py | input-pting | 14.2 ± 0.5 | 13.4 | 17.7 | 18.68 ± 4.74 |
| pting | input-kcen | 14.2 ± 0.5 | 13.4 | 17.1 | 18.69 ± 4.74 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.1 | 17.4 | 18.75 ± 4.77 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.4 | 18.1 | 18.75 ± 4.76 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.2 | 17.2 | 18.75 ± 4.79 |
| kcen | input-lanjian | 14.2 ± 0.6 | 13.2 | 17.3 | 18.78 ± 4.78 |
| kcen | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.6 | 18.82 ± 4.81 |
| pting | input-chancalan | 14.3 ± 0.7 | 13.0 | 17.5 | 18.83 ± 4.80 |
| mattcl-py | input-kcen | 14.3 ± 0.8 | 13.4 | 18.2 | 18.90 ± 4.86 |
| pting | input-pting | 14.4 ± 3.4 | 13.0 | 60.9 | 19.00 ± 6.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|