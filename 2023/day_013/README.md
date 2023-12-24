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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.34 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.34 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.05 ± 0.34 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.37 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.37 |
| lanjian | input-kcen | 1.1 ± 0.3 | 0.7 | 1.6 | 1.17 ± 0.40 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.38 |
| mattcl-py | input-pting | 16.3 ± 3.6 | 14.8 | 55.2 | 18.04 ± 5.84 |
| pting | input-lanjian | 16.7 ± 0.5 | 15.8 | 19.3 | 18.46 ± 4.36 |
| mattcl-py | input-mattcl | 16.7 ± 2.8 | 14.7 | 25.0 | 18.50 ± 5.31 |
| mattcl-py | input-lanjian | 16.8 ± 2.7 | 14.7 | 26.5 | 18.54 ± 5.29 |
| mattcl-py | input-kcen | 16.9 ± 3.1 | 14.7 | 30.8 | 18.65 ± 5.54 |
| pting | input-kcen | 17.2 ± 0.5 | 15.9 | 19.8 | 19.03 ± 4.50 |
| pting | input-mattcl | 17.2 ± 0.5 | 16.2 | 19.7 | 19.05 ± 4.50 |
| pting | input-pting | 18.2 ± 3.0 | 16.2 | 27.1 | 20.16 ± 5.78 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.1 | 22.8 | 22.29 ± 5.26 |
| kcen | input-mattcl | 20.3 ± 0.6 | 19.3 | 22.7 | 22.46 ± 5.31 |
| kcen | input-pting | 20.4 ± 0.6 | 19.4 | 23.1 | 22.59 ± 5.34 |
| kcen | input-lanjian | 20.4 ± 0.6 | 19.3 | 23.1 | 22.59 ± 5.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|