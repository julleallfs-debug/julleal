# Base44 development notes

- The imported repository originally contained only two GIF campaign assets and Suzano font files; the preview shell was added so those assets can be viewed.
- Start with `docker compose -f docker-compose.base44.yml up -d`.
- Verify with `curl -H 'Host: external-preview.example.com' http://localhost:3000/`.
- The Vite development server reads the bind-mounted repository and provides live reload.
