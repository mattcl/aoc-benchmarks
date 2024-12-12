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
| mattcl | input-lanjian | 2.0 ± 0.3 | 1.3 | 2.8 | 1.00 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.6 | 3.9 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 2.1 ± 0.4 | 1.4 | 3.5 | 1.05 ± 0.24 |
| lanjian | input-kcen | 2.4 ± 0.3 | 1.5 | 3.4 | 1.21 ± 0.24 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.5 | 4.5 | 1.22 ± 0.25 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.4 | 3.7 | 1.22 ± 0.23 |
| kcen | input-lanjian | 3.8 ± 0.4 | 3.0 | 7.5 | 1.88 ± 0.35 |
| kcen | input-kcen | 3.9 ± 0.3 | 3.1 | 5.6 | 1.90 ± 0.33 |
| kcen | input-mattcl | 3.9 ± 0.5 | 3.0 | 7.2 | 1.91 ± 0.37 |
| mattcl-py | input-mattcl | 31.0 ± 0.5 | 30.0 | 32.9 | 15.30 ± 2.32 |
| mattcl-py | input-kcen | 31.2 ± 0.8 | 30.1 | 34.0 | 15.40 ± 2.36 |
| mattcl-py | input-lanjian | 31.3 ± 0.9 | 29.9 | 34.3 | 15.41 ± 2.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|