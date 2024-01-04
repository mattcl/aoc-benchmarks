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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 2.2 | 1.01 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.34 |
| lanjian | input-lanjian | 1.1 ± 0.3 | 0.7 | 1.7 | 1.14 ± 0.39 |
| lanjian | input-mattcl | 1.1 ± 0.4 | 0.7 | 4.6 | 1.14 ± 0.47 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.6 | 1.6 | 1.16 ± 0.38 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.38 |
| mattcl-py | input-lanjian | 15.8 ± 0.7 | 14.6 | 19.8 | 17.12 ± 4.03 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 14.5 | 18.3 | 17.33 ± 4.07 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 14.7 | 19.3 | 17.37 ± 4.09 |
| mattcl-py | input-kcen | 16.0 ± 2.4 | 14.6 | 45.7 | 17.40 ± 4.77 |
| pting | input-kcen | 17.0 ± 0.7 | 16.0 | 20.6 | 18.40 ± 4.31 |
| pting | input-pting | 17.2 ± 0.7 | 15.8 | 20.0 | 18.63 ± 4.37 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.0 | 19.7 | 18.73 ± 4.38 |
| pting | input-lanjian | 17.3 ± 1.1 | 15.9 | 23.1 | 18.73 ± 4.50 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.7 | 23.4 | 21.73 ± 5.09 |
| kcen | input-kcen | 20.4 ± 3.1 | 18.7 | 56.5 | 22.16 ± 6.12 |
| kcen | input-pting | 20.5 ± 0.7 | 19.0 | 23.4 | 22.25 ± 5.21 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.1 | 23.6 | 22.38 ± 5.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|