# Day 13 benchmarks

[link to problem](https://adventofcode.com/2023/day/13)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 13)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.9 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.4 | 1.01 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.4 | 1.02 ± 0.36 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.4 | 1.06 ± 0.36 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.15 ± 0.41 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.15 ± 0.40 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.16 ± 0.39 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.20 ± 0.41 |
| mattcl-py | input-lanjian | 15.9 ± 0.8 | 14.8 | 18.8 | 18.35 ± 4.64 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.6 | 18.9 | 18.36 ± 4.60 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 14.6 | 18.7 | 18.47 ± 4.64 |
| mattcl-py | input-kcen | 16.2 ± 3.9 | 14.6 | 53.1 | 18.70 ± 6.44 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.1 | 20.9 | 19.91 ± 5.00 |
| pting | input-kcen | 17.2 ± 0.7 | 16.3 | 20.7 | 19.92 ± 4.99 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.1 | 20.5 | 20.09 ± 5.04 |
| pting | input-pting | 17.4 ± 0.5 | 16.7 | 19.9 | 20.15 ± 5.02 |
| kcen | input-lanjian | 20.5 ± 0.7 | 19.6 | 23.2 | 23.69 ± 5.92 |
| kcen | input-pting | 20.7 ± 0.5 | 19.9 | 22.8 | 23.95 ± 5.95 |
| kcen | input-kcen | 20.8 ± 0.8 | 19.5 | 24.2 | 23.97 ± 6.01 |
| kcen | input-mattcl | 21.0 ± 0.8 | 19.9 | 24.6 | 24.29 ± 6.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|