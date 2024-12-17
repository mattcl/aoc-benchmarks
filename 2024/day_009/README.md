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
| mattcl | input-kcen | 2.2 ± 0.4 | 0.9 | 3.5 | 1.00 |
| mattcl | input-lanjian | 2.2 ± 0.3 | 1.4 | 3.5 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 2.3 ± 0.3 | 1.3 | 3.0 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 2.4 ± 0.4 | 1.1 | 3.4 | 1.08 ± 0.25 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.4 | 3.9 | 1.13 ± 0.24 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.6 | 3.7 | 1.14 ± 0.24 |
| kcen | input-lanjian | 3.8 ± 0.3 | 2.9 | 4.9 | 1.74 ± 0.33 |
| kcen | input-mattcl | 3.9 ± 0.4 | 3.0 | 6.4 | 1.76 ± 0.34 |
| kcen | input-kcen | 4.0 ± 0.4 | 3.1 | 6.5 | 1.82 ± 0.37 |
| mattcl-py | input-mattcl | 31.6 ± 0.8 | 30.3 | 34.2 | 14.41 ± 2.51 |
| mattcl-py | input-kcen | 31.7 ± 1.0 | 30.1 | 34.9 | 14.43 ± 2.52 |
| mattcl-py | input-lanjian | 31.7 ± 0.9 | 30.5 | 34.6 | 14.43 ± 2.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|