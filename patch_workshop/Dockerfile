ARG DRIVER_VERSION
FROM nvcr.io/nvidia/driver:${DRIVER_VERSION}-ubuntu22.04
COPY patched/NVIDIA-Linux-x86_64-${DRIVER_VERSION}.run /drivers/NVIDIA-Linux-x86_64-$${DRIVER_VERSION}.run

ENTRYPOINT ["nvidia-driver", "init"]