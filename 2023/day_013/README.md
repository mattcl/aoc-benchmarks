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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.30 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.02 ± 0.30 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.29 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.8 | 1.7 | 1.10 ± 0.31 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.8 | 1.14 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.16 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 2.4 | 0.7 | 35.1 | 1.26 ± 2.50 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.9 | 18.8 | 16.43 ± 3.36 |
| mattcl-py | input-pting | 16.0 ± 0.6 | 14.7 | 19.3 | 16.45 ± 3.35 |
| mattcl-py | input-mattcl | 16.1 ± 0.6 | 15.1 | 18.7 | 16.50 ± 3.35 |
| mattcl-py | input-lanjian | 16.3 ± 3.5 | 14.4 | 57.9 | 16.76 ± 4.88 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.3 | 20.0 | 17.78 ± 3.61 |
| pting | input-kcen | 17.4 ± 0.8 | 16.3 | 20.4 | 17.82 ± 3.65 |
| pting | input-pting | 17.6 ± 0.8 | 16.2 | 20.7 | 18.03 ± 3.69 |
| pting | input-mattcl | 17.6 ± 0.8 | 16.1 | 21.1 | 18.08 ± 3.70 |
| kcen | input-kcen | 20.6 ± 0.7 | 19.4 | 23.8 | 21.20 ± 4.29 |
| kcen | input-lanjian | 20.9 ± 1.5 | 19.1 | 35.6 | 21.45 ± 4.54 |
| kcen | input-pting | 21.0 ± 0.7 | 19.8 | 24.6 | 21.54 ± 4.37 |
| kcen | input-mattcl | 21.1 ± 0.7 | 20.1 | 24.3 | 21.65 ± 4.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|