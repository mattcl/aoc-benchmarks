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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.1 | 1.00 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.2 | 1.01 ± 0.35 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.01 ± 0.35 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.0 | 1.03 ± 0.35 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.0 | 1.03 ± 0.35 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.40 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.40 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.06 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.2 | 1.0 | 1.10 ± 0.35 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.3 | 1.0 | 1.13 ± 0.34 |
| mattcl-ts | input-lanjian | 9.8 ± 0.4 | 8.7 | 10.5 | 13.80 ± 3.61 |
| mattcl-ts | input-pting | 9.8 ± 0.4 | 8.8 | 10.5 | 13.85 ± 3.63 |
| mattcl-ts | input-kcen | 9.8 ± 0.3 | 9.1 | 10.6 | 13.85 ± 3.62 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 9.0 | 10.7 | 13.90 ± 3.64 |
| mattcl-ts | input-chancalan | 9.9 ± 0.3 | 8.7 | 11.1 | 13.95 ± 3.65 |
| mattcl-py | input-lanjian | 13.9 ± 0.3 | 12.8 | 15.5 | 19.50 ± 5.08 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 13.0 | 16.7 | 19.56 ± 5.12 |
| chancalan | input-pting | 13.9 ± 0.5 | 12.9 | 16.7 | 19.56 ± 5.12 |
| kcen | input-kcen | 13.9 ± 0.5 | 13.1 | 17.2 | 19.56 ± 5.12 |
| chancalan | input-lanjian | 13.9 ± 0.5 | 13.0 | 16.5 | 19.57 ± 5.12 |
| kcen | input-lanjian | 13.9 ± 0.5 | 13.0 | 16.7 | 19.57 ± 5.12 |
| mattcl-py | input-mattcl | 13.9 ± 0.5 | 12.8 | 17.2 | 19.58 ± 5.13 |
| mattcl-py | input-chancalan | 13.9 ± 0.6 | 13.1 | 16.7 | 19.59 ± 5.16 |
| chancalan | input-mattcl | 13.9 ± 0.6 | 12.8 | 17.1 | 19.59 ± 5.15 |
| pting | input-chancalan | 13.9 ± 0.5 | 13.0 | 17.2 | 19.59 ± 5.14 |
| chancalan | input-chancalan | 13.9 ± 0.5 | 12.8 | 17.0 | 19.60 ± 5.13 |
| chancalan | input-kcen | 13.9 ± 0.5 | 12.9 | 17.1 | 19.61 ± 5.15 |
| mattcl-py | input-pting | 14.0 ± 0.6 | 13.1 | 16.9 | 19.63 ± 5.16 |
| kcen | input-mattcl | 14.0 ± 0.5 | 13.0 | 17.3 | 19.65 ± 5.14 |
| pting | input-kcen | 14.0 ± 0.5 | 13.1 | 17.1 | 19.65 ± 5.14 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.0 | 16.7 | 19.67 ± 5.18 |
| pting | input-pting | 14.0 ± 0.6 | 13.1 | 17.4 | 19.67 ± 5.18 |
| pting | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.2 | 19.71 ± 5.19 |
| kcen | input-chancalan | 14.0 ± 0.7 | 12.9 | 17.5 | 19.71 ± 5.20 |
| kcen | input-pting | 14.1 ± 0.7 | 12.8 | 17.3 | 19.77 ± 5.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|