# Developer pushes code → GitHub
#       ↓
# GitHub Actions triggers pipeline
#       ↓
# Build Docker Image
#        ↓
# SSH into EC2 Server
#       ↓
# Pull new code / image
#        ↓
# Stop old container
#        ↓
# Run new container

This file created and edited by `ngollodev`