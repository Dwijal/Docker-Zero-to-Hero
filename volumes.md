# Docker Volumes

## Problem Statement

It is a very common requirement to persist the data in a Docker container beyond the lifetime of the container. However, the file system
of a Docker container is deleted/removed when the container dies. 

## Solution


![Screenshot (2414)](https://github.com/user-attachments/assets/7206e01a-a7e9-4b9c-bb18-0cf4c705c86c)

## Commands

#### - docker volume ls

List All Volumes:

#### - docker volume inspect my-volume

Inspect a Volume:

#### - docker volume rm my-volume

Remove a Volume

#### - docker volume prune

Remove Unused Volumes
## Key Differences between Volumes and Bind Directory on a host as a Mount

Volumes are managed, created, mounted and deleted using the Docker API. However, Volumes are more flexible than bind mounts, as 
they can be managed and backed up separately from the host file system, and can be moved between containers and hosts.

In a nutshell, Bind Directory on a host as a Mount are appropriate for simple use cases where you need to mount a directory from the host file system into
a container, while volumes are better suited for more complex use cases where you need more control over the data being persisted
in the container.
