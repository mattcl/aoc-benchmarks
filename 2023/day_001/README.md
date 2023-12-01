# Day 1 benchmarks

[link to problem](https://adventofcode.com/2023/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 2.0 ± 0.3 | 1.5 | 3.5 | 1.86 ± 0.42 |
| lanjian | input-chancalan | 2.1 ± 0.3 | 1.4 | 2.8 | 1.90 ± 0.40 |
| lanjian | input-lanjian | 2.1 ± 0.3 | 1.3 | 3.4 | 1.92 ± 0.43 |
| chancalan | input-mattcl | 19.8 ± 0.7 | 18.6 | 23.0 | 18.28 ± 2.78 |
| chancalan | input-chancalan | 19.9 ± 0.7 | 18.8 | 22.4 | 18.37 ± 2.80 |
| chancalan | input-lanjian | 19.9 ± 0.8 | 18.7 | 23.0 | 18.41 ± 2.82 |
| mattcl-py | input-mattcl | 34.2 ± 1.0 | 32.4 | 37.4 | 31.63 ± 4.76 |
| mattcl-py | input-chancalan | 34.3 ± 0.9 | 32.8 | 37.6 | 31.67 ± 4.76 |
| mattcl-py | input-lanjian | 34.4 ± 1.1 | 32.6 | 37.6 | 31.78 ± 4.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|