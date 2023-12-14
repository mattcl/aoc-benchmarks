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
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.3 | 1.00 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 ± 0.40 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.4 | 1.02 ± 0.43 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.38 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.0 | 1.5 | 1.07 ± 0.41 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.08 ± 0.40 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.1 | 1.0 | 1.08 ± 0.38 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.10 ± 0.40 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.11 ± 0.42 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.2 | 1.3 | 1.15 ± 0.40 |
| mattcl-ts | input-pting | 10.0 ± 0.3 | 8.8 | 11.0 | 14.18 ± 4.23 |
| mattcl-ts | input-lanjian | 10.0 ± 0.4 | 8.9 | 11.2 | 14.19 ± 4.23 |
| mattcl-ts | input-chancalan | 10.0 ± 0.3 | 8.9 | 11.1 | 14.21 ± 4.23 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 8.9 | 11.3 | 14.21 ± 4.24 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 8.9 | 11.7 | 14.22 ± 4.24 |
| kcen | input-chancalan | 14.1 ± 0.5 | 13.2 | 16.9 | 20.00 ± 5.97 |
| chancalan | input-chancalan | 14.1 ± 0.5 | 12.9 | 16.6 | 20.01 ± 5.97 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.4 | 17.4 | 20.04 ± 6.00 |
| kcen | input-kcen | 14.1 ± 0.6 | 13.3 | 16.9 | 20.04 ± 5.99 |
| pting | input-kcen | 14.1 ± 0.5 | 13.3 | 17.2 | 20.05 ± 5.99 |
| pting | input-lanjian | 14.1 ± 0.5 | 12.9 | 17.0 | 20.06 ± 5.98 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.2 | 17.0 | 20.06 ± 6.00 |
| pting | input-chancalan | 14.1 ± 0.6 | 13.2 | 17.5 | 20.07 ± 6.01 |
| kcen | input-lanjian | 14.1 ± 0.5 | 13.0 | 17.2 | 20.08 ± 6.00 |
| chancalan | input-pting | 14.1 ± 0.8 | 13.2 | 17.8 | 20.11 ± 6.05 |
| pting | input-pting | 14.1 ± 0.6 | 13.2 | 17.6 | 20.11 ± 6.02 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.3 | 17.4 | 20.12 ± 6.03 |
| pting | input-mattcl | 14.2 ± 0.7 | 12.9 | 18.1 | 20.13 ± 6.05 |
| chancalan | input-lanjian | 14.2 ± 0.8 | 12.9 | 17.5 | 20.16 ± 6.07 |
| mattcl-py | input-chancalan | 14.2 ± 0.7 | 12.9 | 17.1 | 20.19 ± 6.06 |
| mattcl-py | input-mattcl | 14.2 ± 0.7 | 13.2 | 18.3 | 20.19 ± 6.05 |
| kcen | input-pting | 14.2 ± 0.6 | 13.2 | 17.2 | 20.20 ± 6.05 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.5 | 17.2 | 20.23 ± 6.05 |
| mattcl-py | input-kcen | 14.2 ± 0.7 | 13.3 | 17.7 | 20.24 ± 6.08 |
| mattcl-py | input-pting | 14.5 ± 3.1 | 13.3 | 56.8 | 20.65 ± 7.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|