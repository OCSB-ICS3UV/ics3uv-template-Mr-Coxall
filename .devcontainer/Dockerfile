FROM denoland/deno:bin-2.0.0 AS deno
FROM mcr.microsoft.com/devcontainers/universal
COPY --from=deno /deno /usr/local/bin/deno
