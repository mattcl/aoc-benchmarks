# Day 18 benchmarks

[link to problem](https://adventofcode.com/2023/day/18)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 18)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 881.6 ± 218.9 | 185.8 | 1537.2 | 1.00 |
| lanjian | input-pting | 887.5 ± 165.2 | 201.7 | 1321.2 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 888.0 ± 202.3 | 150.4 | 1556.6 | 1.01 ± 0.34 |
| mattcl | input-pting | 896.0 ± 155.7 | 345.4 | 1071.1 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 906.7 ± 166.6 | 182.5 | 1234.9 | 1.03 ± 0.32 |
| lanjian | input-lanjian | 914.2 ± 137.1 | 262.6 | 1122.2 | 1.04 ± 0.30 |
| mattcl-py | input-pting | 14343.3 ± 627.4 | 13255.8 | 17344.7 | 16.27 ± 4.10 |
| mattcl-py | input-lanjian | 14428.4 ± 750.5 | 13343.3 | 18225.0 | 16.37 ± 4.15 |
| pting | input-lanjian | 14573.2 ± 573.1 | 13509.5 | 17607.0 | 16.53 ± 4.15 |
| pting | input-pting | 14597.1 ± 766.5 | 13619.0 | 17993.2 | 16.56 ± 4.20 |
| mattcl-py | input-mattcl | 14749.3 ± 737.6 | 13696.7 | 17999.5 | 16.73 ± 4.24 |
| pting | input-mattcl | 15022.8 ± 567.4 | 13977.5 | 18390.2 | 17.04 ± 4.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|