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
| mattcl | input-mattcl | 2.1 ± 0.4 | 1.3 | 3.1 | 1.00 |
| mattcl | input-kcen | 2.2 ± 0.4 | 1.0 | 3.6 | 1.01 ± 0.24 |
| mattcl | input-lanjian | 2.2 ± 0.4 | 1.4 | 3.5 | 1.03 ± 0.25 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.6 | 4.1 | 1.18 ± 0.24 |
| lanjian | input-kcen | 2.5 ± 0.2 | 1.8 | 3.2 | 1.18 ± 0.23 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.6 | 4.4 | 1.18 ± 0.25 |
| kcen | input-lanjian | 3.8 ± 0.3 | 3.0 | 6.5 | 1.80 ± 0.34 |
| kcen | input-kcen | 3.9 ± 0.3 | 3.2 | 5.4 | 1.82 ± 0.34 |
| kcen | input-mattcl | 3.9 ± 0.4 | 3.0 | 6.6 | 1.84 ± 0.37 |
| mattcl-py | input-mattcl | 31.3 ± 0.8 | 30.3 | 34.1 | 14.65 ± 2.54 |
| mattcl-py | input-kcen | 31.4 ± 0.8 | 30.3 | 34.5 | 14.69 ± 2.55 |
| mattcl-py | input-lanjian | 31.5 ± 1.1 | 30.5 | 35.3 | 14.75 ± 2.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|