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
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.32 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.34 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.34 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.2 | 1.10 ± 0.33 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.2 | 1.12 ± 0.32 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.7 | 11.6 | 11.66 ± 2.74 |
| mattcl-ts | input-mattcl | 10.1 ± 0.4 | 9.0 | 11.1 | 11.81 ± 2.78 |
| mattcl-ts | input-pting | 10.2 ± 0.4 | 9.1 | 11.8 | 11.98 ± 2.81 |
| mattcl-ts | input-kcen | 10.7 ± 0.5 | 9.5 | 12.1 | 12.55 ± 2.96 |
| pting | input-mattcl | 14.2 ± 0.5 | 13.3 | 17.5 | 16.71 ± 3.93 |
| kcen | input-pting | 14.3 ± 0.7 | 13.1 | 18.0 | 16.77 ± 3.98 |
| mattcl-py | input-pting | 14.3 ± 0.7 | 13.2 | 17.5 | 16.80 ± 3.97 |
| pting | input-pting | 14.3 ± 0.5 | 13.4 | 17.3 | 16.80 ± 3.95 |
| kcen | input-mattcl | 14.4 ± 2.8 | 13.3 | 54.1 | 16.96 ± 5.16 |
| pting | input-lanjian | 14.5 ± 0.6 | 13.4 | 17.0 | 16.97 ± 4.00 |
| mattcl-py | input-mattcl | 14.5 ± 3.6 | 13.1 | 64.9 | 17.08 ± 5.83 |
| pting | input-kcen | 14.6 ± 0.6 | 13.6 | 17.4 | 17.20 ± 4.05 |
| mattcl-py | input-lanjian | 14.7 ± 0.5 | 13.7 | 17.0 | 17.21 ± 4.04 |
| kcen | input-lanjian | 14.9 ± 2.6 | 13.5 | 50.4 | 17.48 ± 5.07 |
| mattcl-py | input-kcen | 15.2 ± 0.4 | 14.4 | 17.2 | 17.86 ± 4.17 |
| kcen | input-kcen | 15.2 ± 0.3 | 14.4 | 17.1 | 17.88 ± 4.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|