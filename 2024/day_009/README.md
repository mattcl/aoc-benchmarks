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
| mattcl | input-mattcl | 2.0 ± 0.4 | 0.9 | 3.1 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.3 | 1.4 | 3.0 | 1.05 ± 0.28 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.4 | 3.4 | 1.06 ± 0.29 |
| lanjian | input-kcen | 2.4 ± 0.3 | 1.5 | 3.9 | 1.22 ± 0.31 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.6 | 3.4 | 1.22 ± 0.30 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.6 | 4.6 | 1.25 ± 0.31 |
| kcen | input-lanjian | 3.8 ± 0.3 | 3.0 | 5.0 | 1.91 ± 0.44 |
| kcen | input-mattcl | 3.8 ± 0.3 | 3.0 | 5.6 | 1.91 ± 0.44 |
| kcen | input-kcen | 4.0 ± 0.3 | 3.1 | 5.5 | 2.01 ± 0.47 |
| mattcl-py | input-lanjian | 31.2 ± 0.8 | 30.2 | 34.5 | 15.54 ± 3.41 |
| mattcl-py | input-kcen | 31.3 ± 0.8 | 30.2 | 34.5 | 15.58 ± 3.43 |
| mattcl-py | input-mattcl | 31.4 ± 0.9 | 30.1 | 35.6 | 15.64 ± 3.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|