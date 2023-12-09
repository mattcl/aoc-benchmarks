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
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.43 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.41 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.39 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.38 |
| lanjian | input-pting | 0.7 ± 0.1 | 0.1 | 0.9 | 1.08 ± 0.38 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 2.2 | 1.09 ± 0.43 |
| mattcl | input-pting | 0.7 ± 0.1 | 0.3 | 1.3 | 1.10 ± 0.37 |
| mattcl-ts | input-pting | 9.4 ± 0.4 | 8.3 | 10.2 | 13.78 ± 4.02 |
| mattcl-ts | input-lanjian | 9.4 ± 0.3 | 8.3 | 10.5 | 13.80 ± 4.02 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.4 | 10.2 | 13.86 ± 4.04 |
| mattcl-ts | input-kcen | 9.5 ± 0.3 | 8.6 | 10.3 | 13.93 ± 4.05 |
| kcen | input-kcen | 13.8 ± 0.4 | 12.9 | 16.5 | 20.36 ± 5.92 |
| kcen | input-pting | 13.9 ± 0.4 | 12.9 | 16.8 | 20.38 ± 5.92 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 12.9 | 16.8 | 20.41 ± 5.95 |
| mattcl-py | input-pting | 13.9 ± 0.6 | 12.9 | 17.2 | 20.42 ± 5.97 |
| kcen | input-lanjian | 13.9 ± 0.5 | 12.9 | 17.1 | 20.43 ± 5.95 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 13.0 | 16.9 | 20.43 ± 5.95 |
| kcen | input-mattcl | 13.9 ± 0.5 | 13.0 | 17.1 | 20.43 ± 5.95 |
| mattcl-py | input-mattcl | 13.9 ± 0.5 | 13.2 | 17.1 | 20.45 ± 5.96 |
| pting | input-pting | 13.9 ± 0.6 | 13.1 | 17.3 | 20.45 ± 5.97 |
| pting | input-mattcl | 13.9 ± 0.6 | 13.2 | 17.2 | 20.49 ± 5.99 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.2 | 17.1 | 20.54 ± 6.00 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 17.1 | 20.54 ± 6.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|