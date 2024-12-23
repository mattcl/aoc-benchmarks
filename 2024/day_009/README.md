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
| mattcl | input-mattcl | 2.3 ± 0.3 | 1.4 | 3.1 | 1.00 |
| mattcl | input-kcen | 2.3 ± 0.3 | 1.4 | 3.4 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 2.3 ± 0.3 | 1.4 | 3.8 | 1.01 ± 0.22 |
| lanjian | input-kcen | 2.3 ± 0.5 | 1.0 | 4.5 | 1.02 ± 0.27 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.6 | 3.5 | 1.12 ± 0.22 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.7 | 4.4 | 1.15 ± 0.21 |
| kcen | input-lanjian | 3.8 ± 0.3 | 3.1 | 6.3 | 1.69 ± 0.29 |
| kcen | input-kcen | 3.9 ± 0.4 | 2.8 | 5.3 | 1.73 ± 0.32 |
| kcen | input-mattcl | 4.0 ± 0.4 | 3.1 | 6.3 | 1.75 ± 0.32 |
| mattcl-py | input-kcen | 31.6 ± 0.9 | 30.5 | 34.3 | 13.97 ± 2.15 |
| mattcl-py | input-lanjian | 31.7 ± 1.0 | 30.0 | 35.1 | 14.01 ± 2.17 |
| mattcl-py | input-mattcl | 31.8 ± 1.0 | 30.4 | 35.0 | 14.06 ± 2.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|