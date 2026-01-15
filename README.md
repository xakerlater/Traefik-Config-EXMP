# Traefik-Config-EXMP

This repository contains an example configuration of the Traefik reverse proxy
with a request rate limiting mechanism.

The configuration was created as part of a project for the regional stage of the
All-Russian School Olympiad in Informatics (Information Security track).

## Description

The presented configuration demonstrates the use of Traefik middleware
to limit the number of incoming HTTP requests to a web service.
This approach can be used as a basic measure to increase the stability
of web services under high load conditions.

## Contents

- `traefik.yml` — example Traefik configuration with rate limiting middleware

## Notes

The configuration is intended for educational and demonstration purposes only
and was tested in a controlled environment on a test web service.
