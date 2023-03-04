```sh
docker stats --format "table {{.Name}}\t{{.Container}}\t{{.CPUPerc}}\t{{.MemUsage}}"
```

| NAME | CONTAINER | CPU % | MEM USAGE / LIMIT |
| --- | --- | --- | --- |
| test | abcd1234 | 0.00% | 0.0MiB / 10.001GiB |

이렇게 보임

htop의 Docker 버전 같은 느낌
