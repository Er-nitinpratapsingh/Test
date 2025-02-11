#!/bin/bash

while true; do
    inotifywait -r -e modify,create,delete /var/www/Test
    git add .
    git commit -m "Auto-commit: Detected file changes"
done
