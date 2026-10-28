# FestPass – Docker & Container Security Assessment

| Item | Value |
|---|---|
| Name | Naman Jadiya |
| REGNO | 202401100200208 |
| PORT | 8075 |
| Docker Hub user | namannn1869 |
| Docker Hub repo | https://hub.docker.com/r/namannn1869/fest-backend |

## AI tools used
- Claude: Dockerfiles, compose.yaml, commands and troubleshooting errors.

## 1.0.0 digest
krishtech08/fest-backend:1.0.0 @ sha256:40be1a0e6b08927d972fd069b0c0088dfcd9c9f8aa48fb0a904491893fe16d9b (signed with cosign, verified with cosign.pub)

## Trivy before and after
| Image | Base | CRITICAL | HIGH | Size |
|---|---|---|---|---|
| fest-backend:0.1 | python:3.9 | 234 | 2249 | 1.11GB |
| fest-backend:0.2 | python:3.13-slim | see below | see below | 136MB |

After-scan totals:
```
Total: 164 (UNKNOWN: 1, LOW: 61, MEDIUM: 58, HIGH: 44, CRITICAL: 0)
Total: 8 (UNKNOWN: 0, LOW: 1, MEDIUM: 2, HIGH: 5, CRITICAL: 0)
```

## Steps not completed
- 2.4: S2-4 screenshot missing.
- 4.2: Docker Hub tags screenshot not taken (ran out of time).
- 4.3: compose not switched to the Docker Hub image (ran out of time).
- 5.4: unsigned 1.0.1 not built (ran out of time).
