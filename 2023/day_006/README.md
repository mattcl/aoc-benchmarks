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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.4 | 1.01 ± 0.45 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.3 | 1.03 ± 0.39 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.1 | 1.07 ± 0.39 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.2 | 2.6 | 1.07 ± 0.43 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.09 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.09 ± 0.41 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.3 | 1.2 | 1.09 ± 0.36 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 0.9 | 1.10 ± 0.39 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.6 | 1.11 ± 0.39 |
| mattcl-ts | input-mattcl | 9.8 ± 0.4 | 8.8 | 10.7 | 14.03 ± 3.99 |
| mattcl-ts | input-pting | 9.8 ± 0.4 | 8.7 | 10.8 | 14.05 ± 4.00 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 8.6 | 10.7 | 14.07 ± 4.00 |
| mattcl-ts | input-lanjian | 9.8 ± 0.4 | 8.9 | 10.9 | 14.07 ± 4.00 |
| mattcl-ts | input-chancalan | 9.9 ± 0.4 | 8.7 | 10.5 | 14.14 ± 4.02 |
| mattcl-py | input-chancalan | 14.1 ± 0.5 | 13.2 | 16.5 | 20.21 ± 5.73 |
| chancalan | input-chancalan | 14.1 ± 0.5 | 13.1 | 16.4 | 20.22 ± 5.74 |
| pting | input-mattcl | 14.2 ± 0.5 | 13.1 | 17.4 | 20.31 ± 5.77 |
| chancalan | input-kcen | 14.2 ± 0.6 | 13.2 | 16.8 | 20.32 ± 5.79 |
| pting | input-kcen | 14.2 ± 0.6 | 13.1 | 17.8 | 20.33 ± 5.78 |
| pting | input-pting | 14.2 ± 0.5 | 13.2 | 17.4 | 20.34 ± 5.77 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.0 | 17.6 | 20.35 ± 5.80 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.1 | 17.5 | 20.37 ± 5.81 |
| chancalan | input-lanjian | 14.2 ± 0.7 | 13.2 | 18.1 | 20.39 ± 5.82 |
| mattcl-py | input-lanjian | 14.2 ± 0.8 | 13.0 | 17.3 | 20.40 ± 5.85 |
| pting | input-chancalan | 14.3 ± 0.6 | 13.3 | 17.4 | 20.44 ± 5.83 |
| chancalan | input-pting | 14.3 ± 0.7 | 13.0 | 17.6 | 20.44 ± 5.86 |
| kcen | input-pting | 14.3 ± 1.6 | 13.1 | 35.1 | 20.46 ± 6.22 |
| mattcl-py | input-pting | 14.3 ± 0.7 | 13.3 | 17.5 | 20.46 ± 5.85 |
| kcen | input-kcen | 14.3 ± 0.6 | 13.2 | 17.7 | 20.46 ± 5.84 |
| kcen | input-chancalan | 14.3 ± 0.7 | 13.3 | 17.1 | 20.47 ± 5.84 |
| kcen | input-mattcl | 14.3 ± 0.7 | 13.0 | 17.6 | 20.48 ± 5.86 |
| kcen | input-lanjian | 14.3 ± 0.7 | 13.0 | 17.9 | 20.49 ± 5.85 |
| mattcl-py | input-mattcl | 14.4 ± 1.9 | 13.1 | 40.5 | 20.57 ± 6.42 |
| chancalan | input-mattcl | 14.5 ± 0.6 | 13.6 | 17.3 | 20.84 ± 5.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|