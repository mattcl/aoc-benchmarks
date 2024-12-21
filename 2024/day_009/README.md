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
| mattcl | input-kcen | 2.1 ± 0.3 | 1.4 | 3.1 | 1.00 |
| mattcl | input-mattcl | 2.1 ± 0.4 | 1.3 | 3.8 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 2.2 ± 0.4 | 1.2 | 3.9 | 1.03 ± 0.23 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.8 | 4.2 | 1.17 ± 0.23 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.6 | 4.2 | 1.17 ± 0.23 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.4 | 3.8 | 1.19 ± 0.22 |
| kcen | input-lanjian | 3.8 ± 0.2 | 3.0 | 4.5 | 1.79 ± 0.30 |
| kcen | input-mattcl | 4.0 ± 0.4 | 3.0 | 5.6 | 1.87 ± 0.35 |
| kcen | input-kcen | 4.0 ± 0.5 | 3.2 | 7.4 | 1.87 ± 0.37 |
| mattcl-py | input-mattcl | 31.1 ± 0.6 | 30.2 | 33.3 | 14.64 ± 2.26 |
| mattcl-py | input-kcen | 31.3 ± 0.8 | 30.3 | 34.3 | 14.73 ± 2.29 |
| mattcl-py | input-lanjian | 31.4 ± 1.0 | 30.3 | 34.5 | 14.78 ± 2.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|