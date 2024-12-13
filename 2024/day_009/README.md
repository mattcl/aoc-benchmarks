# Day 9 benchmarks

[link to problem](https://adventofcode.com/2024/day/9)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 9)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 2.1 ± 0.4 | 0.9 | 3.1 | 1.00 |
| mattcl | input-lanjian | 2.2 ± 0.3 | 1.4 | 2.9 | 1.07 ± 0.25 |
| mattcl | input-mattcl | 2.2 ± 0.4 | 1.4 | 3.5 | 1.08 ± 0.27 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.1 | 3.9 | 1.22 ± 0.27 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.6 | 3.3 | 1.23 ± 0.26 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.6 | 4.6 | 1.24 ± 0.28 |
| kcen | input-lanjian | 3.9 ± 0.5 | 3.0 | 7.3 | 1.86 ± 0.42 |
| kcen | input-mattcl | 3.9 ± 0.5 | 3.1 | 7.1 | 1.89 ± 0.42 |
| kcen | input-kcen | 4.1 ± 0.5 | 3.1 | 7.3 | 1.96 ± 0.44 |
| mattcl-py | input-lanjian | 31.5 ± 0.8 | 30.2 | 34.7 | 15.21 ± 2.87 |
| mattcl-py | input-kcen | 31.7 ± 1.6 | 30.5 | 45.0 | 15.30 ± 2.96 |
| mattcl-py | input-mattcl | 31.8 ± 1.0 | 30.4 | 35.3 | 15.36 ± 2.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|