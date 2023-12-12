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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.4 | 1.05 ± 0.41 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 1.3 | 1.08 ± 0.42 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.40 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.2 | 1.11 ± 0.41 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.2 | 1.11 ± 0.39 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.3 | 1.0 | 1.12 ± 0.38 |
| lanjian | input-kcen | 0.7 ± 0.1 | 0.1 | 0.9 | 1.12 ± 0.39 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.1 | 1.13 ± 0.41 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.15 ± 0.42 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.8 | 10.9 | 14.85 ± 4.31 |
| mattcl-ts | input-pting | 9.9 ± 0.3 | 8.9 | 10.7 | 14.85 ± 4.31 |
| mattcl-ts | input-chancalan | 9.9 ± 0.4 | 8.7 | 10.7 | 14.85 ± 4.31 |
| mattcl-ts | input-kcen | 9.9 ± 0.4 | 8.8 | 11.0 | 14.89 ± 4.32 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 8.9 | 10.7 | 14.91 ± 4.32 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 13.0 | 17.0 | 20.91 ± 6.06 |
| mattcl-py | input-chancalan | 13.9 ± 0.4 | 12.8 | 16.4 | 20.93 ± 6.06 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 12.8 | 16.5 | 20.96 ± 6.08 |
| chancalan | input-pting | 13.9 ± 0.5 | 13.2 | 16.4 | 20.97 ± 6.08 |
| chancalan | input-mattcl | 13.9 ± 0.6 | 12.9 | 16.9 | 20.98 ± 6.09 |
| pting | input-kcen | 13.9 ± 0.6 | 13.0 | 17.3 | 20.98 ± 6.10 |
| kcen | input-lanjian | 13.9 ± 0.6 | 13.0 | 17.1 | 20.99 ± 6.10 |
| kcen | input-mattcl | 13.9 ± 0.5 | 13.0 | 17.1 | 21.00 ± 6.10 |
| mattcl-py | input-pting | 13.9 ± 0.6 | 13.0 | 17.8 | 21.01 ± 6.12 |
| pting | input-pting | 13.9 ± 0.6 | 13.0 | 17.0 | 21.02 ± 6.11 |
| kcen | input-pting | 13.9 ± 0.6 | 13.0 | 17.0 | 21.02 ± 6.10 |
| mattcl-py | input-mattcl | 13.9 ± 0.6 | 13.0 | 17.2 | 21.02 ± 6.11 |
| pting | input-mattcl | 13.9 ± 0.5 | 13.2 | 16.5 | 21.03 ± 6.09 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.2 | 17.5 | 21.04 ± 6.12 |
| kcen | input-kcen | 14.0 ± 0.5 | 13.0 | 16.5 | 21.06 ± 6.10 |
| kcen | input-chancalan | 14.0 ± 0.7 | 12.9 | 17.5 | 21.06 ± 6.15 |
| chancalan | input-chancalan | 14.0 ± 0.7 | 13.1 | 17.3 | 21.11 ± 6.16 |
| chancalan | input-lanjian | 14.0 ± 0.7 | 12.9 | 17.6 | 21.15 ± 6.18 |
| chancalan | input-kcen | 14.2 ± 2.8 | 12.9 | 46.8 | 21.35 ± 7.47 |
| pting | input-chancalan | 14.4 ± 4.5 | 13.0 | 60.2 | 21.78 ± 9.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|