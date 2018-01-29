# Choosing an image

- The image must be the closes possible to the image used in production, or the same, to avoid surprises while publishing and maintaining the software
- The image has to be compatible with the execution environment, that means it should support every tool and libs that the application uses to run

## The smallest distros

- Apline Linux
- Debian Slim
- Busybox
- Scratch (The simplest image)
- Distroless (Does not have a shell, usually very safe and small)

## Vulnerabilities

- Most dockerhub images have vulnerabilities (last research showed more than 60% of the images had vulnerabilities)
