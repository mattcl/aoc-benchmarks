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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.22 |
| lanjian | input-lanjian | 1.8 ± 0.3 | 1.2 | 2.9 | 1.73 ± 0.37 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.3 | 2.6 | 1.77 ± 0.36 |
| lanjian | input-chancalan | 1.9 ± 0.3 | 1.3 | 2.8 | 1.78 ± 0.37 |
| chancalan | input-chancalan | 19.5 ± 0.6 | 18.6 | 22.2 | 18.48 ± 2.95 |
| chancalan | input-mattcl | 19.6 ± 0.7 | 18.5 | 22.0 | 18.59 ± 3.00 |
| chancalan | input-lanjian | 19.8 ± 2.3 | 18.6 | 46.2 | 18.77 ± 3.67 |
| mattcl-py | input-mattcl | 33.8 ± 0.8 | 32.4 | 37.0 | 32.04 ± 5.10 |
| mattcl-py | input-chancalan | 33.9 ± 1.1 | 32.7 | 37.0 | 32.18 ± 5.16 |
| mattcl-py | input-lanjian | 34.2 ± 1.2 | 32.9 | 38.5 | 32.46 ± 5.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|