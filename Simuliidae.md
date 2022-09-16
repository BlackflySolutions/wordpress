# Simuliidae

## Purpose

The Simuliidae project uses this modified version of the Wordpress docker project to generate base images that are further enhanced/extended in the build directory.

## Contents
 
This directory contains a lightly forked version of the official wordpress docker project.

It's forked only in the Docker.template file
1. It converts the build to a multistage so we can build a version without the wordpress code, i.e. a "bare" container.

To see details of the changes, use:

git diff master origin/master

