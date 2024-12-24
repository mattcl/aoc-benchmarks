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
| mattcl | input-lanjian | 2.2 ± 0.5 | 0.9 | 3.1 | 1.00 |
| mattcl | input-mattcl | 2.3 ± 0.3 | 1.3 | 3.1 | 1.02 ± 0.26 |
| mattcl | input-kcen | 2.3 ± 0.3 | 1.4 | 3.2 | 1.02 ± 0.26 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.1 | 3.5 | 1.13 ± 0.26 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.4 | 3.2 | 1.14 ± 0.26 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.8 | 3.8 | 1.16 ± 0.26 |
| kcen | input-lanjian | 3.7 ± 0.5 | 2.6 | 6.5 | 1.68 ± 0.41 |
| kcen | input-mattcl | 4.0 ± 0.4 | 3.1 | 6.6 | 1.78 ± 0.40 |
| kcen | input-kcen | 4.1 ± 0.4 | 3.4 | 5.5 | 1.85 ± 0.41 |
| mattcl-py | input-kcen | 31.9 ± 0.9 | 30.3 | 35.5 | 14.36 ± 2.95 |
| mattcl-py | input-lanjian | 32.0 ± 0.9 | 30.2 | 34.6 | 14.40 ± 2.96 |
| mattcl-py | input-mattcl | 32.0 ± 1.7 | 30.5 | 46.3 | 14.41 ± 3.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|