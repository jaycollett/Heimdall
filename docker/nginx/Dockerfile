# Pinned to an explicit minor tag rather than the floating `nginx:alpine`.
# A floating tag makes the image non-reproducible and hides base drift; freshness
# comes from the scheduled rebuild, not from an unpinned tag.
# (Container hardening pass, 2026-07-29.)
FROM nginx:1.29-alpine
COPY ./default.conf /etc/nginx/conf.d